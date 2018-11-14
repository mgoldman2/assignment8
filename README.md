# assignment8
# Project 8 - Pentesting Live Targets

Time spent: 10 hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: __SQL INJECTION________________ SQL injection,adding the script to URL, once injecting that, the Database's query failed.

Vulnerability #2: __________SESSION HIJACKING________ This exploit was found by changing the session ID in the URL. I had to change the log in and attack the URL . Once the exploit was found, i was able to modify the sessionID to whatever i wanted, in this case I put my name into the script.


## Green

Vulnerability #1: ________CSS ATTACK__________ CSS attack, the feedbak tab had an exploit . Once submitting the sript in the feedback tab,the attack started and exposed the exploit. 

Vulnerability #2: ________USERNAME ENUMERATION__________ Username Enumeration- This vulnerability exists as a hint to identifying a valid user . If a valid user attempts a wrong password, it login text is bolded, if there is no existing user, the login text is not bolded at all . Hinting at whether or not you have an existing user, the exploit is the obvious hint the site leaves you.


## Red

Vulnerability #1: __Insecure Direct Object Reference (IDOR)________________ Insecure Direct Object Reference (IDOR). The exploit was finding the salespeople's ID's. If changed the session ID by one number (1 to 11) we are able to reach new information, which wasn't protected . By changing to 11 in the new ID i was able to see a former salesperson that was fired for stealing, all just by changing the ID number, that is the exploit.

Vulnerability #2: ______CSRF ATTACK____________ CSRF attack, to find the exploit under the red page, I had to find the users page, once i opened up inspect on any random user, i was able to modify the contents of the page, by doing so I changed the name, ID, etc. The exploit was that the website doesn't protect against CSRF attacks which allowed me to exploit that section.


## Notes

Describe any challenges encountered while doing the work
