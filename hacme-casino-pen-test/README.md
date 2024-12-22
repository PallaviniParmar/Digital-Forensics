# Penetration Testing on Gaming Portal

## Overview
This repository contains the results of a penetration testing assessment conducted on the **Hacme Casino** gaming portal. The test aimed to identify and analyze critical security vulnerabilities in the platform, focusing on potential threats that could compromise the integrity, security, and fairness of the gaming environment. The report outlines several key vulnerabilities, including SQL Injection, Cross-Site Request Forgery (CSRF), improper session handling, and more.

## Key Vulnerabilities Identified
The penetration test revealed the following key security vulnerabilities:

1. **Blind SQL Injection**  
   Vulnerabilities that allow unauthorized access to sensitive data.

2. **Cross-Site Request Forgery (CSRF)**  
   Attackers can perform actions on behalf of authenticated users without their consent.

3. **Improper Session Handling**  
   Allows users to exploit session data for unfair advantages.

4. **Application Logic Vulnerability**  
   Enables users to replay successful outcomes, manipulating game results.

5. **Detailed Error Messages**  
   Exposes sensitive backend information that could be leveraged for attacks.

Each vulnerability is detailed in the report, including its impact, exploit steps, and recommended mitigations.

## Tools Used
- **Burp Suite**: Used for web vulnerability scanning and exploitation.
- **OWASP ZAP**: Used for automated penetration testing.
- **Paros Proxy**: Used for capturing and replaying requests.

## Conclusion
This project highlights the importance of securing gaming portals and web applications. The findings demonstrate the need for robust security practices, including input validation, session management, and error handling. The recommendations provided in the report aim to enhance the security of online gaming platforms and protect users from potential threats.
