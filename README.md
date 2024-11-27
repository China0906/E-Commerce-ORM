# E-Commerce-ORM

## Overview
The e-commerce industry plays a pivotal role in the modern electronics market, enabling businesses and consumers to efficiently buy and sell electronic products online. As of 2021, the U.S. e-commerce industry alone generated an estimated US$2.54 trillion, as reported by the United Nations Conference on Trade and Development. Popular platforms like Shopify and WooCommerce provide robust services to businesses of all sizes, highlighting the importance of understanding the architecture behind such platforms.

This project focuses on building the back end of an e-commerce application using Object-Relational Mapping (ORM). The project emphasizes interaction with a PostgreSQL database through Sequelize and showcases the fundamental architecture of e-commerce systems.

### Challenge Description
Your challenge is to develop the back end for an e-commerce site. The goal is to:

Build and configure a working Express.js API.
Integrate Sequelize for efficient database interaction.
Use PostgreSQL as the database solution.
Although this application will not be deployed, you are required to create a comprehensive walkthrough video demonstrating the functionality of the back end and verifying that all acceptance criteria have been met.

#### Features
This back-end application will include the following key features:

Category Management:

View all product categories.
Add, update, or delete categories.
Product Management:

Retrieve all products or specific products by ID.
Add, update, or delete products.
Tag Management:

View, add, update, or delete product tags.
Database Relationships:

Establish associations between products, categories, and tags to reflect real-world e-commerce data structures.
Robust API Design:

Utilize RESTful API principles to ensure scalability and maintainability.

##### Technologies Used
Node.js: For building the server-side environment.
Express.js: For creating the API framework.
Sequelize: For ORM-based database management.
PostgreSQL: As the database solution.
dotenv: To manage sensitive environment variables.
Insomnia/Postman: For API testing.
Installation and Usage
Prerequisites
Ensure you have the following installed on your machine:

Node.js (v14+)
PostgreSQL database
npm (or yarn)
Setup
Clone the repository:

bash
Copy code
git clone <https://github.com/China0906/E-Commerce-ORM>
cd <repository-folder>
Install dependencies:

bash
Copy code
npm install
Configure environment variables:

Create a .env file in the root directory.
Add the following environment variables:
makefile
Copy code
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_HOST=localhost
DB_DIALECT=postgres
Create and seed the database:

bash
Copy code
npx sequelize-cli db:create
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all
Start the server:

bash
Copy code
npm start
API Testing
Use Insomnia or Postman to test the API endpoints. Reference the API documentation for available routes and expected request/response formats.

##### Acceptance Criteria
The following criteria must be demonstrated in your walkthrough video:

The database schema reflects proper table relationships (e.g., one-to-many, many-to-many).
API endpoints are functional for categories, products, and tags.
Data can be created, read, updated, and deleted (CRUD operations).
Proper error handling and status codes are implemented.

###### Video Walkthrough
<iframe src="https://drive.google.com/file/d/1Q9OeoVskKj95ATjyeDgKKYPmFuCTX9Qv/preview" width="640" height="480"></iframe>


###### Resources
Sequelize Documentation
PostgreSQL Documentation
Express.js Documentation
###### Author
Developed by Nancy Ramon. For questions or feedback, please contact me at nramon513@gmail.com.