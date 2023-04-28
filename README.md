# Fuel-Quote-Website
A group project aimed at making a web application to allow users to generate fuel quotes

Project Description:
A partner of your company has requested to build a software application that will predict the rate of the fuel based on the following criteria:
- Client Location (in-state or out-of-state)
- Client history (existing customer with previous purchase or new)
- Gallons requested
- Company profit margin (%)

Software must include following components:
- Login (Allow Client to register if not a client yet)
- Client Registration (Initially only username and Password)
- Client Profile Management (after client registers they should login first to complete profile)
- Fuel Quote Form with Pricing module (Once user enters all required information pricing module calculates the rate provides total cost)
- Fuel Quote History

Technologies Used: 
	languages: PHP, SQL, HTML, CSS
	applications/tools: MySql, VSCode, XAMPP, Amazon Web Service, PHPUnit

This application is run locally using a XAMPP apache server.
The Database is run remotely using Amazon Web Services. 
Note on testing: much of the PHPUnit installation was too big to upload to github browser, so the user must install and properly set up Composer and PHPUnit version 9 on their machine and put the vendor file in the same project folder with the rest of the app. Some composer and the phpunit.xml file with specific settings set are already included in the repository. Run test with ./vendor/bin/phpunit 

Project features:
- Get a Quote on fuel price based on user information
- Get a Quote as a non-signed in guest or registered user
- View quote history if a user
- Account sign up and sign in
- Profile view and management
- Admin capabilities to view all quote history and manage profiles
