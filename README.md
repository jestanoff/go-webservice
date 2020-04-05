# Webservice
Simple RESTFul webservice built in go

## Run the service
```go run .```

## Build
```go build .```

## Access the service
```curl http://localhost:3000/users```

## Available methods
`GET /users` - to get all users

`POST /users` with "FirstName" and "LastName" - to crate a user

`PUT /users/{id}` with "FirstName" and "LastName" - to update a user

`DELETE /users/{id}` - to remove a user
