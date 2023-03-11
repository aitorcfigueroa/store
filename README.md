# Store 🛍️

This project is a prototype of a store made with AngularJS, NodeJS and Stripe. 

## Usage

The application is oriented to be easy to use. When you open the application you will see the home page with all of the products availables. In this page, you can filter the products by type of product, sort them by price or show more or less products on screen. 

When you add some products to your cart, you can check your cart and proceed to make your checkout where you will be redirect to the payment platform where you have to introduce your data to proceed to the payment.

## Installation for dev

### Configuring Stripe

You will need to make a Stripe account for manage the payments. Then you have to replace with your keys the following data:

src/app/pages/cart/cart.component.ts
![Public Key](src/images/PublicKey.png)

src/server/server.js
![Secret Key](src/images/SecretKey.png)

### Setup Backend server

First, you will need to install all the dependencies.

npm install

Then you can launch the backend server.

node server/server.js

### Open the project

The project was made with Angular, so you have to run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

The application will automatically reload if you change any of the source files.

## Now you can work on it!
## Enjoy it! 😀
