
# SQL Injection (SQLi)

## 1. Introduction
SQL Injection is a web application vulnerability that occurs when user input is included in database queries without proper handling.

## 2. How SQL Injection Works
When an application builds SQL queries by directly combining user input with SQL statements, specially crafted input may change the intended query.

## 3. Types of SQL Injection
- Error-Based SQL Injection: Uses database error messages to understand query behavior.
- UNION-Based SQL Injection: Attempts to combine results from multiple SELECT queries.
- Boolean-Based Blind SQL Injection: Uses differences in application responses to infer database behavior.
- Time-Based Blind SQL Injection: Uses response delays to infer database behavior.

## 4. Possible Impact
- Unauthorized database access.
- Exposure of sensitive information.
- Authentication bypass.
- Modification or deletion of database records.

## 5. Prevention
- Use prepared statements and parameterized queries.
- Validate input on the server side.
- Apply least-privilege database permissions.
- Handle database errors securely.
- Perform regular security assessments.

## 6. Conclusion
SQL Injection demonstrates why secure database query handling is essential for protecting web applications and their users.
