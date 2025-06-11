# CI-CD-process
1. What is Unit Testing?
Unit Testing is a software testing method where individual components (or units) of a program—like functions, methods, or classes—are tested in isolation to ensure they work as expected.
It is usually done by developers during the development phase.
It helps catch bugs early, before integrating with other components.
Tools used: JUnit (Java), PyTest/unittest (Python), NUnit (.NET), etc

2. What is Static Code Analysis?
Static Code Analysis is the process of examining source code without executing it to find potential errors, code smells, security vulnerabilities, or violations of coding standards.
It’s often used as part of a CI/CD pipeline or during code reviews to maintain code quality.

3.What is Code Quality?
Code Quality refers to how well-written, efficient, and maintainable your code is. High-quality code is:

Property	Meaning
Readable	Easy to understand by other developers
Maintainable	Easy to update or fix bugs later
Reliable	Works correctly under expected conditions
Testable	Easy to write and run unit tests against
Efficient	Uses system resources (CPU, memory) effectively
Consistent	Follows consistent naming, indentation, and formatting

4.What is Code Vulnerability?
Vulnerability is a weakness or flaw in the code that can be exploited by attackers to gain unauthorized access, crash the application, or steal data.
🧠 Common Types of Vulnerabilities:
Vulnerability	Description
SQL Injection	Injecting malicious SQL queries
XSS (Cross-Site Scripting)	Injecting JavaScript into web pages
Buffer Overflow	Writing beyond memory limits
Hardcoded Credentials	Passwords or API keys inside code
Unvalidated Input	Taking user input without checks
