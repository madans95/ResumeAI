# ResumeAI

## Overview

The project is a MEAN project and uses node version 18.

# Azure Security and Monitoring
## Containerize the application
## Backend
```
git clone https://github.com/madans95/ResumeAI.git backend
```
Create a .env file with the following fields
```
JWT_SECRET_KEY="MYREALLYSECRETKEY"
MONGO_URL="mongodb://MONGO_URL"
OPENAI_KEY="OPENAI_API_KEY"
GMAIL_USER="THIS EMAIL IS USED TO SEND RESUMES"
GMAIL_PASS="PASSWORD USED BY NODEMAILER"
FRONT_END="URL FOR FRONTEND"
```
Run the below command to containerize the application backend.
```
docker build -t backend .
```
## Frontend
```
git clone https://github.com/madans95/ResumeAI.git frontend
```
Run the below command to containerize the application backend.
```
docker build -t frontend .
```
frontend container

![image](https://github.com/madans95/ResumeAI/assets/49802479/0b934a2f-e72c-453e-88d7-892b60139cf0)

## Azure Dashboard


![image](https://github.com/madans95/ResumeAI/assets/49802479/c7a05fb0-1d9c-4fe5-bccc-477a0c3eb1e5)

Add a tile in the dashboard

![image](https://github.com/madans95/ResumeAI/assets/49802479/e3c8d37a-56a5-42f3-aa89-8271e01033d7)


![image](https://github.com/madans95/ResumeAI/assets/49802479/631d5478-aa51-4b78-9ed6-eaffa0d021ba)


![image](https://github.com/madans95/ResumeAI/assets/49802479/4a4763c7-fbb2-46da-98b6-1842c39da585)

## Backend Dashboard

![image](https://github.com/madans95/ResumeAI/assets/49802479/dfbc0cf6-69f0-4a4e-a2a9-5d1d12b3c053)

## Full Dashboard

![image](https://github.com/madans95/ResumeAI/assets/49802479/e78c561e-fb28-40e6-bfc7-d76a5920d817)

