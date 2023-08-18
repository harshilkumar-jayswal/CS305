
#  **CS-305 Software Security**

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![ArtemisLogo](https://github.com/harshilkumar-jayswal/CS305/assets/87956398/a2ee63c4-5d55-4c4e-ae53-283b35edd5ec)


### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a company that creates personalized financial plans for its clients. They want to modernize their operations and are currently using a RESTful web application programming interface (API). They're seeking ways to defend against external threats and secure their data. They needed to implement a data verification step using checksums to ensure secure transfer of financial data and using secure protocol such as HTTPS for site verification.


### What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I thoroughly reviewed the codebase, conducted static code analysis, and utilized OWASP Maven tools for dependency scanning. This proactive approach helped identify vulnerabilities in the development process. Secure coding is vital as it prevents exploitation of vulnerabilities, protects sensitive data, maintains customer trust, and mitigates potential legal and financial risks. Software security enhances a company's overall wellbeing by safeguarding its reputation, customer information, and intellectual property.

### What part of the vulnerability assessment was challenging or helpful to you?
I had a bit of challenging time fixing all the errors and vulnerabilities found in the codebase. But I was able to fix them once identified. This process was helpful in ensuring that even subtle security weaknesses were addressed to provide comprehensive protection.

### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
To enhance security, I implemented HTTPS with certificate generation to encrypt communication between the web application and clients. Additionally, I integrated SHA-256 checksums to verify data integrity during transmission. This ensured that data remains confidential and tamper-proof. I suppressed false positives in the dependency report for more accurate vulnerability assessment. 

### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure both functionality and security, I tested the refactored code. I verified that the code executed without errors and produced the expected output, including generating valid checksums for data verification. Additionally, I confirmed that the connection between the web application and clients was encrypted and secure through the implementation of HTTPS with certificate generation.

### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used Vulnerability Assessment Process Flow Diagram and Secure Coding Guidelines for Java SE to guide me through secure coding practices. I used OWASP Maven tools for dependency scanning, static code analysis tools for identifying vulnerabilities, and followed OWASP's secure coding guidelines. 

### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
From this assignment, I can demonstrate my ability to integrate secure communication mechanisms, conduct vulnerability assessments, implement security layers, and ensure functional and secure software development. I can present the enhanced codebase, documentation of security measures, and a summary of the risk mitigation strategies employed, showcasing my skills in ensuring software security and quality.

### Credits
Programming by Harshilkumar Jayswal

Professor Alan Spencer

Module 8-1 Portfolio Journal 

CS-305 Software Security @ SNHU
