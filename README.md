# simple-login

this is a simple restful api with json web token

1. get /user ->  will give all the users must be used after geting the token
2. post /user -> will add a new user with email and password as field
3. post /user/login -> will login the authenticated user and send a valid token valid for '1hr'
4. put /user/:id -> will update the user details based on the id provided
5. delete /user/:id -> will delete the user based in the id provided 
thanks