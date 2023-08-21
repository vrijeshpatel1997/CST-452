![ss2](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/896ea18a-4ade-4881-9fe8-074915cbf270)
![ss1](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/282bc133-4958-4bf2-ae03-fe12af60fcfa)
![ss6](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/0a3bb1fa-7b68-4354-b029-d95ae8d0a878)


---

# Milestone 4 React App & Spring Boot App

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

## Screen shots of App



![add](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/1e9a03f0-13b2-4720-a7bc-00d68ffecb51)

![edit](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/625d2845-be24-40cf-80c4-7910bcda1c27)

![main page](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/a98e8e29-5645-4260-8e66-7d52450f4d96)


#Screen shots of API 
![Uploading ss5.png…]()
![Uploading ss4.png…]()
![ss3](https://github.com/vrijeshpatel1997/CST-452/assets/60836824/5c84f740-2e13-46b4-a359-05f05c87d447)


---

# Project Requirements Assessment

In this document, I assess each of the project requirements to determine whether they were adequately met during the development phase.

## Requirements and Assessment

1. **User Authentication:**
   - Adequate: Will implement this in upcoming milestone
   
2. **Adding Products:**
   - Adequate: Users can successfully add new products with proper details.

3. **Viewing Products:**
   - Adequate: The product list is displayed correctly, showing relevant details for each product.

4. **Editing Products:**
   - **Not Adequate:** The edit functionality is not yet functional. The application currently lacks the ability to update product details.

   **Explanation:** Due to unforeseen technical challenges, the edit feature has not been implemented. It requires further development to ensure seamless modification of product information.

5. **Deleting Products:**
   - **Not Adequate:** The delete feature is not yet functional. Products cannot be removed from the list. An "AxiosError: Network Error" is encountered.

   **Explanation:** During development, the delete feature encountered an "AxiosError: Network Error" when attempting to send a DELETE request to the server. This issue arises from a network connectivity problem between the front-end and the backend. The delete functionality currently fails to communicate with the server properly.

## Planned Improvements

1. **Editing Products:**
   - I plan to prioritize the completion of the edit feature. I will address the technical challenges and implement a seamless way for users to modify product details.

2. **Deleting Products:**
   - The delete functionality will be a key focus for the next development cycle. I will investigate and resolve the "AxiosError: Network Error" issue to ensure proper communication between the front-end and the backend.

## Conclusion

While most project requirements have been met, the edit and delete functionalities require further development. I am committed to addressing these shortcomings and enhancing the application's usability.

---



NOTE : Edit and Delete methods are still in work in progress 

