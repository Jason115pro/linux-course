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
References:https://owasp.org/Top10/A01_2021-Broken_Access_Control/
           https://owasp.org/Top10/A05_2021-Security_Misconfiguration/
           https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/
           https://owasp.org/Top10/A03_2021-Injection/
           https://xkcd.com/327/

a)install Goat
<img width="1492" height="554" alt="h4 quistion A-1" src="https://github.com/user-attachments/assets/0a8df229-5463-4bbb-b9a3-e80d3725db5b" />

b)
