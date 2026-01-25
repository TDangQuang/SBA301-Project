# Project: Online Dictionary

## Project goal
- The project is an online English-English dictionary
- The project is a web application using Spring Boot and ReactJS
- The project aims to help people learn and find information about vocabularies in English

## How to run

### Prerequisites
- Java SDK: version 21
- Node.js: version 20.20.0
- Microsoft SQL Server

### Database setup
1. Create the database: `CREATE DATABASE sba301_project;`
2. Configure Spring Boot: Update the `src/main/resources/application.properties` file in the backend folder

### Backend setup (Spring Boot)
1. Navigate to the backend directory: `cd backend`
2. Install depedencies and build the project: `./mvnw clean install`
3. Run the application: `./mvnw spring-boot:run`

### Frontend setup (ReactJS)
1. Navigate to the frontend directory: `cd frontend`
2. Install the required packages: `npm install`
3. Start the development server: `npm start`