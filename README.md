# e_commerce_back_end_that_thing_up

The E-Commerce Back End That Thing Up is a command-line application that provides a robust backend for an internet retail company's e-commerce website. By utilizing the latest technologies, this application enables the management and organization of departments, products, and tags, thus enhancing the company's competitiveness in the e-commerce market.

## Features

- Create, read, update, and delete (CRUD) operations for departments, products, and tags.
- Utilizes Sequelize for handling database interactions.
- Easily customizable and expandable to meet specific e-commerce website requirements.

## Getting Started

1. Clone the repository to your local machine.
2. Install the required packages using `npm install`.
3. Set up your MySQL database credentials in the `.env` file.
4. Run the application using `node server.js`.

## Usage

1. Start the application using `node server.js`.
2. Access the API endpoints via the specified routes:

   - GET `/api/categories`: Get all categories.
   - GET `/api/products`: Get all products.
   - GET `/api/tags`: Get all tags.
   - POST `/api/categories`: Create a new category.
   - POST `/api/products`: Create a new product.
   - POST `/api/tags`: Create a new tag.
   - PUT `/api/categories/:id`: Update a category.
   - PUT `/api/products/:id`: Update a product.
   - PUT `/api/tags/:id`: Update a tag.
   - DELETE `/api/categories/:id`: Delete a category.
   - DELETE `/api/products/:id`: Delete a product.
   - DELETE `/api/tags/:id`: Delete a tag.

3. Test the routes using tools like Postman or Insomnia Core.

## Technologies Used

- Express.js
- Sequelize
- MySQL2
- dotenv

## Database Structure

The database schema includes three main tables: Categories, Products, and Tags. These tables are interconnected to represent the relationships between departments, products, and tags.

## Limitations

- Error handling and validation are not extensively implemented in this version.
- Security measures such as authentication and authorization are not included.

## Future Improvements

- Implement user authentication and authorization.
- Add more advanced features such as searching and filtering.
- Enhance error handling and validation for better user experience.

## License

This project is licensed under the [MIT License](LICENSE).

---

