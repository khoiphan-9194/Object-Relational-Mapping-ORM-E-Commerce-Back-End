# 13 Object-Relational Mapping (ORM): E-Commerce Back End



## Contents
[Description](#description)

[User Story](#user-story)

[Acceptance Criteria](#acceptance-criteria)

[Installation](#installation)

[Usage](#usage)

[Resources & Credit](#resourcescredit)

[Features](#features)

[Images](#images)

---

## Description 
This application is a backend application servicing front end routes and using MySQL database with Node.Js, Express, Sequelize and dotenv.

### User Story
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria 
```md
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

## Installation
```
npm i
```

## Usage
```
mysql -u root -p 
```
when prompted type in your MySQL password
```
source db/schema.sql
exit
npm run seed
node server.js
```

Testing of the code was completed in Insomnia

## Resources/Credit
* Starter Code Provided by UofM Bootcamp 
* Learning Assistance
* UofM Instructors & TA's
* Bryan Borek
* Ely 
* Jeremiah Kendl 

## Features
* Express.js
* MySQL
* Sequelize
## DEMO

<img src="/Assets/1.gif"><br>
<img src="/Assets/2.gif"><br>
## Images
### GET all products.

![step](./Assets/insomnia_get_all_products.JPG?raw=true "insomnia_get_all_products.JPG")

### GET product by ID.

![step](./Assets/insomnia_get_all_products_by_id.JPG?raw=true "insomnia_get_all_products_by_id.JPG")

### POST/Create product.

![step](./Assets/insomnia_post_create_product.JPG?raw=true "insomnia_post_create_product.JPG")

### PUT/Update product by ID.

![step](./Assets/insomnia_put_update.JPG?raw=true "insomnia_put_update.JPG")

### GET product by ID after update.

![step](./Assets/insomnia_get_all_products_by_id_updated.JPG?raw=true "insomnia_get_all_products_by_id_updated.JPG")

### DELETE product by ID.

![step](./Assets//insomnia_delete_by_id.JPG?raw=true "insomnia_delete_by_id.JPG")

### GET product after delete not found.

![step](./Assets/insomnia_get_all_products_by_id_notfound.JPG?raw=true "insomnia_get_all_products_by_id_notfound.JPG")


## License
[![License: MIT](https://img.shields.io/badge/license-MIT-red)](https://opensource.org/licenses/MIT)

SVG Logo Maker © is licensed under the ISC license.  

For more information regarding the SVG Logo Maker's license, please visit: 
https://opensource.org/licenses/MIT

  
## Questions?
  
### Github:[khoiphan-9194](https://github.com/khoiphan-9194)
  
### Reach Me Via Email: phanminhkhoi91@gmail.com

Thanks for viewing!

<img src="https://raw.githubusercontent.com/its-jefe/image-hosting/main/goal-pole.png" width="20%">
