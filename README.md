# BigAnt-Office-Messenger-5.6.06-RCE-via-SQL-Injection
The SQL injection vulnerability in BigAnt Messenger causes the RCE vulnerability
# Exploit
We extract the database version used in the 'dev_code' parameter exposed to SQL injection
![SQLI version](https://github.com/user-attachments/assets/109a800c-af76-4a0b-9b42-0f03d0a9acbe)
Thanks to the wrong configuration in SQL, we can upload webshell to the target using SQL stack queries.
![crate webshell 1](https://github.com/user-attachments/assets/258f0ae0-8c8e-4b09-b454-fcd4339d877c)
Proof of command injection:
![whoami](https://github.com/user-attachments/assets/94c2bf8e-6ba3-4329-aeaa-44215f88fed0)
![command dir](https://github.com/user-attachments/assets/07320b55-01c7-4e34-8d26-4b3a0d62d817)
# Timeline
31-10-2024: Submitted vulnerabilities to vendor via email
31-10-2024: Emailed vendor, no response
15-11-2024: Emailed vendor, no response
15-11-2024: Requested CVEs
# Reference
https://www.bigantsoft.com/download.html
