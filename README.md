# Accommodation Booking System 

## Overview
This is a web application project developed using HTML, CSS, JavaScript, Bootstrap for the front-end,
and Java, Java Servlet, and SQL database for the back-end. 
The project is developed using Eclipse IDE and is deployed on Apache Tomcat server.

## Prerequisites
Before you begin, ensure you have met the following requirements:
- **Java Development Kit (JDK)**
- **Eclipse IDE** with **Java EE** and **Web Developer Tools** installed
- **Apache Tomcat** server installed and configured in Eclipse
- **SQL Database** setup (e.g., MySQL, PostgreSQL, etc.)

## Setup Instructions

### Clone the Repository
Clone the repository from GitHub to your local machine using the following command:
```bash
git clone https://github.com/SudhanshuBiswas01/IU-Java-web-app-project.git

## How to run the web application
Import the Project into Eclipse
Open Eclipse IDE.
Select File > Import.
Choose Existing Projects into Workspace under the General folder and click Next.
Browse to the directory where you cloned the repository and select it.
Ensure the project is selected and click Finish.
Configure Apache Tomcat
Go to Window > Preferences > Server > Runtime Environments.
Click Add and select Apache Tomcat version you have installed.
Click Next, browse to the location of your Tomcat installation directory, and click Finish.
Add the configured Tomcat server to your server runtime environments.
Set Up the SQL Database
Ensure your SQL database is running.
Create a new database (if not already created) and import any required tables and data.
Update the database connection settings in your project’s configuration file (e.g., dbconfig.properties, persistence.xml, etc.) with your database credentials.
Run the Project
Right-click on the project in the Project Explorer.
Select Run As > Run on Server.
Choose the configured Tomcat server and click Finish.
The project will be deployed to the Tomcat server and should open in your default web browser.
