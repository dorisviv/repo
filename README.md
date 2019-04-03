# my-json-server

1. Create a JSON object in GitHub, with the exact path (dorisviv = your user):

https://github.com/dorisviv/repo/blob/master/db.json

`
{
  "persons": [
    {
      "id": 1,
      "euid": "admin",
      "emplid": "12345678",
      "firstName": "AdminFirst",
      "lastName": "AdminLast",
      "roles": [
        "ROLE_ADMIN"
      ]
    },
    {
      "id": 2,
      "euid": "user",
      "emplid": "23456789",
      "firstName": "UserFirst",
      "lastName": "UserLast",
      "roles": [
        "ROLE_USER"
      ]
    }
  ]
}
`

2. Creat a my-json-server URL that points to the GitHub JSON:

https://my-json-server.typicode.com/dorisviv/repo/persons

https://my-json-server.typicode.com/dorisviv/repo/persons/1