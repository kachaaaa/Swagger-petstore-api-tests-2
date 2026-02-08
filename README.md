# Swagger Petstore API Testing (Postman)

This project demonstrates negative API testing of the Swagger Petstore User API using Postman.

## Tools
- Postman
- Swagger Petstore API

## Tested Endpoint
- GET /user/login

## Negative Test Scenarios
- Wrong password
- Empty password
- Non-existing user

## Result
API returns 200 OK for invalid login attempts, which indicates validation issues.
