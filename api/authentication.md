# Authentication API

## Login

### Endpoint
POST /auth/login

### Request Body
```json
{
  "email": "user@example.com",
  "password": "123456"
}
{
  "token": "abc123xyz"
}


# User API

## Get User Details

### Endpoint
GET /users/{id}

### Headers
Authorization: Bearer <token>

### Response
```json
{
  "id": 1,
  "name": "Ritika",
  "email": "ritika@example.com"
}

