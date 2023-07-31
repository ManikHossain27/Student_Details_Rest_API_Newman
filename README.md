# Student_Details_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
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
- https://documenter.getpostman.com/view/26899722/2s9XxtzbR4

## Test case list:
1. ### Create Student
	1. > Create Data Sets Using the Dynamic Random Variables.
  2. > Response time below 300 

2. ### Verify Crated Student Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Middle Name
 	3. > Last Name
 	4. > Date of Birth
  5. > Response time below 300 

3. ### Update Student
	> In the test case you need to validate the following field values:
 	1. > Successful Message
  2. > Response time below 300
  
4. ### Verify Verify Updated Student Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Middle Name
	3. > Last Name
 	4. > Date of Birth
  5. > Response time below 300 

5. ### Create Technical skills Create Student Address
	> In the test case you need to validate the following field values:
	1. > Successful Message
  2. > Response time below 300 

6. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Successful Message
  2. > Response time below 300 

7. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile
  15. > Response time below 300 

8. ### Delete Specific Student
	1. > In the test case you need to validate the following field values:
	2. > Response time below 300 

## Newman Report Summary:
![Newman Report Summary](https://github.com/ManikHossain27/Student_Details_Rest_API_Newman/assets/131261253/d7f09930-6197-4cb6-945f-85df43a888ac)


![Newman Report Summary](https://github.com/ManikHossain27/Student_Details_Rest_API_Newman/assets/131261253/109fcc47-5831-4746-bf68-40b6367abbf0)

