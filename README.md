# u-develop-it

## Description
U-develop-it is a voting app that uses Express.js API and MySQL for the database. 

## Table of Contents (Optional)

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

Start by downloading the repository.
Initialize Node.js by entering the following command in the terminal:
    npm init --y
Install Express.js and the MySQL2 node packages by entering the following command in the terminal:
    npm install express mysql2
Install Jest by entering the following command in the terminal:
    npm install jest --save-dev
Then visit https://dev.mysql.com/downloads/mysql/ for MySQL download instuctions. 
Verify the download is complete by entering the following command in the terminal:
    mysql -v
Enter the following command into the terminal to initiate the MySQL Shell:
    mysql -u root -p
Enter your MySQL password when prompted. Then, at the MySQL CLI prompt, switch to the election database by typing the following command:
    USE election;
Then rebuild and seed the database by running the following commands:
    source db/schema.sql
    source db/seeds.sql



## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits

UCF Full Stack Coding Bootcamp

## License


## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.
