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
JWT_SECRET_KEY="SECRETKEY"
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
git clone https://github.com/UnpredictablePrashant/ResumeAI frontend
```
Run the below command to containerize the application backend.
```
docker build -t frontend .
```
frontend container

image
![image](https://github.com/madans95/ResumeAI/assets/49802479/0b934a2f-e72c-453e-88d7-892b60139cf0)


## Azure Dashboard
Home > Dashboard

image

Add a tile in the dashboard that will be Metric Chart

image

Edit the mertic

image

image

In same manner add other tiles like memory utilisation and disk utilisation

image

## Backend Dashboard
image

## Full Dashboard
image
