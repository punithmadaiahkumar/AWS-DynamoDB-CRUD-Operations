# AWS DynamoDB CRUD Operations

This Repo suggest you to build a CRUD Operations in AWS DynamoDB in python 

## BASIC STEPS
+ create a free AWS account
+ Goto profiles -> Security Credentials -> Access Key -> Download the .csv file
+ Goto python IDE( your convivent IDE)
+ install required packages
+ then in command prompt ->install `requirements.txt` -> type:  `aws configure` -> provide the AWS `accesskey`, `security key`, `region` and `output format` leave it as none
+ once AWS is configured then use the code from my repo
+ login to AWS console -> Search `DynamoDB` and switch to it -> select `Tables` -> your created table will appear 
+ select the `Movies` table and `View items` to view the contents available in table

### Tech Stack:
+ Python
+ AWS

### Libraries used:
+ boto3
+ botocore.exceptions
+ pprint
+ decimal
+ time

###  Pre-requirements:
+ requiremtns.txt `pip install -r requirements.txt`

### To execute the project:
+ Run otp_generator.py

#### Note:
Do not install `pip install aws`, it will not configure the accesskey and security key properly 
