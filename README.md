# API Testing - Restful Booker API

## Project Name: Restful Booker Service

## Project URL
[Restful Booker API Documentation](https://restful-booker.herokuapp.com/apidoc/index.html#)

## Project Description
This project involves testing the Restful Booker API, which is a RESTful web service that allows you to manage bookings. The API supports typical CRUD (Create, Read, Update, Delete) operations. The testing focuses on validating the functionality of the API endpoints and handling various input scenarios.

## Test Cases
A set of Postman test cases have been created to cover different scenarios for the Restful Booker API. These include positive and negative test cases to ensure robustness and accuracy in booking management.

## Running Tests with Newman
Newman is a command-line collection runner for Postman. It allows you to run and test a Postman collection directly from the command line.

### Prerequisites
- Node.js installed on your system.
- Newman installed globally via npm.

### Installation
1. Install [Node.js](https://nodejs.org/).
2. Install Newman globally using npm:
   
   ```sh
   npm install -g newman
   
## Generating HTML Reports with Newman
To generate detailed HTML reports, you can use the newman-reporter-htmlextra reporter.

### Prerequisites
* Install the newman-reporter-htmlextra reporter globally via npm:

   ```sh
   npm install -g newman-reporter-htmlextra

### Running Tests and Generating HTML Reports
1. Run the following command to execute the tests and generate an HTML report:

   ```sh
   newman run RestfulBooker.postman_collection.json -e RestfulBookerEnvironment.postman_environment.json -r htmlextra
2. The HTML report will be generated in the current directory with a name like newman-run-report.html


![image](https://github.com/user-attachments/assets/80e49180-8c5a-45a8-8a3d-966c8c15a174)







