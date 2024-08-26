# SQL-Injection-Scanner
A Python-based SQL Injection vulnerability scanner for web applications.
This project is a Python-based SQL Injection Vulnerability Scanner. It tests web applications for common SQL injection vulnerabilities using a set of predefined payloads.

## Features

- Scans a given URL for SQL injection vulnerabilities.
- Supports various SQL injection payloads.
- Provides detailed output on potential vulnerabilities.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/itzzzzmeeee/SQL-Injection-Scanner.git

2. Navigate to the project directory:
   '''bash
   cd SQL-Injection-Scanner
   
3. Install the required Python libraries:
   '''bash
   pip install requests

4. Run the Vulnerability Scanner:

   To run the vulnerability scanner, use the following command:

   '''bash
   python vulnerability_scanner.py
   AFTER RUNNING THIS COMMAND
   
   The script will prompt you to input the target URL. For example:

   '''bash
   Enter the target URL eg : "http://demo.owasp-juice.shop/rest/user/register"
   The script will then test the URL against several SQL injection payloads and output the results.

5. View the Results:

   The scanner will display possible SQL injection vulnerabilities in the console.
   The output will show which payloads might have caused an SQL injection vulnerability, similar to the following:
     OUTPUT:
   
     [!] Possible SQL Injection vulnerability found with payload: ' OR '1'='1
     [!] Possible SQL Injection vulnerability found with payload: ' OR '1'='1' -- 
     [!] Possible SQL Injection vulnerability found with payload: ' OR '1'='1' #
     [!] Possible SQL Injection vulnerability found with payload: ' OR '1'='1' /*
     [!] Possible SQL Injection vulnerability found with payload: ' UNION SELECT NULL--
     [!] Possible SQL Injection vulnerability found with payload: ' OR EXISTS(SELECT * FROM information_schema.tables)--
     [!] Possible SQL Injection vulnerability found with payload: ' OR 1=1--
     [!] Possible SQL Injection vulnerability found with payload: ' AND 1=1--
     [!] Possible SQL Injection vulnerability found with payload: ' AND 1=2--
   

                                         ----ENJOY CODING----
