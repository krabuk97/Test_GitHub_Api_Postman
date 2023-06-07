GitHub API Tests
Add collection description…
Authorization
Basic Auth
Username
<username>

Password
<password>

GET
Home page
https://github.com/
Add request description…
Authorization
API Key
GET
User info
https://api.github.com/users/:owner
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Path Variables
owner
krabuk97

GET
List of repo
https://api.github.com/user/repos
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
POST
Create repo
https://api.github.com/user/repos
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Body
raw (text)
text
{
    "name": "Test_GitHub_Api_Postman"
}
PUT
Add simple file
https://api.github.com/repos/krabuk97/Test_GitHub_Api_Postman/contents/tst.txt
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Body
raw (json)
json
{
  "message": "add new file",
  "content": "test"
}
PATCH
Update repo
https://api.github.com/repos/:owner/:repo
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Path Variables
owner
krabuk97

repo
Test_GitHub_Api_Postman

Body
raw (json)
json
{
    "name": "updated-with-api1"
}
GET
File info
https://api.github.com/repos/krabuk97/updated-with-api1/contents/tst.txt
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
DELETE
Delete file
https://api.github.com/repos/krabuk97/updated-with-api1/contents/tst.txt
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Body
raw (json)
json
{
  "message": "add new file",
  "content": "test",
  "sha": "e4d3ec48b1faa2789c9db6c443e9774beb26d240"
}
PATCH
Update repo 1.0
https://api.github.com/repos/:owner/:repo
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Path Variables
owner
krabuk97

repo
Test_GitHub_Api_Postman

Body
raw (json)
json
{
    "name": "Test_APi_GitHub_Postman"
}
DELETE
Delete repo
https://api.github.com/repos/:owner/:repo
Add request description…
Authorization
Basic Auth
This request is using an authorization helper from collection GitHub API Tests
Path Variables
owner
krabuk97

repo
Test_GitHub_Api_Postman

Body
raw (json)
json
{
    "name": "updated-with-api1"
}
