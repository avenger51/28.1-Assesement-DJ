### Conceptual Exercise
### Completed 11/2/23 6:12PM
Answer the following questions below:

- What is PostgreSQL?
A: PostgreSQL is an object-relational database management system (ORDBMS).

- What is the difference between SQL and PostgreSQL?
A: PostgreSQL is open source and SQL Server is owned by Microsoft.

- In `psql`, how do you connect to a database?
A: psql database_name

- What is the difference between `HAVING` and `WHERE`?
A: HAVING: Filter results of a grouped query and used often with GROUP BY.
   WHERE: Used to filter individual rows from a table.

- What is the difference between an `INNER` and `OUTER` join?
A: An INNER join is joining when the rows match the condition in both tables.  An OUTER join
is returns all the rows from one table and matching rows from other table.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
A: LEFT - ALL of the rows from the first table (left), combined with
MATCHING rows from the second table (right)

RIGHT - The MATCHING rows from the first table (left), combined with
ALL the rows from the second table (right)

- What is an ORM? What do they do?
A: ORM (object relation mapping) is a translation service between OOP, Python, and SQL syntax.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
A: AJAX is an asynchronous request for a web page while requests can be both synchronous and asynchronous. 

- What is CSRF? What is the purpose of the CSRF token?
A: Cross-Site Request Forgery (CSRF) is an attack that forces authenticated users to submit a request to a Web application against which they are currently authenticated. CSRF attacks exploit the trust a Web application has in an authenticated user. A CSRF token is a secure, random token that is used to prevent cross-site request forgery attacks.

- What is the purpose of `form.hidden_tag()`?
A: It is used to hide input fields used to store data that is being submitted but should not be visible or editable by the user.  It
is generally used for CSRF purposes.