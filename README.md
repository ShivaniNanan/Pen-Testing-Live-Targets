# Pen Testing Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each color is vulnerable to only 2 of the 6 possible exploits. First discover which color has the specific vulnerability, then write a short description of how to exploit it, and finally demonstrate it using screenshots compiled into a GIF.

## Blue

Vulnerability #1: Session Hijacking/Fixation

Description: The Session ID is vulnerable as it does not check for duplicates or change the id session to make the login more secure.

<img src="https://github.com/ShivaniNanan/Pen-Testing-Live-Targets/blob/main/bluehijacking.gif">



## Green

Vulnerability #1: Cross-Site Scripting (XSS)

Description: The user can execute an XSS attack by injecting JavaScript into the the feedback form. I injected and was succesful in my attempt.

<img src="https://github.com/ShivaniNanan/Pen-Testing-Live-Targets/blob/main/greenxss.gif">


## Red

Vulnerability #1: Insecure Direct Object Reference (IDOR)

Description: Under the staff information tab, a user can change the staff id in the url to view information that is not even public.

<img src="https://github.com/ShivaniNanan/Pen-Testing-Live-Targets/blob/main/redidor.gif">



