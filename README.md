1. Artemis Financial was a financial services company that needed help improving the security of its software application. The company wanted secure communication, stronger data integrity, and protection for sensitive financial information. The main issue I addressed was adding secure communication through HTTPS and using SHA-256 checksum verification to make sure data had not been changed or tampered with.

2. One thing I did well was identifying areas where the application needed stronger security and then applying multiple security improvements. I added checksum verification, generated a certificate, configured HTTPS, and used OWASP Dependency-Check to scan for known dependency vulnerabilities. Secure coding is important because it protects customer information, reduces the chance of attacks, and helps maintain trust. Software security adds value to a company by protecting its reputation, reducing risk, and supporting compliance with security expectations.

3. The most challenging part of the vulnerability assessment was working through the certificate and dependency-check process because small configuration issues could cause errors. However, it was also helpful because it showed me how security tools are used in real software development.

4. I increased layers of security by using SHA-256 for data integrity, generating a certificate with Java Keytool, enabling HTTPS communication, and scanning dependencies with OWASP Dependency-Check. In the future, I would use tools such as OWASP Dependency-Check, code reviews, secure coding standards, and vulnerability databases to decide which risks need mitigation.

5. To make sure the application was functional and secure, I tested the refactored application after making changes. I confirmed that the checksum page worked, HTTPS loaded through localhost, and the application ran without errors. After refactoring, I ran dependency-check again to see whether new vulnerabilities were introduced.

6. The resources and practices I used that will help me in the future include Java Keytool, SHA-256 hashing, SSL/TLS configuration, Spring Boot security settings, OWASP Dependency-Check, and secure coding practices such as testing after every major change.

7. For future employers, I could show the completed secure software report, screenshots of the working HTTPS application, checksum verification, certificate generation, dependency-check report, and the refactored code. These examples show that I can identify security risks, apply secure coding practices, test software functionality, and document my work professionally.
