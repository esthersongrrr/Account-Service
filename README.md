# Account-Service
Account-Service for online shopping

## AccountService
## (Todo)authentication server
this server helps to secure services by providing authentication and authorization facility.
e.g. once a user logs into its account successfully, the server generates a token, with this token as part of the request header, requests sent to order service can be accepted.

**JwtTokenUtil.java**:

This class will encapsulate the logic for generating, parsing, and validating tokens, handle JWT creation and verification.

**JwtRequestFilter.java**

This filter checks for the presence of the JWT in the request headers and sets the authentication context.

