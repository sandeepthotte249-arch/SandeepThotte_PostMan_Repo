# SandeepThotte_PostMan_Repo
PostMan_Basics

# Simple Books API Testing using Postman

This project demonstrates API testing using Postman on the Simple Books API. It covers CRUD operations, environment setup, and API chaining.

## Objectives
- Learn REST API testing concepts
- Practice authorization and chaining
- Validate status codes and responses
- Use Postman environment variables

## Tools & Technologies
- Postman
- Newman CLI
- JSON, JavaScript
- Bearer Token Authentication

## API Endpoints
1. GET /books
2. POST /orders
3. GET /orders/:id
4. DELETE /orders/:id

## Authorization
Bearer Token: `{{token}}`

## Environment Variables
- `baseUrl`
- `token`
- `orderId`

## Test Script Example
```javascript
pm.test("Response status is 201", function() {
    pm.response.to.have.status(201);
});
