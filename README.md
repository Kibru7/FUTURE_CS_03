Project title: API Security Risk Analysis (Nationalize.io)

Project Overview
This repository contains a security risk analysis of the public API Nationalize.io (https://api.nationalize.io). Testing was performed using Postman and Browser DevTools to observe security-relevant behaviors such as CORS configuration, rate limiting, caching, and input handling.

API Selected
API Name: Nationalize.io
Base URL: https://api.nationalize.io
Example Endpoint Tested: GET /?name=nathaniel

Tools Used
Postman (request execution and response capture)
Browser DevTools (Network tab inspection of request and response headers)

Repository Structure
README.md: Project overview and reproduction steps
report/report.md: Full security risk analysis report
evidence/: Screenshots and captured outputs

How to Reproduce
Open in a browser:
https://api.nationalize.io/?name=nathaniel

Or send in Postman:
Method: GET
URL: https://api.nationalize.io/?name=nathaniel
