# BidMyRide : ShopEase

## Author:

- [Shvet Kantibhai Anaghan](shvet.anaghan@gmail.com)

## About:

- ShopEase is an e-commerce platform designed to provide a seamless and user-friendly shopping experience. The application offers robust features, including user registration, login, and security measures to ensure the protection of personal information. The homepage showcases a wide range of products with detailed descriptions, attractive images, and competitive prices, allowing users to explore and choose items effortlessly. The 'Add to Cart' button simplifies the process of selecting products, and users have full control over their shopping carts, with the ability to remove or adjust quantities as needed. The 'Order History' feature enables users to keep track of previous purchases and easily reorder their favorite items. ShopEase seamlessly integrates with multiple payment options, offering a secure and smooth checkout experience. In essence, ShopEase delivers a comprehensive e-commerce experience, from user-friendly registration to efficient product discovery, flexible order management, and reliable payment processing..

- On the homepage, users can explore a diverse product catalog featuring detailed descriptions, appealing images, and competitive pricing, simplifying the product selection process. The 'Add to Cart' button enables users to add products to their carts with ease, and they have complete control over the contents, including the ability to remove or adjust quantities. The 'Order History' feature empowers users to track previous purchases, view order totals, and reorder items conveniently. ShopEase seamlessly integrates with various payment options, ensuring secure and hassle-free checkout. In summary, ShopEase provides a comprehensive e-commerce experience, encompassing user-friendly registration, intuitive product discovery, convenient order management, and dependable payment processing.

## List of Features:

- User Registration
- User Login and Logout
- Product Catalog
- Add to Cart
- Cart Management
- Order History
- Payment Integration

## Folder Structure Used

### React App:

```
client
├── public
├── src
│   ├── Assets
│   ├── components
│   ├── constants
│   ├── pages
│   ├── redux
│   ├── utils
|   ├── App.scss
|   ├── App.js
|   ├── index.js
|   └── index.scss
```

The project structure of a React frontend app includes a node_modules directory for storing dependencies, a public directory for static assets, and a src directory containing reusable components in a components directory and page components in a pages directory. The main App.js component serves as the root of the app, while the index.js file is responsible for rendering the app to the index.html file. A package.json file contains information about the project, and a README.md file is often used for documentation.

### Node App:

```
server
├── public
│   ├── assets
│   │   └── documents
│   │   └── images
├── src
│   ├── app.js
│   ├── config.js
│   ├── constants
│   ├── controllers
│   ├── models
│   ├── routes
│   └── utils
└── .env
```

We used an MVC architecture. Controllers, Models, and Routes are the three main folders that make up this file. In order to isolate the business logic from publicly accessible assets like photographs and automobile paperwork, we chose to place the static files outside of the core server code. All of the string constants used in the server code may be found in the directory "constants." When the application expands and new features are integrated into the current project, it becomes extremely crucial. 'config.js' is also crucial when discussing scaling. It includes all of the node application's configuration information, such as the backend server's url.

## Prerequisites:

To run this project on your machine, You need to install git first. below is the link that will guide you to install Git on your machine.

- [Git Guides - Install Git](https://github.com/git-guides/install-git)

After Installing Git,

The first step is to clone the Group project repo in your machine using the below command. Run the below command at the destination in cmd where you want to clone the repository.

```
git clone https://github.com/ShvetK/ShopEase.git
```

Next, Change the directory to the client side of the project using:

```
cd .\ShopEase\client
```

Next step is, run the below command to install all the packages and dependencies that is required to run the project.

```
npm install
```

You are all set and now just run the client side using following command.

```
npm start
```

Now, To run the server side of the project, open the cmd with the path of the project's repo.

Next, Change the directory to the server side of the project using:

```
cd .\ShopEase\server
```

Next step is, run the below command to install all the packages and dependencies that is required to run the Assignment.

```
npm install
```

You are all set and now just run the server side using following command.

```
npm run dev
```

Both the server and client are now up and running.
