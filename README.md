# Library Management System
We have created a relational database management system for REAL (Read,Edify, and Learn). It is a Library Management System. REAL maintains records of the individual customer and the list of books issued by them, upcoming events/exhibitions, inventory details,
and invoices generated. A customer can book a room in the library for their preferred time slotand can select books from a wide range of genres depending on their availability. Once a book isissued by the customer, an estimated return date is reflected on the customer's profile and invoice
is generated for him/her, and payments are made against those bills. Similarly, a separate login page is made for the admin from where he can see the list of customers who have issued books currently and can also view the older issuance records. Admin also see the rooms that have been
booked with their respective time slots. Our website also gives the admin the flexibility to add or delete books from the inventory which is reflected in real-time on the user page also.

The system allows users to update their personal details from the login page using stored
procedures. This provides flexibility and convenience to the users, as they can easily make
changes to their information as needed. The system has separate login pages for both users and
admins. This helps to ensure that each group has access to only the features and resources that
are relevant to them. To ensure the security of the user's account, the system requires the user to
select 3 security questions from a dropdown list during the registration process. This allows the
user to reset their password in the event that they forget it in the future. The password is also
protected using SHA-256 encryption to further enhance security.

Customers are able to book rooms in advance on the system. When a room is booked, it is locked
for the specified date and time to prevent other users from booking it during that period. The
system is able to handle concurrent transactions when multiple users try to reserve the same
resources. This ensures that the system is able to handle a high volume of requests and
reservations without experiencing delays or errors. There is a user function in the system that
allows users to retrieve the time slot for room booking based on the character value stored in the
backend. This function helps to streamline the booking process and make it easier for users to
find available time slots.

To protect against SQL injection attacks and ensure the security of user data, the system makes
use of stored procedures and sanitizes form inputs. This helps to prevent malicious users from
accessing or altering sensitive data. As the data size increases, it may be necessary to analyze the
tables and make use of indexing to increase the query processing speed. This will help to ensure
that the system remains efficient and responsive even as the volume of data grows.
