# Web Application Security Remediation

## Overview

This repository contains the security remediation of a simple web application following the OWASP Top Ten guidelines. The remediations address the following vulnerabilities:

1. Sensitive Data Exposure
2. Cross-Site Scripting (XSS)
3. Broken Authentication

## Remediation Details

### Sensitive Data Exposure

- **Issue**: Storing sensitive information (username and password) in `localStorage`.
- **Fix**: Removed storage of sensitive data in `localStorage`.

### Cross-Site Scripting (XSS)

- **Issue**: Injecting user input directly into the DOM without sanitization.
- **Fix**: Implemented input sanitization before injecting into the DOM.
