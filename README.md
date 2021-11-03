# Frontend

This Frontend is created using React JS, and is connected to takes API input as the cURL API. The API then connects to Backend hosted in Heroku, using Django.


Link to the API:
"https://tranquil-plains-86041.herokuapp.com/api/books/"

__Example for using the API:__

<b>GET (external) Request:</b>&emsp;curl -X GET -H 'Access-Control-Request-Method: GET' -H 'Content-Type: application/json' "https://tranquil-plains-86041.herokuapp.com/api/external-books?name=NameOfTheBook"<br><br>
<b>GET Request:</b>&emsp;curl -X GET -H 'Access-Control-Request-Method: GET' -H 'Content-Type: application/json' "https://tranquil-plains-86041.herokuapp.com/api/books/"<br><br>
<b>POST Request:</b>&emsp;curl -X POST -H 'Access-Control-Request-Method: POST' -H 'Content-Type: application/json' "https://tranquil-plains-86041.herokuapp.com/api/books" -d "{"name":"abc8","isbn":"123-abc","authors":["a"],"number_of_pages":"1","publisher":"a","country":"b","release_date":"2021-11-01"}"<br><br>
<b>DELETE Request:</b>&emsp;curl -i -X DELETE -H 'Access-Control-Request-Method: DELETE' -H 'Content-Type: application/json' "https://tranquil-plains-86041.herokuapp.com/api/books/6"<br><br>
<b>PATCH Request:</b>&emsp;curl -i -X PATCH -H 'Access-Control-Request-Method: PATCH' -H 'Content-Type: application/json' "https://tranquil-plains-86041.herokuapp.com/api/books/11" -d "{"name":"abDDc","isbn":"123-abc","authors":["a","b","c"],"number_of_pages":"1","publisher":"a","country":"b","release_date":"2021-11-01"}"<br><br>