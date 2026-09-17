# SQL Injection — Login Bypass

## Lab
SQL injection vulnerability allowing login bypass

## Platform
PortSwigger Web Security Academy

## Status
Solved ✅

## Objective
Identify and exploit a SQL injection vulnerability in the login
function to bypass authentication.

## What I Learned
- How SQL injection can affect authentication
- How user input can alter a backend SQL query
- How authentication can be bypassed when input is not handled securely
- How Burp Suite can be used to inspect and modify HTTP requests

## Remediation
- Use parameterized queries / prepared statements
- Never concatenate untrusted user input into SQL queries
- Validate input as defense in depth
- Apply least-privilege permissions to database accounts

<img width="1480" height="205" alt="image" src="https://github.com/user-attachments/assets/e8c047a6-fc0a-4d98-b35e-774711f5e4e2" />




