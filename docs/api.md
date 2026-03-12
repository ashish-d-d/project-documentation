# API Documentation

## Get User Details

Endpoint:
GET /api/users/{id}

Description:
Returns the details of a specific user.

Example Request:
GET /api/users/101

Example Response:
{
    "id":101,
    "name":"John Jackson",
    "email":"john@example.com"
}

POST api/users

Example Payload:
{
    "id":1,
    "name":"John Jackson",
    "email":"john@example.com"
}

Example Response:
{
    "status" : "created",
    "status_code" : 201,
    "message" : "User created successfully..."
}
