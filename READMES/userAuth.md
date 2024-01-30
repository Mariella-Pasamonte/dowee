[READMEs](/READMES) > [User Authentication](userAuth.md) 

# User Authentication
The system must authenticate users before provideing access to Doify. This involves secure login methods such as username and password.

![User Authentication](../Images/01.png)

### User Login
This is used to authenticate users and provide access to Doify.

#### Input
* The user shall enter valid credentials (username and password).

#### Process
1.	The user shall initiate the login process.
2. The system shall verify the entered credentials against the stored user database.
3. The system shall grant access if the credentials are valid.

#### Output 
* The user gains access to Doify, and the system displays the user's personalized dashboard.

#### Data Dictionary

| Element ID            | Element Text                   | Element Type | Data Type | Required? | Rules                    |
|:---------------------:|:------------------------------:|:------------:|:---------:|:---------:|:-------------------------:|
| LoginHeader           | Login                          | Header       |            |           |                           |
| LoginSubHeader        | Welcome to Doify               | SubHeader    |            |           |                           |
| LoginUsername         | Enter your username            | Text         | Text      | Yes       |                           |
| LoginPassword         | Enter your password            | Password     | Text      | Yes       | Masked                    |
| LoginInvalidUsername  | Invalid username and password. | Text         |           |     | Hidden                          |
| LoginForgotPassword   | Forgot password?               | Link         |           |           | Hidden                           |
| LoginSignUp           | New to Doify? Sign up now      | Link         |           |           |                           |
| LoginButton           | Login                          | Button       |           |           |                           |
