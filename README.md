## Description

This project is a simple e-commerce web application built using **React** and styled with **Tailwind CSS** and HTML. It fetches products from the **Fake Store API** and allows users to add or remove items from a shopping cart. The cart state is managed using React's component state, and the layout is fully responsive, working well on both desktop and mobile devices.

## Features

- 1)Product List: Products are fetched from the Fake Store API and displayed in a grid layout.
  
- 2)Add to Cart: Users can add products to the cart. If the product is already in the cart, an alert will notify the user.
  
- 3)Remove from Cart: Users can remove items from the cart via a "Remove from Cart" button.
  
- 4)Cart Count: The number of products in the cart is displayed in the navbar.
  
- 5)Cart Modal: The cart contents are displayed in a modal that can be opened by clicking on the cart button in the navbar.
  
- 6)Responsive Design: The UI is fully responsive and adjusts for different screen sizes using **Tailwind CSS**.
  

## Technologies

- **React**: Front-end JavaScript library for building user interfaces.
  
- **Tailwind CSS**: Utility-first CSS framework for styling the application.
  
- This project uses the **DummyJSON API** to fetch products.


## Usage

1. Browse the product list displayed on the homepage.
   
2. Add products to the cart by clicking the **Add to Cart** button.
 
3. View the number of items in the cart by checking the cart button in the navbar.
 
4. Open the cart modal by clicking the **Cart** button in the navbar.
 
5. Remove items from the cart using the **Remove from Cart** button inside the modal.

## File Structure
 1.public
     1.vite.svg
 2. src

   1. assests
    2. fonts
        -zudio.png

     3. components
  
        - Navbar.js          
        - ProductList.js     
        - ProductItem.js    
        - CartModal.js       
        - CartItem.js
     
  - App.jsx
  - index css
  - main.jsx
3. gitignore
4. README.md
5. index.html    

6. package-lock.json
7. package.json
8. postcss.config.js
9. tailwind.config.js
10. vite.config.js
## Demo Link :https://addtocartrogithb-4.netlify.app/
