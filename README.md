# 🎯 Restful Booker API Testing
API testing project using Postman.

1️⃣Step 1 — Add Postman Collection with Authentication Test
❔Purpose
The first goal of this project is to understand how authentication works in an API.
Before testing protected actions like update or delete, we need to learn how to log in and get a token.
❔What I did
- Created a Postman collection
- Added an authentication request
- Sent valid username and password to the API
- Received a token from the response
- Saved the token automatically as a collection variable
🔘Endpoint POST /auth
➡Request Body
{
  "username": "admin",
  "password": "password123"
}
↩Expected Result
{
  "token": "..."
}
❔Why this matters
Authentication is the first step before testing secured API actions.
The token proves that the user is logged in and can be used later for authorized requests.
