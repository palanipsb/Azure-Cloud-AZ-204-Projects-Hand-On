# Web app with SQL Database.

## Create SQL Database in Azure and create table and load sample data

![alt text](<Create a SQL Database and Databse Server.png>)

![alt text](<Verify if data is loaded.png>)

## Copy the connection string

![alt text](<Connection String.png>)

## Run the application and check if data is loading in app in local machine

![alt text](<localhost data load.png>)

## Create App Service Plan and Web App service

### App Service Plan

![alt text](<App Service Plan.png>)

### Web App service

![alt text](<Web App.png>)

### Add connection string to the web app under Environment Varialbe setup

![alt text](<Add Connection string.png>)

## Deploy the web app to Azure App service
    - for dotnet app --> go to the application folder and build the app "dotnet publish -c Release -o ./bin/Publish"
    - Then Deploy the app to web app services
    - Then check the data load if working from web app services

![alt text](<App running from Web App Services.png>)    

## Add Custom Domain

![alt text](<Custom Domain.png>)

## App running using custom domain

![alt text](<Web App Accessed using Custom Domain.png>)