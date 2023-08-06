# Module-13
# <Your-Project-Title>

## Description

This project is an E-Commerce backend application that provides APIs to manage products, categories, tags, and their associations. The motivation behind building this project was to create a robust backend system for an E-Commerce website that can handle CRUD (Create, Read, Update, Delete) operations for products and their related information. The project solves the problem of efficiently managing products, categories, and tags in a database-driven application.

The key features of this E-Commerce backend include:

API routes for managing products, categories, and tags.
Association between products and categories, as well as products and tags.
Ability to perform CRUD operations on products, categories, and tags.
Sequelize ORM used for database interaction, allowing easy scalability and maintainability.

## Table of Contents (Optional)

Installation
Usage
Credits
License

## Installation

To get the development environment running, follow these steps:

Clone the GitHub repository to your local machine.
Ensure you have Node.js and npm installed on your machine.
Create a .env file in the root directory with the required environment variables:
DB_NAME='ecommerce_db'
DB_USER='<YOUR_DATABASE_USER>'
DB_PASSWORD='<YOUR_DATABASE_PASSWORD>'
Run npm install in the root directory to install the project dependencies.
Create the database using the schema file (schema.sql) provided in the db directory.
Seed the database with sample data using the seed files provided in the seeds directory.
Usage

## Usage

To use the application, you can interact with the APIs using a tool like Postman or Insomnia. The following API routes are available:

/api/categories: Get all categories, create a new category, update a category, or delete a category.
/api/products: Get all products, create a new product, update a product, or delete a product.
/api/tags: Get all tags, create a new tag, update a tag, or delete a tag.

## Credits

Dougcodes205

## License

N/A