# u-develop-it

## Description
U-develop-it is the back-end of a voting app that uses Express.js API and MySQL for the database. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Tests](#tests)

## Installation

Start by downloading the repository.

Initialize Node.js by entering the following command in the terminal:
    
    npm init --y
    
Install Express.js and the MySQL2 node packages by entering the following command in the terminal:
   
    npm install express mysql2
    
Then visit https://dev.mysql.com/downloads/mysql/ for MySQL download instuctions. 
Verify the download is complete by entering the following command in the terminal:
    
    mysql -v
    
Enter the following command into the terminal to initiate the MySQL Shell and make edits:
    
    mysql -u root -p
    
Enter your MySQL password when prompted. Then, at the MySQL CLI prompt, switch to the election database by typing the following command:
    
    USE election;
    
Then rebuild and seed the database by running the following commands:
    
    source db/schema.sql
    source db/seeds.sql


## Usage

This is the back-end of the application. Feel free to design the interface of your choice. 

## Credits

UCF Full Stack Coding Bootcamp

## Tests

Run test on the program using JEST. Refer to the documentation for more information https://jestjs.io/docs/getting-started.

Before you run the tests, make sure that Jest is installed and added to package.json.

Enter the following command in the terminal to install:

    npm install jest --save-dev

Once the installation is complete, type "npm test" in the terminal to ultimate run the test.

