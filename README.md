Task 1 – Web Application Security Testing
 Internship: Future Interns
 Role: Cybersecurity Intern
 Status: ✔ Completed

 Objective :-
The goal of this task was to analyse and exploit web vulnerabilities using DVWA (Damn Vulnerable Web Application).
The focus was on two major vulnerabilities:

SQL Injection :-
Stored Cross-Site Scripting (XSS)

 Environment Used :-
Component	Details
Server	XAMPP
Tool	DVWA
Browser	Google Chrome
OS	Windows
DVWA Security Level	LOW
 Vulnerabilities Tested
 SQL Injection

Payload used :-
1

Result :-
The query returned user information without validation.

 Impact :-
Attackers can bypass authentication and extract data.

 Fix Recommendation :-
Use prepared statements
Validate & sanitize input
 Stored XSS (Cross-Site Scripting)

Payload used :-
<script>alert('Hacked!');</script>

Result :-
Stored JavaScript executed every time the data was loaded.

 Impact :-
Cookie/session stealing
Browser exploitation
UI tampering

 Fix Recommendation :-
Escape output
Validate user input
Apply Content Security Policy (CSP)

 Files Included :-
File	Description
Task1_Report.pdf	Final PDF Report
DVWA_Task1_Screenshots & evidence

 Conclusion :-
This task helped me gain hands-on understanding of how insecure coding and poor validation lead to real security vulnerabilities.

 Author :-
Sai Prasath
Cyber Security Intern @ Future Interns
 Learning |  Ethical Hacking |  Web Security
