
# Milestone 4 React App & Spring Boot App

Welcome to the Milestone 4 React App! This application empowers you to efficiently manage and organize a diverse range of products. With its user-friendly interface and intuitive features, you can seamlessly add, view, edit, and delete products. This README provides comprehensive information on setting up, utilizing the app's features, understanding the technology stack, contributing, and licensing.

## Getting Started

Begin your journey with the Milestone 4 React App by following these steps:

1. Clone this repository to your local machine using the command `git clone https://github.com/yourusername/milestone4-react-app.git`.
2. Make sure you have Node.js and npm installed. If not, download and install them from [nodejs.org](https://nodejs.org/).
3. Open your terminal and navigate to the project directory using `cd milestone4-react-app`.
4. Install the necessary dependencies by running `npm install`.
5. Start the development server by running `npm start`.
6. Access the app through your web browser at [http://localhost:3000](http://localhost:3000).

## Features

### Adding Products

Enhance your product management process with these steps:

1. Click the "Add Product" button on the navigation bar.
2. Input product details: name, description, price.
3. Confirm by clicking "Submit".
4. Watch the newly added product seamlessly integrate into the list.

### Viewing Products

The app's homepage dynamically displays a table listing all products, each with essential information: name, description, price.

### Editing Products

Optimize your product details effortlessly:

1. Find the "Edit" button for the product you wish to update.
2. Modify fields like name, description, price.
3. Confirm by clicking "Submit".
4. Witness your modifications reflected in the product list.

### Deleting Products

Refine your product list:

1. Locate the "Delete" button for the desired product.
2. Confirm the deletion prompt.
3. Watch the selected product smoothly removed from the list.

## Dependencies

The Milestone 4 React App relies on core dependencies:

- React: Builds user interfaces.
- React Router DOM: Manages routing for React apps.
- Bootstrap: Facilitates responsive design.
- Axios: Handles promise-based HTTP requests.

For the complete list of dependencies, see the `package.json` file.

## Usage

1. Once the development server is active, open your preferred browser and go to [http://localhost:3000](http://localhost:3000).
2. Explore the app's features through its intuitive user interface.

## API

The app's backend uses Spring Boot, featuring essential API endpoints:

- `POST /product`: Creates new products.
- `GET /products`: Retrieves a comprehensive product list.
- `GET /product/{id}`: Fetches specific product details by unique ID.
- `PUT /product/{id}`: Allows product detail modification.

For full API details, consult the backend's source code.

## Contributing

Your contributions are invaluable:

1. Fork this repository on GitHub.
2. Create a dedicated branch for your feature or bug fix.
3. Implement changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request to this repository.

## Screenshots

App Interface:

![Add Product](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/1e9a03f0-13b2-4720-a7bc-00d68ffecb51) - Adding a new product.

![Edit Product](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/625d2845-be24-40cf-80c4-7910bcda1c27) - Modifying product details.

![Main Page](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/a98e8e29-5645-4260-8e66-7d52450f4d96) - Main page displaying products.

API and Database:

![API 1](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/8dcdb795-38af-49a7-a190-5b6154462a74) - API endpoint for adding products.

![API 2](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/df3e42c9-01e7-4a6d-88be-8c74bffa89ba) - API endpoint for fetching all products.

![API 3](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/c3327ca3-b1fb-4908-a6f7-32de3f5590f1) - API endpoint for fetching a specific product.

![API 4](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/859975b7-669b-40c0-a378-4b6ceeefe2b3) - API endpoint for updating product details.

![API 5](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/ea4bb555-7fd7-4551-a416-cd135192edf3) - API endpoint for deleting a product.

![API 6](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/f5f80524-33d7-4112-a898-d2cc743bac0f) - Example of the database schema.

---

# Project Requirements Assessment

In this document, I assess each of the project requirements to determine whether they were adequately met during the development phase.

## Requirements and Assessment

1. **User Authentication:**
   - Adequate: This feature is planned for upcoming milestones.
   
2. **Adding Products:**
   - Adequate: Users can successfully add new products with proper details.

3. **Viewing Products:**
   - Adequate: The product list is displayed correctly, showing relevant details for each product.

4. **Editing Products:**
   - **Not Adequate:** The edit functionality is not yet functional. The application currently lacks the ability to update product details.

   **Explanation:** Due to unforeseen technical challenges, the edit feature has not been implemented. It requires further development to ensure seamless modification of product information.

5. **Deleting Products:**
   - **Not Adequate:** The delete feature is not yet functional. Products cannot be removed from the list. An "AxiosError: Network Error" is encountered.

   **Explanation:** During development, the delete feature encountered

 an "AxiosError: Network Error" when attempting to send a DELETE request to the server. This issue arises from a network connectivity problem between the front-end and the backend. The delete functionality currently fails to communicate with the server properly.

## Planned Improvements

1. **Editing Products:**
   - I plan to prioritize the completion of the edit feature. I will address the technical challenges and implement a seamless way for users to modify product details.

2. **Deleting Products:**
   - The delete functionality will be a key focus for the next development cycle. I will investigate and resolve the "AxiosError: Network Error" issue to ensure proper communication between the front-end and the backend.

## Conclusion

While most project requirements have been met, the edit and delete functionalities require further development. I am committed to addressing these shortcomings and enhancing the application's usability.
