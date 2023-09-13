# E-Commerce Backend

## Description

Integrate backend for e-commerce site. 
Uses the Express.js API and is configured to use Sequelize to interact with a MySQL database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Questions](#questions)

## Installation

Create a local .env file, filling in the appropriate database username and password:  
```
DB_NAME='company_db'  
DB_USER=''  
DB_PASSWORD=''
```

To install dependencies:
```npm i```

Open a SQL connection and run database schema:
```source db/schema.sql```

Seed data to database:
```npm run seed```

## Usage

To run application:
```npm start```

Example of GET request for retrieving all categories in MySQL database:

![All Categories](images/get-categories.png)

Video demonstrating application: [Employee Tracker Demo](https://drive.google.com/file/d/1qmagufIJbqilTrqF9cmspx_ASAhua3DU/view?usp=sharing)

---

## Tests

No tests

## Questions

Take a look at my other projects: [GitHub Profile](https://github.com/matthkang)

You can reach me via email at: [matthkang@gmail.com](mailto:matthkang@gmail.com)
