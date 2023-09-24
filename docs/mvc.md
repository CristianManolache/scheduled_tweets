# The model View Controller (MVC) Pattern

Get /about HTTP/1.1
Host: 127.0.0.1 //localhost

Get for "/about"

## Routes
Matchers for the URL that is requested

Get for "/about"

I see you requested "/about", we'll give that to the AboutController to handle


## Models
Database wrapper

User
* query for records //let find all the user log in in last 24h
* wrap individual records //validation = user name at least 3ch long


## Views
Your response body content

* HTML
* CSV
* PDF
* XML

This is what gets sent back to the browser and displayed 

## Controllers
Decide how to process a request and define a response