# Finding 02 — Cross-Site Scripting (XSS)

## Severity
Medium

## Description
Cross-Site Scripting (XSS) occurs when untrusted input is rendered by a web application without adequate output encoding.

## Impact
An attacker may be able to execute unintended JavaScript in another user's browser.

## Remediation
Validate input and apply context-appropriate output encoding. Use secure templating practices and Content Security Policy where appropriate.

## Testing Scope
This finding is documented for authorized web-security training environments only.
