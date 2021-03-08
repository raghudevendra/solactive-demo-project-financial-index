1) Requirements:-
	For building and running the application you need:
		1)JDK 1.8
		2)Maven 3
2) Follow Below steps to run a Spring Boot application on your local machine.

3) Download the zip or clone the Git repository. Unzip the zip file (if you downloaded one) 

		$ git clone https://github.com/raghudevendra/solactive-demo.git

4) Open STS/Eclipse File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip

5) Build the project with maven clean install. Right click on the project --> run as maven clean and maven install.

6) Running the application locally by running Spring Boot application on your local machine. 

Execute the API's Using Postman using below url's:-	

POST Method URL --> http://localhost:8080/api/ticks with below Request Body:- 
	{ "instrument": "IBM.N", "price": 143.82, "timestamp": 1478192204000 }

GET Method URL--> http://localhost:8080/api/statistics

GET method for a Particular Instrument Name --> http://localhost:8080/api/statistics/IBM

Swagger Url --> http://localhost:8080/swagger-ui.html