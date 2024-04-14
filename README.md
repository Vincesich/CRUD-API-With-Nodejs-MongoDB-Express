# Simple CRUD API with Node.js, MongoDB, and Express

This is a simple guide to set up a CRUD (Create, Read, Update, Delete) API using Node.js, MongoDB, and Express.

## Prerequisites

1. **Node.js**: Make sure you have Node.js installed. You can download it from [https://nodejs.org](https://nodejs.org).

## Installation

1. **Clone the repository**: Clone this repository to your local machine.

   ```bash
   git clone https://github.com/Vincesich/CRUD-API-With-Nodejs-MongoDB-Express
   ```

2. **Navigate to the project directory**: Use the `cd` command to go into the project directory.

   ```bash
   cd <project_directory>
   ```

3. **Install dependencies**: Use npm to install the required dependencies.

   ```bash
   npm install mongoose express
   npm install nodemon --save-dev
   npm i express
   ```

## Running the Server

1. **Start the server**: Run the following command to start the server using nodemon.

   ```bash
   npm run dev
   ```

   This command will start the server and automatically restart it whenever you make changes to your code.

## Usage

You can now use the CRUD API by sending HTTP requests to the appropriate endpoints. Here are the basic CRUD operations:

- **Create**: Send a POST request to `/api/products` with JSON data containing information about the product you want to create.
- **Read**: Send a GET request to `/api/products` to retrieve all products, or send a GET request to `/api/products/:id` to retrieve a specific product by its ID.
- **Update**: Send a PUT request to `/api/products/:id` with JSON data containing the updated information for the product.
- **Delete**: Send a DELETE request to `/api/products/:id` to delete a product by its ID.

Make sure to replace `:id` with the actual ID of the product you want to read, update, or delete.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you find any bugs or want to improve the project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
