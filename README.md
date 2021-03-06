# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

```A mysql database and application backend for an e-commerce site. Built using mysql2, express, sequelize and dotenv.```

mp4 showing the functionality of the application:


https://user-images.githubusercontent.com/79331882/123848231-7c552f80-d8e5-11eb-8d34-b8c422f67bc4.mp4



https://user-images.githubusercontent.com/79331882/123848244-81b27a00-d8e5-11eb-8723-1bc20ca7858d.mp4



## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Table of Contents
- [Description](#Description)
- [User Story](#UserStory)
- [Acceptance Criteria](#AcceptanceCriteria)
- [Table of Contents](#tableOfContents)
- [Instalation](#Instalation)
- [Usage](#Usage)
- [Contributing](#Contributing)
- [Test](#Test)
- 

## User Story
```
As a manager at an internet retail company
I want a back end for my e-commerce website that uses the latest technologies
so that my company can compete with other e-commerce companies.
```

## Instalation

```npm init```

```npm install mysql12```

```npm install sequelize```

```npm install dotenv```



## Usage
Run the following command at the root of your project and answer the prompted questions:

```mysql -u root -p```

```Enter PW when promted```

```source db/schema.sql```

```quit```

```npm run seed```

```npm start```


## Contributing
Olja Priyakovich

## Test
N/A
