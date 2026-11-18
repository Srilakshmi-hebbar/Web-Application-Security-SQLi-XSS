
# Testing Methodology

## 1. Testing Environment
The assessment is intended to be performed using a deliberately vulnerable web application in a controlled local lab.

**Environment:**
- Operating System: Kali Linux
- Web Application: bWAPP
- Deployment: Docker
- Browser: Web browser

## 2. SQL Injection Testing
The SQL Injection testing process involves:
1. Accessing the relevant application functionality.
2. Identifying fields that accept user input.
3. Observing normal application responses.
4. Comparing responses when test inputs are submitted.
5. Recording any database-related errors or unexpected behavior.

## 3. Cross-Site Scripting Testing
The XSS testing process involves:
1. Identifying input fields and parameters.
2. Observing how the application handles submitted input.
3. Checking whether input is safely encoded before being displayed.
4. Recording any verified script execution in the authorized lab.
5. Documenting the results.

## 4. Evidence Collection
Evidence may include:
- Screenshots of the application.
- Relevant request and response observations.
- Error messages.
- Testing notes.
- Final assessment report.

## 5. Responsible Testing
All testing must remain within the authorized local lab. A vulnerability should only be marked as confirmed when the available evidence demonstrates it.

## 6. Conclusion
A systematic testing methodology helps identify application weaknesses, document observations accurately, and recommend appropriate security improvements.
