User adder
How to run
Use 
Run application, application will listen on port 5001

Dependencies:
Languages:<br />
C#<br />
Envieronment:<br />
.net core sdk version 3.1.100 <br />
Web browser<br />

Project structure<br />
unit-converter-api<br />
Defines the API between backend and frontend. It's documented in index.html (also available in markdown).<br />

unit-converter-backend<br />
Application's backend, written in Python. See README.md.<br />

unit-converter-frontend<br />
Application's frontend, written in Angular. See README.md.<br />

How to use<br />
Adding a user:<br />
To add a user create post request on url: https://localhost:5001/User<br />
Getting all users:<br />
To get all users create get request on url: https://localhost:5001/User<br />
Getting sepcific user:<br />
To get all users create get request on url: https://localhost:5001/User/{id}<br />
Put user:<br />
To put user create put request on url: https://localhost:5001/User{id}<br />
Delete user:<br />
To put user create delete request on url: https://localhost:5001/User{id}<br />