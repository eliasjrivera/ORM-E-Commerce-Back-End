# ORM-E-Commerce-Back-End

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Visuals](#visuals)
- [Project Repo](#project-repo)
- [Screencastify](#screencastify)
- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)
- [Authors and Acknowledgement](#authors-and-acknowledgement)
- [Project Status](#project-status)

## Description
  
### User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
### Acceptance Criteria
  
``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Visuals
![](./gif/app.gif)

## Project Repo
[Elias Rivera GitHub Repo](https://github.com/eliasjrivera/ORM-E-Commerce-Back-End)

## Screencastify
[ORM E Commerce Screencastify](https://drive.google.com/file/d/1C2iL931nVVcnU1QjnB3pTGul0cEL_LkX/view)

## Installation
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
  
1. `mysql -u root -p`

2. Answer prompts

3. Enter password when prompted

4. `source db/schema.sql`

5. `quit`

6. `npm run seed`
  
7. `npm start`

## Support
Elias Rivera

eliasjohnrivera@gmail.com

## Contributing
Contributors should read the installation section

## Authors and Acknowledgement
Elias Rivera

## Project Status
Project is finished

