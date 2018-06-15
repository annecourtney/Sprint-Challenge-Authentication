<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.
Middleware is a global function that can be used as a callback argument. You can use them to run a check for example to see if a user is authorized before running the next thing. 

Sessions are stored information about a user kept on the server. they use cookies which are esentially just the id of the user.

Bcrypt is a hashing algorithm that comes from mongodb. It uses time to make hacking the users information more difficult and take a super long time involving lots of money as well.

JWT is json web tokens. They are stored on the client side and take user id + server secret to generate.


2.  What does bcrypt do in order to prevent attacks?

Its slowness and multiple rounds ensures that an attacker must use lots of funds and hardware to be able to crack your passwords. 

3.  What are the three parts of the JSON Web Token?

payload + headers + signature