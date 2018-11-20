				Green
Stored XSS
-Submitting a comment as an end user, I could actually submit a script that has the potential to steal vital information of an admin such as login information.  In this case I just displayed an alert proving that I took advantage of the vulnerability.
Enumeration
-When submitting a username that is in use, the website returned that a password must be submitted in bold, rather than unbolded found on the other sites. This indicates that the username is in use if the hacker is guessing usernames.  
				Blue
SQL Injection
-When on an employees info page, you can alter the URL by appending a ' to the URL. This causes the database query to fail.
Session Hijacking
-Using two different browsers, showcases how this can be done on two different devices.  By taking the cookies of an admin, a hacker can use them as theirs to "sign in" as an admin without the need of a username and password. 
				Red
IDOR
-When searching for a salesperson, an end user can manipulate the URL to return an employee's page that is not supposed to be public until a later date.
CSRF
-After logging in, I edited the user's CSRF by inspecting the web page and changing the csrf token.  
