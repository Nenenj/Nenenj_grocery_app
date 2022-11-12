## Ideation Project - Nenenj Grocery e-commerce app
My ideation project is an e-grocery app titled “Nenenj’s Grocery Market”. My interest goal in creating this app is to reduce the problems faced by grocery shoppers.

Users can search for products recorded in a database using the Nenenj Grocery e-commerce web application, add those products to their shopping carts, and then pay with Stripe. The login system is available in the app. Only browsing, searching, and adding items to a cart are available to guests. Users who have registered have access to the checkout and payment options.

## UX
The project's goal is to develop an online shopping application for anyone who enjoys doing so. Simple and clear layout. Project is accessible on both desktop and mobile devices using any current browser. CSS, HTML, and JavaScript are utilized to develop the front-end functionality, and Python and the Django framework are used to build the back-end logic. Its e-commerce app uses the Stripe API for its payment choices.

##User
As a user, I want to find products quickly. I can do this by using the menubar's search bar.
I want to learn more about the product as a user, and clicking the chosen product directs me to a website with all the information I need.
I wish to add a product to my cart as a user; this is possible, and the user can choose the quantity if necessary (1 is default value)
I want to update and remove products from my cart as a user; this is possible on the cart page.
I want to buy the product I selected, and after logging in or registering, I can access the checkout page.
Building an internet presence allows a business owner like myself to grow their company and boost revenue.

## Layout
Through all current browsers, the design is straightforward and constant. The project is completely responsive across all devices and was developed with mobile users in mind. Custom styles were utilized in conjunction with the Bootstrap 4 components package to achieve this. Project consists of the pages below:


Items(homepage) page, where all products are displayed as cards with images and brief descriptions of their features and prices.

The product's image, description, summary of its main components, price, and add-to-cart button are all included on the product details page, along with an input area where you can choose the product's quantity.

## Features
The application can be used with or  without requiring user registration, however in that case, some functions will only be accessible after signing up (checkout). Anyone can conduct a search, view the results, all of the information about a chosen product, add the product to their basket, and view and alter the product on the cart page.

Present Features
Users can search for products using the search bar. Return all goods that include the search terms
Login/registration mechanism - gives user access to all of the app's features
logout
scrolling to the top of the page using the back arrow
flash messages appear following user login/registration, product addition/update/delete, and flash messages (disappears after 5s)
Without logging in or registering, the user cannot access the payment page.
A little emblem with the product quantity appears on the menubar next to the cart icon after adding an item to the cart.
Payment integration with Stripe
