## Description

Description of PR that completes issue here...

## Changes

- Item 1
- Item 2
- Item 3

## Requests / Responses

**Request**

POST `/api/users` Returns a list of users

```
{
  "data": {
    "attributes": {
      "name": "The Dude",
      "email": "thedudeabides@wee.net",
      "password": "hellopassword"
    }
  },
  "type": "users"
}
```

**Response**

HTTP/1.1 200 OK

```
{
  "data": {
    "type": "users",
    "id": "4",
    "attributes": {
      "name": "The Dude",
      "email": "thedudeabides@wee.net",
      "last-logged-in": null,
      "created-at": "2016-10-20T17:45:08.190Z",
      "updated-at": "2016-10-20T17:45:08.190Z"
    },
    "links": {
      "self": "/users/4"
    }
  }
}
```

## Testing

Describe how this should be tested manually

## What are the relevant issues?

Finishes #issue_number

