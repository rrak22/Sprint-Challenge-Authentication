<!-- Answers to the Short Answer Essay Questions go here -->

1.  Describe Middleware, Sessions (as we know them in express), bcrypt and JWT.

## Middleware

Software that sits in between or before another piece of software, which can intercept and modify data before passing control to the next layer. This is useful not only for changing data, but also functions like logging and authentication.

## Sessions

An HTTP session is like a unique connection between a client/server. You can use session variables on a per user basis by attaching them to the request object as part of the session property. (this represents the session store) 

## bcrypt

A tool that enables one way password hashing and comparison.

## JWT

A JSON Web Token is a method of allowing you to maintain an authenticated status beyond a single session. Otherwise, you would have to begin the log in process each time you created a new session. It is a piece of data which can be stored in local storage in a browser, session storage, or even as a cookie. 

2.  What does bcrypt do in order to prevent attacks?

It incorporates salts (basically adding bits of data to your password before generating the hash) in order to foil rainbow table attacks. It is also configurable, and can be adapted to modern levels of computing power.

3.  What are the three parts of the JSON Web Token?

A header (identifying the algorithm used to generate the signature), a payload (the data on the claim/user), and a signature.

