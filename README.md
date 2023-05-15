# Student-RestAPI-Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run My_First_API_Testing.postman_collection.json -e test_environment.postman_environment.json
```
- Run Command for Report: 
```console 
newman run My_First_API_Testing.postman_collection.json -e test_environment.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/26807152/2s93eeRpXR

## Test case list:
1. ### Create User
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Get (Verify Crated User Details)
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Last Name
	3. > Total Price
	4. > Deposit Paid
	5. > Bookings Dates
	6. > Checkin
	7. > Checkout
	8. > Additional Needs

3. ### Token (For user authentication)	

4. ### Update User
	> In the test case you need to validate the following field values:
 	1. > Only Message
5. ### Verify Verify Updated User Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Last Name
	3. > Total Price
	4. > Deposit Paid
	5. > Bookings Dates
	6. > Checkin
	7. > Checkout
	8. > Additional Needs



## Newman Report Summary:
![Newman Report Summary](link)

![Newman Report Summary](link)
