# Web Application Security Assessment

## Project Overview
This project focuses on assessing common web application vulnerabilities in a controlled laboratory environment.

## Lab Environment
- Operating System: Kali Linux
- Target Application: OWASP Juice Shop
- Deployment: Docker
- Target URL: http://127.0.0.1:3000

## Tools
- OWASP ZAP
- Burp Suite
- Nikto
- SQLMap
- Wapiti

## Progress

### Exercise 1: HTTP Traffic Analysis with OWASP ZAP
**Status: Completed**

- Launched OWASP Juice Shop locally using Docker.
- Configured OWASP ZAP as an HTTP proxy.
- Intercepted HTTP requests and responses.
- Examined GET requests and HTTP status codes.
- Observed potential security alerts.

### Exercise 2: Burp Suite
Not started.

### Exercise 3: Nikto
Not started.

### Exercise 4: SQLMap
In progress: SQL injection testing in the Juice Shop laboratory.

### Exercise 5: Wapiti
Not started.

## Security Recommendations
- Validate and sanitize user inputs.
- Use parameterized SQL queries.
- Configure security headers appropriately.
- Implement strong access controls.

## Disclaimer
All security tests are performed against an intentionally vulnerable application in an authorized local laboratory for educational purposes.
