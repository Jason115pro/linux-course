x)
1.OWASP A01:2021 – Broken Access Control
Key Point: This vulnerability occurs when the system fails to properly enforce restrictions on what authenticated users are allowed to do.
Explan: Attackers bypass authorization to access unauthorized functionality or data, such as accessing other users' accounts, viewing sensitive files, or gaining admin privileges.
It’s fascinating how we often focus so much on the authentication but forget to lock the authorization

2.OWASP A05:2021 – Security Misconfiguration
Key Point: Security risks arising from insecure default settings, incomplete configurations, or poorly managed cloud storage.
Explan: This happens when developers leave default passwords unchanged, keep unnecessary features enabled, or allow verbose error messages that leak system technical details.
This is often the result of speed over security. Leaving default settings active is like keeping the factory-set code on a new digital smart lock.

3. OWASP A06:2021 – Vulnerable and Outdated Components
Key Point: The risk of using third-party libraries, frameworks, or software modules that have known security flaws.
Explan: If your application relies on a component that has a public vulnerability, attackers can use ready-made exploits to compromise your entire system.
With the massive number of dependencies in modern apps, how can developers realistically stay on top of every single update without breaking their code?

4. OWASP A03:2021 – Injection
Key Point: Injection happens when untrusted data is sent to an interpreter as part of a command or query.
Explan: The interpreter is tricked into executing unintended commands, such as allowing a user to bypass a login screen or delete a database via input fields.
Injection is a classic identity crisis in computing—the system can't distinguish between a piece of data and a command.

5. XKCD #327: Exploits of a Mom
Key Point: A famous webcomic illustrating the real-world danger of SQL Injection.
Explan: It shows a mother naming her son Robert'); DROP TABLE Students;-- to sanitize her school's database, mocking systems that don't filter user input.
If a simple name can destroy a database, who is really at fault: the person who entered the data, or the developer who wrote the code?
References: https://owasp.org/Top10/A01_2021-Broken_Access_Control/
            https://owasp.org/Top10/A05_2021-Security_Misconfiguration/
            https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/
            https://owasp.org/Top10/A03_2021-Injection/
            https://xkcd.com/327/

a)install Goat
<img width="1492" height="554" alt="h4 quistion A-1" src="https://github.com/user-attachments/assets/0a8df229-5463-4bbb-b9a3-e80d3725db5b" />
<img width="1422" height="574" alt="h4 quistion A-2" src="https://github.com/user-attachments/assets/22a09ef7-9830-4450-bba5-ce798fe000aa" />
<img width="777" height="542" alt="h4 quistion A-3" src="https://github.com/user-attachments/assets/8b854c6b-bc6b-4b2f-a4d8-20eaa2df64f9" />
<img width="1488" height="906" alt="h4 quistion A-4" src="https://github.com/user-attachments/assets/ae48a708-2767-4b87-85ea-af2013b26d87" />
<img width="1486" height="869" alt="h4 quistion A-5" src="https://github.com/user-attachments/assets/913663af-a2df-4717-8519-2b703dbef9e1" />
<img width="1494" height="834" alt="h4 quistion A-6" src="https://github.com/user-attachments/assets/4dba0330-05b7-4a47-a022-c3bee6e5d0c6" />

b)F12
Don't know where the quistion is

c)Update all operating system and all applications in Linux
<img width="801" height="369" alt="h4 quistion C-1" src="https://github.com/user-attachments/assets/27449a53-b863-4ba6-9d22-9d20102633cf" />
<img width="626" height="72" alt="h4 quistion C-2" src="https://github.com/user-attachments/assets/4589ed0b-43d1-472f-a2be-231dc49def6f" />
<img width="946" height="244" alt="h4 quistion C-3" src="https://github.com/user-attachments/assets/f91cfb4b-7901-4929-9f0b-16ed4e146916" />
<img width="956" height="278" alt="h4 quistion C-4" src="https://github.com/user-attachments/assets/56a2d6d1-d240-4aca-8ba6-0b2928a0eefb" />

d)Sequel -Solve SQLZoo
0:
<img width="1951" height="903" alt="h4 Q d 0-1" src="https://github.com/user-attachments/assets/b8a74693-98e1-4ef5-898b-5287c59c8654" />
<img width="1947" height="1072" alt="h4 Q d 0-2" src="https://github.com/user-attachments/assets/8e9829f6-330a-4ab9-bc8c-8a4a71e560a4" />
<img width="1972" height="995" alt="h4 Q d 0-3" src="https://github.com/user-attachments/assets/0e59f5c4-4792-4425-96d8-b18fb767d3d1" />
1:
<img width="1457" height="838" alt="h4 Q d 1-1" src="https://github.com/user-attachments/assets/2e0aad89-82ef-4ef4-9e36-e0b24552c99b" />
<img width="1393" height="855" alt="h4 Q d 1-2" src="https://github.com/user-attachments/assets/673671fc-2043-4b44-8113-a43e0c4117a9" />
<img width="1422" height="747" alt="h4 Q d 1-3" src="https://github.com/user-attachments/assets/8e311cfe-eeaa-4ad0-8098-00f105378a81" />
<img width="1398" height="708" alt="h4 Q d 1-4" src="https://github.com/user-attachments/assets/217f62a7-ee5d-4bda-967a-c9feda1e3aa7" />
<img width="1414" height="746" alt="h4 Q d 1-5" src="https://github.com/user-attachments/assets/390c8c24-c60c-44eb-b60e-7e68027867fd" />
<img width="1415" height="736" alt="h4 Q d 1-6" src="https://github.com/user-attachments/assets/99cf6d90-8361-4059-bcd8-65bda2fa3a9a" />
<img width="1539" height="713" alt="h4 Q d 1-7" src="https://github.com/user-attachments/assets/66ce83b0-fee5-44ab-ab08-d9468845a8bd" />
<img width="1417" height="925" alt="h4 Q d 1-8" src="https://github.com/user-attachments/assets/4c9b6870-b263-457a-b495-24c15c1c5751" />
<img width="1476" height="784" alt="h4 Q d 1-9" src="https://github.com/user-attachments/assets/5abb6d6e-ffda-4a89-9f27-83439f7a22f7" />
<img width="1401" height="736" alt="h4 Q d 1-10" src="https://github.com/user-attachments/assets/3a7205b9-1178-4b18-96ab-8ed94e479802" />
<img width="1935" height="1064" alt="h4 Q d 1-11" src="https://github.com/user-attachments/assets/ec0e1cf4-7363-4554-a3a5-299e1685bcdc" />
<img width="1659" height="863" alt="h4 Q d 1-12" src="https://github.com/user-attachments/assets/5d190f29-1ece-4c0d-b908-43e06f168ebc" />
<img width="1544" height="803" alt="h4 Q d 1-13" src="https://github.com/user-attachments/assets/9ffab3a0-3500-45d2-81be-26258d2d10ce" />
<img width="1440" height="783" alt="h4 Q d 1-14" src="https://github.com/user-attachments/assets/30696b46-2842-4b03-a841-bfe9a6658b2d" />
<img width="1459" height="849" alt="h4 Q d 1-15" src="https://github.com/user-attachments/assets/c6e0b316-cac1-4ecc-b39c-a9095d1bd144" />
2:
<img width="1846" height="771" alt="h4 Q d 2-1" src="https://github.com/user-attachments/assets/816c5ba8-e1c2-4627-a653-eefb5f99c2ad" />
<img width="1405" height="722" alt="h4 Q d 2-2" src="https://github.com/user-attachments/assets/519de2f8-05f9-45fc-8009-abf1851fe421" />
<img width="1584" height="860" alt="h4 Q d 2-3" src="https://github.com/user-attachments/assets/4fe4f5f1-d3e1-4e66-9e84-db8f753cdb1c" />
<img width="1818" height="756" alt="h4 Q d 2-4" src="https://github.com/user-attachments/assets/cbf9b001-8d6d-4a44-88a1-d1c52b5dcecd" />
<img width="1612" height="668" alt="h4 Q d 2-5" src="https://github.com/user-attachments/assets/682688a4-99fc-452c-aa90-db5c277e6139" />
<img width="1417" height="714" alt="h4 Q d 2-6" src="https://github.com/user-attachments/assets/698513e3-7418-4bb3-bdb2-36a8f3f57d07" />
<img width="1644" height="859" alt="h4 Q d 2-7" src="https://github.com/user-attachments/assets/7046e635-a116-472d-a551-02628c0ff1b7" />
<img width="1644" height="876" alt="h4 Q d 2-8" src="https://github.com/user-attachments/assets/a567dd27-0443-4325-b9c5-a1dbfbb947d0" />
<img width="1863" height="805" alt="h4 Q d 2-9" src="https://github.com/user-attachments/assets/b66eb5e5-c1e5-48e2-9347-7151d843cb51" />
<img width="1816" height="861" alt="h4 Q d 2-10" src="https://github.com/user-attachments/assets/dd9e1217-1107-4750-8ed8-607b3a8cfd40" />
<img width="1720" height="852" alt="h4 Q d 2-11" src="https://github.com/user-attachments/assets/c5d39bf9-5f42-496a-b2c7-56ac94a5aaba" />
<img width="1793" height="770" alt="h4 Q d 2-12" src="https://github.com/user-attachments/assets/bf5ed575-e8ca-40a3-836a-21d9e81f62e8" />
<img width="1421" height="945" alt="h4 Q d 2-13" src="https://github.com/user-attachments/assets/e068f3fb-9fe3-4a07-8150-61ea60906523" />

e)Solve Portswigger Labs: Lab: SQL injection vulnerability in WHERE clause allowing retrieval of hidden data
1:how and why
This vulnerability occurs because the application concatenates user input directly into a SQL query without proper sanitization. This allows an attacker to "rewrite" the logic of the database command
Expected : Only show products from the "Gifts" category that are "released" 
2:How to find the vulnerabitiy
Identify the input point
First, browse the website and interact with the category filter. When you click a specific product category ("Gifts"), observe the URL: https://xxx.web-security-academy.net/filter?category=Gifts This indicates that category is a parameter sent to the backend.
Test for syntax interference
Append a single quote (') to the value of the category parameter:
Action: Change category=Gifts to category=Gifts'.
Observation: If the server returns an error message or the page content disappears unexpectedly, it usually means your quote broke the SQL query's string structure. This is a primary indicator of a SQL injection vulnerability.
Verify using Boolean logic
To confirm it is a SQL injection and not just a generic input error, try injecting logical statements:
True Statement: Input Gifts' AND 1=1--. If the page loads normally and shows the Gifts category, you have successfully closed the query and executed it.
False Statement: Input Gifts' AND 1=2--. If the page shows "no products found," it confirms that your injected SQL code is directly influencing the database query results.
Bypass application logic
Finally, try using OR 1=1 to test if you can extract hidden data.
Action: Modify the parameter to ' OR 1=1--.
Result: If the page displays more products than usual, you have confirmed that the vulnerability can be exploited to retrieve sensitive or hidden information.
References: https://portswigger.net/web-security/sql-injection/lab-retrieve-hidden-data
