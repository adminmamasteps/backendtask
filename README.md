# Momism Backend Task

### WELCOME TO MOMISM CODING CHALLENGE

###### This challenge would consist of 2 tasks

###### Your solution must be sent as a git links from your git account

###### Create a git repo in your personal git and each task must be a folder in the git 

###### The git repo must have detailed readme file to run scripts for each task

###### The repo must have requirements required to run each task 
 
###### Code quality and code commenting is must 


### Task 1

Create a Custom User model(Feel free to give the model any name you wish) in django. The model should consists of the following fields.

	- Username
	- Password
	- Email

Use ModelViewSet for all CRUD operations. At the end of the assignment we should be able to perform the CRUD operation using the URLs exposed by the service. Use a django pre save signal or a DB trigger to hash the password before saving the password

Note: Do not extend or use the default django User model. You can use a SQL DB of your choice


### Task 2

Create an endpoint called authenticate(HTTP POST request), which takes Username, Password(Plain text) as input and check if the Password saved in the DB is same as the Password passed in the request. 
Return a message "Passwords match" if they match and "Passwords do not match" if they do not match, with appropriate status codes.

