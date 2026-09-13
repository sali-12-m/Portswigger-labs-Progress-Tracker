# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-19-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--03-yellow) ![Level](https://img.shields.io/badge/Level-Progress-green)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below).

## Level progress
- **Apprentice**: 18 of 61
- **Practitioner**: 29 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 11/14 lab
- **SQL injection**: 9/18 lab
- **Access control**: 13/13 lab
- **Path traversal**: 6/6 lab
- **OS command injection**: 5/5 lab
- **File upload vulnerabilities**: 3/7
- **XML external entity (XXE) injection: 8/9

## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-17 | SQL injection | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data | Apprentice | N/A |
| 2  | 2026-06-17 | SQL injection | SQL injection vulnerability allowing login bypass | Apprentice | N/A |
| 3  | 2026-06-17 | SQL injection | SQL injection UNION attack, determining the number of columns returned by the query | Practitioner | N/A |
| 4  | 2026-06-18 | SQL injection | SQL injection UNION attack, finding a column containing text | Practitioner | N/A |
| 5  | 2026-06-18 | SQL injection | SQL injection UNION attack, retrieving data from other tables | Practitioner | N/A |
| 6  | 2026-06-18 | SQL injection | SQL injection UNION attack, retrieving multiple values in a single column | Practitioner | N/A |
| 7  | 2026-06-21 | SQL injection | SQL injection with filter bypass via XML encoding | Practitioner | N/A |
| 8  | 2026-06-21 | SQL injection | Blind SQL injection with time delays | Practitioner | N/A |
| 9  | 2026-06-21 | SQL injection | Visible error-based SQL injection | Practitioner | N/A |
| 10 | 2026-06-24 | Authentication vulnerabilities | Lab: Username enumeration via different responses | APPRENTICE | N/A |
| 11 | 2026-06-24 | Authentication vulnerability | lab: 2FA simple bypass | APPRENTICE | N/A |
| 12 | 2026-06-24 | Authentication vulnerability | lab: Username enumeration via subtly different responses | Practitioner | N/A |
| 13 | 2026-06-26 | Authentication vulnerability | lab: Username enumeration via response timing | Practitioner | N/A |
| 14 | 2026-06-26 | Authentication vulnerability | lab: Broken brute-force protection, IP block | Practitioner | N/A |
| 15 | 2026-06-26 | Authentication vulnerability | lab: Username enumeration via account lock | Practitioner | N/A |
| 16 | 2026-06-27 | Authentication vulnerability | lab: 2FA broken logic | Practitioner | N/A |
| 17 | 2026-06-27 | Authentication vulnerability | lab: Brute-forcing a stay-logged-in cookie | Practitioner | N/A |
| 18 | 2026-06-27 | Authentication vulnerability | lab: Offline password cracking | Practitioner | N/A |
| 19 | 2026-06-28 | Authentication vulnerability | lab: Password reset poisoning via middleware | Practitioner | N/A |
| 20 | 2026-06-28 | Authentication vulnerability | lab: Password reset broken logic | APPRENTICE | N/A |
| 21 | 2026-07-01 | Path traversal | File path traversal, simple case | Apprentice | N/A |
| 22 | 2026-07-01 | Path traversal | File path traversal, traversal sequences blocked with absolute path bypass | Practitioner | N/A |
| 23 | 2026-07-01 | Path traversal | File path traversal, traversal sequences stripped non-recursively | Practitioner | N/A |
| 24 | 2026-07-01 | Path traversal | File path traversal, traversal sequences stripped with superfluous URL-decode | Practitioner | N/A |
| 25 | 2026-07-01 | Path traversal | File path traversal, validation of start of path | Practitioner | N/A |
| 26 | 2026-07-01 | Path traversal | File path traversal, validation of file extension with null byte bypass | Practitioner | N/A |
| 27 | 2026-07-03 | OS command injection | OS command injection, simple case | Apprentice | N/A |
| 28 | 2026-07-03 | OS command injection | Blind OS command injection with time delays | Practitioner | N/A |
| 29 | 2026-07-03 | OS command injection | Blind OS command injection with output redirection | Practitioner | N/A |
| 30 | 2026-07-03 | OS command injection | Blind OS command injection with out-of-band interaction | Practitioner | N/A |
| 31 | 2026-07-03 | OS command injection | Blind OS command injection with out-of-band data exfiltration | Practitioner | N/A |
| 32 | 2026-07-20 | Access control vulnerabilities | Unprotected admin functionality | Apprentice | N/A |
| 33 | 2026-07-20 | Access control vulnerabilities | Unprotected admin functionality with unpredictable URL | Apprentice | N/A |
| 34 | 2026-07-20 | Access control vulnerabilities | User role controlled by request parameter | Apprentice | N/A |
| 35 | 2026-07-20 | Access control vulnerabilities | User role can be modified in user profile | Apprentice | N/A |
| 36 | 2026-07-20 | Access control vulnerabilities | URL-based access control can be circumvented | PRACTITIONER | N/A |
| 37 | 2026-07-22 | Access control vulnerabilities | Method-based access control can be circumvented | PRACTITIONER | N/A |
| 38 | 2026-07-22 | Access control vulnerabilities | User ID controlled by request parameter  | APPRENTICE | N/A |
| 39 | 2026-07-22 | Access control vulnerabilities | User ID controlled by request parameter, with unpredictable user IDs   | APPRENTICE | N/A |
| 40 | 2026-07-22 | Access control vulnerabilities | User ID controlled by request parameter with data leakage in redirect   | APPRENTICE | N/A |
| 41 | 2026-07-22 | Access control vulnerabilities | User ID controlled by request parameter with password disclosure | APPRENTICE | N/A |
| 42 | 2026-07-22 | Access control vulnerabilities | Insecure direct object references | APPRENTICE | N/A |
| 43 | 2026-07-26 | Access control vulnerabilities | Multi-step process with no access control on one step | PRACTITIONER | N/A |
| 44 | 2026-07-26 | Access control vulnerabilities | Referer-based access control | PRACTITIONER | N/A |
| 45 | 2026-07-26 | File upload vulnerabilities | Remote code execution via web shell upload | APPRENTICE | N/A |
| 46 | 2026-07-26 | File upload vulnerabilities | Web shell upload via Content-Type restriction bypass | APPRENTICE | N/A |
| 47 | 2026-07-26 | File upload vulnerabilities | Web shell upload via path traversal | PRACTITIONER | N/A |
| 48 | 2026-07-28 | File upload vulnerabilities | Web shell upload via extension blacklist bypass | PRACTITIONER | N/A |
| 49 | 2026-07-28 | File upload vulnerabilities | Web shell upload via obfuscated file extension | PRACTITIONER | N/A |
| 50 | 2026-07-30 | Race conditions | Limit overrun race conditions | APPRENTICE | N/A |
| 51 | 2026-07-30 | Race conditions | Bypassing rate limits via race conditions | PRACTITIONER | N/A |
| 52 | 2026-07-30 | Race conditions | Multi-endpoint race conditions | PRACTITIONER | N/A |
| 53 | 2026-07-30 | Race conditions | Single-endpoint race conditions | PRACTITIONER | N/A |
| 54 | 2026-08-15 | Server-side request forgery (SSRF) | Basic SSRF against the local server | APPRENTICE | N/A |
| 55 | 2026-08-15 | Server-side request forgery (SSRF) | Basic SSRF against another back-end system | APPRENTICE | N/A |
| 56 | 2026-08-15 | XML external entity (XXE) injection | Exploiting XXE using external entities to retrieve files | APPRENTICE | N/A |
| 57 | 2026-08-15 | XML external entity (XXE) injection | Exploiting XXE to perform SSRF attacks | APPRENTICE | N/A |
| 58 | 2026-08-15 | XML external entity (XXE) injection | Blind XXE with out-of-band interaction | PRACTITIONER | N/A |
| 59 | 2026-08-16 | XML external entity (XXE) injection | Blind XXE with out-of-band interaction via XML parameter entities | PRACTITIONER | N/A |
| 60 | 2026-08-16 | XML external entity (XXE) injection | Exploiting blind XXE to exfiltrate data using a malicious external DTD | PRACTITIONER | N/A |
| 61 | 2026-08-16 | XML external entity (XXE) injection | Exploiting blind XXE to retrieve data via error messages | PRACTITIONER | N/A |
| 62 | 2026-08-16 | XML external entity (XXE) injection | Exploiting XInclude to retrieve files | PRACTITIONER | N/A |
| 63 | 2026-08-16 | XML external entity (XXE) injection | Exploiting XXE via image file upload | PRACTITIONER | N/A |
| 64 | 2026-08-16 | XML external entity (XXE) injection | Exploiting XXE via image file upload | PRACTITIONER | N/A |
| 65 | 2026-08-26 | Cross-site request forgery (CSRF) | CSRF vulnerability with no defenses | APPRENTICE | N/A |
| 66 | 2026-08-26 | Cross-site request forgery (CSRF) | CSRF where token validation depends on request method | PRACTITIONER | N/A |
| 67 | 2026-08-26 | Cross-site request forgery (CSRF) | CSRF where token validation depends on token being present | PRACTITIONER | N/A |
| 68 | 2026-08-29 | Cross-site request forgery (CSRF) | CSRF where Referer validation depends on header being present | PRACTITIONER | N/A |
| 69 | 2026-08-29 | Cross-site scripting | Reflected XSS into HTML context with nothing encoded | APPRENTICE | N/A |
| 70 | 2026-08-29 | Cross-site scripting | Stored XSS into HTML context with nothing encoded | APPRENTICE | N/A |
| 71 | 2026-08-29 | Cross-site scripting | DOM XSS in document.write sink using source location.search | APPRENTICE | N/A |
| 72 | 2026-08-29 | Cross-site scripting | DOM XSS in innerHTML sink using source location.search | APPRENTICE | N/A |
| 73 | 2026-08-30 | Cross-site scripting | Reflected XSS into attribute with angle brackets HTML-encoded | APPRENTICE | N/A |
| 74 | 2026-08-30 | Cross-site scripting | Exploiting cross-site scripting to steal cookies | PRACTITIONER | N/A |
| 75 | 2026-08-30 | Cross-site scripting | Exploiting cross-site scripting to capture passwords | PRACTITIONER | N/A |
| 76 | 2026-08-30 | Cross-site scripting | Exploiting XSS to bypass CSRF defenses| PRACTITIONER | N/A |
| 77 | 2026-09-03 | Server-side template injection | Basic server-side template injection | PRACTITIONER | N/A |
| 78 | 2026-09-03 | Server-side template injection | Basic server-side template injection (code context) | PRACTITIONER | N/A |
| 79 | 2026-09-03 | Server-side template injection | Server-side template injection using documentation | PRACTITIONER | N/A |
| 80 | 2026-09-05 | Server-side template injection | Server-side template injection in an unknown language with a documented exploit | PRACTITIONER | N/A |
| 81 | 2026-09-05 | Server-side template injection | Server-side template injection with information disclosure via user-supplied objects| PRACTITIONER | N/A |
| 82 | 2026-09-10 | HTTP request smuggling | HTTP request smuggling, confirming a CL.TE vulnerability via differential responses | PRACTITIONER | N/A |
| 83 | 2026-09-10 | HTTP request smuggling | HTTP request smuggling, confirming a TE.CL vulnerability via differential responses | PRACTITIONER | N/A |
| 84 | 2026-09-10 | HTTP request smuggling | Exploiting HTTP request smuggling to bypass front-end security controls, CL.TE vulnerability | PRACTITIONER | N/A |
| 85 | 2026-09-11 | HTTP request smuggling | Exploiting HTTP request smuggling to bypass front-end security controls, TE.CL vulnerability | PRACTITIONER | N/A |
| 86 | 2026-09-11 | HTTP request smuggling | Exploiting HTTP request smuggling to reveal front-end request rewriting | PRACTITIONER | N/A |
| 87 | 2026-09-11 | HTTP request smuggling | Exploiting HTTP request smuggling to capture other users' requests | PRACTITIONER | N/A |
| 88 | 2026-09-12 | HTTP request smuggling | Exploiting HTTP request smuggling to deliver reflected XSS | PRACTITIONER | N/A |
| 89 | 2026-09-12 | HTTP request smuggling | HTTP request smuggling, basic CL.TE vulnerability | PRACTITIONER | N/A |
| 90 | 2026-09-12 | HTTP request smuggling | HTTP request smuggling, basic TE.CL vulnerability | PRACTITIONER | N/A |
| 91 | 2026-09-12 | HTTP request smuggling | HTTP request smuggling, obfuscating the TE header | PRACTITIONER | N/A |
| 92 | 2026-09-13 | HTTP request smuggling | Response queue poisoning via H2.TE request smuggling | PRACTITIONER | N/A |
| 93 | 2026-09-13 | HTTP request smuggling | H2.CL request smuggling | PRACTITIONER | N/A |
| 94 | 2026-09-13 | HTTP request smuggling | HTTP/2 request smuggling via CRLF injection | PRACTITIONER | N/A |
| 95 | 2026-09-13 | HTTP request smuggling | HTTP/2 request splitting via CRLF injection | PRACTITIONER | N/A |
















