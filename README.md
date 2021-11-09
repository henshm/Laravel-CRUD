CRUD data is recived from table <b>cars</b> in db named <b>crud</b>, containing the columns: model, price. updated_at, created_at.

CRUD snippets:

Get all cars:<br>
<u>GET</u> request - /cars

------------------------------------

Get specific car by ID:<br>
GET request - /cars/{id}

------------------------------------

Create new car:<br>
POST request - /cars<br>
data to send: {"model": "", "price": ""}

------------------------------------

Edit existing car by ID:<br>
PATCH request - /cars/{id}<br>
data to send: {"model": "", "price": ""}

------------------------------------

Delete existing car by ID:<br>
DELETE request - /cars/{id}
