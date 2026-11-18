
# Cross-Site Scripting (XSS)

## 1. Introduction
Cross-Site Scripting (XSS) is a web application vulnerability in which an attacker can cause malicious client-side scripts to execute in another user's browser.

## 2. Types of XSS

### Reflected XSS
Occurs when untrusted input is immediately included in a web page response without proper encoding.

### Stored XSS
Occurs when malicious input is saved by an application and later displayed to other users without proper handling.

### DOM-Based XSS
Occurs when client-side JavaScript processes untrusted data in an unsafe way, causing script execution in the browser.

## 3. Possible Impact
- Theft of sensitive session information.
- Unauthorized actions performed through a victim's browser.
- Modification of displayed web page content.
- Phishing and malicious redirection.

## 4. Prevention Techniques
- Apply context-aware output encoding.
- Validate input on the server side.
- Avoid unsafe JavaScript functions and DOM operations.
- Use Content Security Policy (CSP).
- Set secure cookie attributes such as HttpOnly and Secure where appropriate.

## 5. Security Testing
XSS testing should be performed only in an authorized environment. Test results must be supported by actual observations and evidence.

## 6. Conclusion
Understanding XSS helps developers recognize the risks of unsafe input and output handling and build safer web applications.
