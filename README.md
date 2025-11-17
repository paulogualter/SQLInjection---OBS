# SQLInjection-OBS

A critical SQL Injection vulnerability has been identified in the `book.php` file of the "Simple Online Book Store" web application. The `bookisbn` parameter is inserted directly into SQL queries without proper validation or sanitization, allowing remote attackers to execute arbitrary SQL commands against the database.
The vulnerability directly affects the application database. The complete DUMP of the database can be performed.
The application uses the `bookisbn` parameter directly in a SQL query without using prepared statements or appropriate sanitization. This allows an attacker to inject malicious SQL commands that are executed against the database.


<img width="1522" height="650" alt="image" src="https://github.com/user-attachments/assets/393c1242-04a8-44e4-a26c-b623e85a6b55" />


<img width="432" height="180" alt="image" src="https://github.com/user-attachments/assets/85c167fc-9111-4f93-8fc9-b0da12242db8" />


<img width="403" height="877" alt="image" src="https://github.com/user-attachments/assets/8019c55e-c597-4eca-a5b3-39590477490a" />


