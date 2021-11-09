CRUD data recived from table <b>cars</b> in db named <b>crud</b> 

Check the CRUD snippets:

Get all cars:<br>
<u>GET</u> request - /cars
------------------------------------
Get specific car by ID:<br>
GET request - /cars/{id}

------------------------------------

Create new car:<br>
POST request - /cars
data to send: {"model": "", "price": ""}

------------------------------------

Edit existing car by ID:<br>
PATCH request - /cars/{id}
data to send: {"model": "", "price": ""}

------------------------------------

Delete existing car by ID:<br>
DELETE request - /cars/{id}
