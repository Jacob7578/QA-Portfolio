# Prime Video - Login Test Scenarios




## Document Information

Application:
Amazon Prime Video

Platform:
Web / Google Chrome 

Prepared by:
Jakub Minecki

Version:
1.0

Date:
29 June 2026

-------

## Objective

Verify that users can successfully log in to Prime Video and that authentication behaves correctly under common and boundary scenarios.

-------

## Scope

Included:
- Login page
- Email authentication
- Password authentication
- Remember me
- Forgot password
- Logout

Excluded:
- SQL Injection
- XSS
- Penetration testing
- API testing
- Performance testing

Reason:
Security testing is intentionally excluded because this portfolio focuses on manual functional testing performed without attempting unauthorised actions against production systems.

-------

Prerequisites:
- internet connection
- Google Chrome installed
- Prime Video account
- Access to the login page





## Test Scenarios

TS-001

Verify that the user can log in using valid credentials.
Priority: medium

TS-002

Verify that the user cannot log in using an incorrect password.
Priiority: high

TS-003

Verify that the user cannot log in with an invalid email address.
Priority: medium

TS-004

Verify that the user cannot log in with an empty email field.
Priority: low

TS-005

Verify that the user cannot log in with an empty password field.
Priority: high

TS-006

Verify that the user cannot log in with both fields empty.
Priority: medium

TS-007

Verify Forgot Password functionality.
Priority: high

TS-008

Verify the "Remember Me" option.
Priority: medium

TS-009

Verify user logout.
Priority: medium

TS-010

Verify session persistence after browser refresh.
Priority: medium

-------

Risks - (what can go wrong while performing the tests):
- test performed on a live service
- account lockout after multiple failed logins
- accidentally buying a movie


