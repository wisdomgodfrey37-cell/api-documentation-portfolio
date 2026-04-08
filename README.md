# user-api.yaml
openapi: 3.0.0
info:
  title: User Management API
  version: 1.0.0

paths:
  /users:
    post:
      summary: Create user
      responses:
        '201':
          description: User created

  /users/{id}:
    get:
      summary: Get user
      responses:
        '200':
          description: Success

    put:
      summary: Update user
      responses:
        '200':
          description: Updated

    delete:
      summary: Delete user
      responses:
        '200':
          description: Deleted
