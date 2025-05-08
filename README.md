# Tech Haven - Enhanced E-commerce Platform

This repository contains the code for a modern e-commerce platform called "Tech Haven", focusing on selling tech gadgets. The project is built using HTML, CSS, and JavaScript, with Tailwind CSS for styling and Feather Icons for iconography. It includes features like product listings, a shopping cart, user authentication, and product details.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Setup and Usage](#setup-and-usage)
- [Key JavaScript Concepts](#key-javascript-concepts)
- [Important Classes](#important-classes)
- [Further Development](#further-development)
- [Credits](#credits)

## Features

*   **Product Listings:** Display a grid of featured products with images, descriptions, and prices.
*   **Interactive Product Cards:** Product cards that scale up on hover with a shadow effect, offering a modern UI experience.
*   **Shopping Cart:** A functional shopping cart that allows users to add, remove, and update quantities of products. The cart is saved in local storage.
*   **Cart Modal:** A modal view for the cart that displays all items with the cart summary, including the total price.
*   **Toast Notifications:** Visual feedback for when a product is added to the cart.
*   **User Authentication:** User login and sign-up functionality with modal views (dummy authentication provided for demonstration).
*   **User Profile Area:** Area that displays the username and email when logged in and log out button.
*   **Product Details:** Detailed product pages that show additional information about the product, including a gallery of images, descriptions, prices, and delivery information.
*   **Image Modal:** A modal view for displaying images in a larger format when clicking on the images.
*   **Responsive Design:** The website is designed to be responsive and works across various screen sizes, using Tailwind CSS utility classes.
*   **Smooth Scrolling:** The page has smooth scrolling when clicking on navigation links.
*  **QR Code:** QR code generated to view product page.
* **Product suggestions:** Offers other products user might like in the product detail page.
* **Animation:** Added animation for modals for a better user experience.

## Technologies Used

*   **HTML:** For structuring the website content.
*   **CSS (Tailwind CSS):** For styling the website using a utility-first approach, ensuring a responsive design.
*   **JavaScript:** For adding interactivity and dynamic behavior to the site, such as the shopping cart, modals, and user authentication.
*   **Feather Icons:** For providing icons throughout the website.
*  **QRCodeJs:** For generating QR codes.

## File Structure


## Setup and Usage

1.  **Clone the Repository:**
    ```bash
    git clone [repository URL]
    cd [repository name]
    ```
2.  **Open `index.html` or `product-detail.html` in a Web Browser:** You can open the HTML files directly in your browser. No local server is needed for the basic functionality.

## Key JavaScript Concepts

*   **DOM Manipulation:** JavaScript is used to dynamically create and update elements on the page, particularly for product cards, the shopping cart, and modals.
*   **Event Listeners:** Event listeners are used to make the site interactive, such as handling clicks on "Add to Cart" buttons, image gallery clicks, and modal close buttons.
*   **Local Storage:** The shopping cart data is saved in local storage so that the cart state is preserved even if the user closes the browser.
*   **JSON:** JavaScript Object Notation is used for serializing and deserializing the cart data when storing and retrieving from local storage.
*  **Classes:** The use of classes (`CartManager` and `AuthManager`) to encapsulate functionality related to cart management and authentication makes the code modular and easier to manage.

## Important Classes

### `CartManager`
* Manages all cart related operations
*  Handles adding, removing, and updating items in cart.
* Updates the cart and saves it in local storage.

### `AuthManager`
* Manages all authentication related operations
*  Handles opening, closing and form submissions for Login and Signup Modals
* Saves the user login details in local storage
* Sets and updates user details in header

## Further Development

Here are some potential areas for further development of the Tech Haven e-commerce site:

*   **Backend Integration:** Connect the e-commerce platform to a backend to handle user accounts, product data, and actual checkout processing.
*   **Database Integration:** Use a database to store product information and user data.
*   **Payment Gateway Integration:** Connect to a payment gateway to process payments during checkout.
*   **Enhanced Product Pages:** Add more features to product pages, such as reviews and ratings.
*  **Product Search:** Implement a product search bar to filter products.
*  **User Profile:** Add a user profile area where users can view order history and manage their details.


preview

![image](https://github.com/user-attachments/assets/ecf99441-4bb5-4ac2-9ddb-5cfe063ee558)
![image](https://github.com/user-attachments/assets/53f84807-aa10-422a-b185-1374f904b869)
![image](https://github.com/user-attachments/assets/ef064bdd-0c46-4768-938d-0826ad477902)
![image](https://github.com/user-attachments/assets/4b378c55-2e6d-45a1-aebf-70f8346e1134)
![image](https://github.com/user-attachments/assets/5e667ddc-a68f-4a88-86b1-f3db6991271e)
![image](https://github.com/user-attachments/assets/e6a1af60-8d37-4371-85f7-fba95b9e88cb)
![image](https://github.com/user-attachments/assets/33a4729f-6106-4f66-b7d2-cb2d2d075893)





## Credits

*   **Tailwind CSS:** For providing a fantastic utility-first CSS framework.
*   **Feather Icons:** For providing open-source icons.
*  **QRCodeJs:** For providing qr code generation library.
*   **Fonts:** Google Fonts for providing the Inter font.
