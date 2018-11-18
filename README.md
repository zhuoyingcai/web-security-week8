# Project 8 - Pentesting Live Targets

Time spent: 6 hours spent in total

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

#### Vulnerability #1: SQL Injection (SQLi)

  - Able to search salesperson by SQL injection

GIF Walkthrough: <img src="blue-SQL Injection.gif" width="800">

#### Vulnerability #2: Session Hijacking/Fixation

  - Able to login by using old session ID

GIF Walkthrough: <img src="blue-Session Hijacking-Fixation.gif" width="800">

## Green

#### Vulnerability #1: Username Enumeration

  - "Login was unsuccessful" is bold if username is in the database

GIF Walkthrough: <img src="green-Username Enumeration.gif" width="800">

#### Vulnerability #2: Cross-Site Scripting (XSS)

  - Able to input CSS at contact us section

GIF Walkthrough: <img src="green-Cross-Site Scripting.gif" width="800">


## Red

#### Vulnerability #1: Insecure Direct Object Reference (IDOR)

  - Able to search salesperson by ID directly

GIF Walkthrough: <img src="red- Insecure Direct Object Reference.gif" width="800">

#### Vulnerability #2: Cross-Site Request Forgery (CSRF)

  - Able to edit salesperson information even if the CSRF value is invalid

GIF Walkthrough: <img src="red-Cross-Site Request Forgery (CSRF).gif" width="800">



## Notes

Describe any challenges encountered while doing the work
