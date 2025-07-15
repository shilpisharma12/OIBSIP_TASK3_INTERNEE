# OIBSIP_Task3
# OIBSIP_internshipforcybersecurity_Task3
Performed SQL Injection on DVWA (Low Security) to demonstrate how malicious users can exploit the databases of a organization.

# Task 3: SQL Injection on DVWA (Low Security)

## Objective
To demonstrate a basic SQL Injection vulnerability using DVWA with the security level set to LOW.

## Tools Used
- Kali Linux (Apache2 & MySQL)
- DVWA (Damn Vulnerable Web App)
- Web Browser
- Bash Script

## Steps Performed
1. Started Apache2 and MySQL services.
2. Configured and launched DVWA at http://localhost(127.0.0.1)/DVWA
3. Set DVWA security level to *Low* from DVWA Security
4. Move your curshor to *SQL Injection* module.
5. Injected payload: 1' OR '1'='1
6. Successfully retrieved all user records.

## Output
Screenshot: sql_injection_task4_result.png

## Script
File: sql_injection_exploit.sh  
Description: Demonstrates the payload used.

## Learning Outcome
- Understood SQL Injection basics.
- Learned how weak input validation exposes data.
- Gained hands-on experience with DVWA.
- Use better program to secure your databases.
- Audit everytime to know what is going around your databases.

## 😊 Author
Shilpi Sharma
