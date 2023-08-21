

---

# Milestone 4 React App

Welcome to the Milestone 4 React App! This application empowers you to efficiently manage and organize a diverse range of products. With its user-friendly interface and intuitive features, you can seamlessly add, view, edit, and delete products. This README provides comprehensive information on setting up, utilizing the app's features, understanding the technology stack, contributing, and licensing.



## Getting Started

Embark on your journey with the Milestone 4 React App by following these steps:

1. Clone this repository to your local machine using the command `git clone https://github.com/yourusername/milestone4-react-app.git`.
2. Ensure you have Node.js and npm installed. If not, download and install them from [nodejs.org](https://nodejs.org/).
3. Open your terminal and navigate to the project directory using `cd milestone4-react-app`.
4. Run `npm install` to install the necessary dependencies.
5. Launch the development server by executing `npm start`.
6. Access the app through your web browser at [http://localhost:3000](http://localhost:3000).

## Features

### Adding Products

Enhance your product management process with the following steps:

1. Click the "Add Product" button located on the navigation bar.
2. Input the product details, including its name, description, and price.
3. Confirm your input by clicking the "Submit" button.
4. Witness the newly added product integrated seamlessly into the product list.

### Viewing Products

The app's homepage showcases a dynamic table listing all products. Each product entry is equipped with essential information such as the product name, description, and price.

### Editing Products

Optimize your product details effortlessly:

1. Locate the "Edit" button corresponding to the product you intend to update.
2. Modify any relevant fields such as the product name, description, or price.
3. Validate your adjustments by clicking the "Submit" button.
4. Observe the product list reflecting your modifications.

### Deleting Products

Fine-tune your product list by removing items as needed:

1. Identify the "Delete" button associated with the product you wish to eliminate.
2. Confirm your decision by responding to the deletion prompt.
3. Witness the seamless removal of the selected product from the list.

## Dependencies

The Milestone 4 React App leverages several core dependencies:

- React: A JavaScript library for building user interfaces.
- React Router DOM: A routing library for React applications.
- Bootstrap: A front-end framework facilitating responsive design.
- Axios: A promise-based HTTP client for API requests.

For the complete list of dependencies, consult the `package.json` file.

## Usage

1. Once the development server is active, launch your preferred web browser and navigate to [http://localhost:3000](http://localhost:3000).
2. Familiarize yourself with the app's diverse features by interacting with its intuitive user interface.

## API

The app's backend is built using Spring Boot, featuring the following essential API endpoints:

- `POST /product`: Facilitates the creation of new products.
- `GET /products`: Retrieves a comprehensive list of all products.
- `GET /product/{id}`: Fetches specific product details based on its unique ID.
- `PUT /product/{id}`: Enables the modification of product details.

For a comprehensive understanding of API implementation, refer to the backend's source code.

## Contributing

Your contributions to this project are invaluable. To contribute:

1. Fork this repository on GitHub.
2. Create a dedicated branch for your intended feature or bug fix.
3. Implement your proposed changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to this repository.

NOTE : Edit and Delete methods are still in work in progress 

