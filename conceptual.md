### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
PostgreSQL is a relational database management system that uses and extends the SQL language and allows us to interact with our database.

- What is the difference between SQL and PostgreSQL?
SQL is an advanced database management system, and PostgreSQL is an advanced, extended version of SQL that adds more functionality to SQL.

- In `psql`, how do you connect to a database?
psql db_name

- What is the difference between `HAVING` and `WHERE`?
WHERE filters table by the alues of specific rows. HAVING selects groups of information, i.e. authors with multiple books.

- What is the difference between an `INNER` and `OUTER` join?
INNER join only selects the information with matching information, and anything that is missing a piece of the information is left out. OUTER join joins all rows from both tables. 

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
LEFT join selects all rows from first tsble, combined with matching rows from second table. RIGHT join selects the matching rows from first table, combined with all rows from the second table.

- What is an ORM? What do they do?
Object-relational mapping, creates an object that maps to relational data.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
An ajax request waits for the data to load before displaying on the page. A regular server-side library can handle the entire request at once. 
<!-- what else??? -->
- What is CSRF? What is the purpose of the CSRF token?
Cross-Site Request Forgery, exploits the privilege of a user on a particular website and uses secret tags or hidden forms to trick a user into providing information or sending money. 
The purpose of the token is to add a third argument to the requests that cannot be reverse-engineered or decoded. The server-side application has to validate the request. 

- What is the purpose of `form.hidden_tag()`?
A hidden field that includes a token that is used to protect the form against CSRF attacks.
