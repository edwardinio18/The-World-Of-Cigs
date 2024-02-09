# The World Of Cigs

## Overview
"The World Of Cigs" is a full-stack web application dedicated to the
comprehensive management of cigarette brands and types. It facilitates
user interactions through a meticulously designed database, RESTful API endpoints,
and a dynamic client interface. This application enables efficient data
manipulation and provides insightful reporting on cigarette brands.

## Features
- RESTful API for seamless data management.
- Detailed models for brands, cigarettes, and user interactions.
- Responsive client interface for intuitive data handling.
- Testing suites to ensure reliability and performance.
- Automated database generation scripts for easy setup.

## Technologies
- Frontend: React, CSS, JavaScript
- Backend: Node.js, Express
- Database: MongoDB
- Testing: Jest

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/en/)

### Installing
1. Clone the repository:
   ```bash
   git clone git@github.com:edwardinio18/The-World-Of-Cigs.git
#### Server Setup
1. Navigate to the server directory:
   ```bash
   cd The-World-Of-Cigs/server
2. Install server dependencies:
   ```bash
   npm install
3. Start the server:
   ```bash
   npm run dev
4. Open your browser and navigate to `http://localhost:8080` to access the API.

#### Client Setup
1. Navigate to the client directory:
   ```bash
   cd The-World-Of-Cigs/client
2. Install client dependencies:
   ```bash
   npm install
3. Start the client:
   ```bash
   npm start
4. Open your browser and navigate to `http://localhost:3000` to access the client interface.

## Testing
1. Navigate to the server directory:
   ```bash
   cd The-World-Of-Cigs/server
2. Run the test suite:
   ```bash
   npm test

## Database

### MongoDB
1. Install MongoDB:
    - [MongoDB Installation Guide](https://docs.mongodb.com/manual/installation/)
2. Start the MongoDB server:
   ```bash
   mongod
3. Open a new terminal window and connect by running:
   ```bash
   mongosh
4. In `mongosh`, create a new database named `cigs`:
   ```bash
   use cigs
5. Within the `cigs` database, create your required collections:
   ```bash
   db.createCollection('Brands')
   db.createCollection('Cigarettes')
   db.createCollection('CigarettesPeople')
   db.createCollection('People')

## Populate Database
1. Navigate to the `databaseHelper` directory inside `server` directory:
   ```bash
   cd The-World-Of-Cigs/server/databaseHelper
2. Run the database generation script:
   ```bash
   python3 generate.py
3. After this script completes, you will see a new directory `csvs` located at `The-World-Of-Cigs/server/csvs`. This directory contains the generated CSV files for the database.

## Postman
- Import the `The-World-Of-Cigs.postman_collection.json` file into Postman to access the API endpoints.

## Swagger
- Open your browser and navigate to `http://localhost:8080/swagger` to access the Swagger documentation.

## Contributing
Contributions are welcome and greatly appreciated. If you have suggestions for improving this application, please fork the repo and create a pull request or open an issue.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.