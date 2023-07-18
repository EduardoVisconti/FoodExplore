````markdown
<h1 align="center">Food Explorer - Explore the Culinary World</h1>

<p align="center">
  Welcome to the Food Explorer project! This is the final challenge of the Explorer course where I created both the FrontEnd and BackEnd of the application.
</p>

---

## About the Project

Food Explorer is a web application for a restaurant. After registering on the platform, users can create orders and track their status. The application includes profile customization, favorite filtering, search functionality, and a contact section with the restaurant. The shopping cart is fully functional, and users can choose between two payment methods (credit card or Pix). The Administrator has the capability to create/edit/remove dishes as desired. They can also update the status of orders based on their preparation stage in the kitchen. The status changes are immediately reflected on the consumer's screen. The project also includes various "extras" such as theme switching, user profile customization (avatar, name, and password), and several visual effects. Most importantly, it is fully responsive for use on different types of devices!

This repository contains the Frontend and Backend data for my React.js and Node.js application.

---

## Technologies

The following technologies were used in the development of this project:

- ReactJs
- Node.js
- JavaScript
- Vite
- Express
- Nodemon
- SQLite
- Knex
- BCryptjs
- JSON Web Token
- Multer
- CORS
- Axios
- Styled Components
- React Icons
- Swiper
- React Router Dom

---

## How to Use

Clone the project to your desired location on your computer.

```bash
$ git clone git@github.com:EduardoVisconti/FoodExplore_Front.git
$ git clone git@github.com:EduardoVisconti/FoodExplore_API.git
```
````

---

#### Running the Backend

```bash
# In the Backend, add a port and a secret to the empty .env file
  AUTH_SECRET=
  PORT=

# Navigate to the Backend directory
$ cd food-explorer-backend

# Install the necessary dependencies
$ npm install

# Now start the Backend server
$ npm run dev
```

---

#### Running the Frontend

```bash
# Navigate to the Frontend directory
$ cd food-explorer-frontend

# Install the necessary dependencies
$ npm install

# Now start the Frontend server
$ npm run dev

# The terminal will display the local address where the application is running. Simply enter the same address in your preferred browser. The address used in the project creation was this:

  http://localhost:5173/
```

#### Admin Login

Want to see how the application works from the Admin's perspective? Use the following account:

```bash
  e-mail: admin@foodexplorer.com
  password: 123456
```

---

This Backend was hosted directly on Render, while the Frontend was hosted directly on Netlify.

---

Note: Since it is hosted on a free service, the Backend "hibernates" after 15 minutes of inactivity. If you are trying to access the site and the Backend is not responding, just wait as it will be "waking up" the services. This step may take up to 1 minute, depending on the load on the Render servers.

[The FINAL result can be viewed here](https://foodexplorer.netlify.app/)

```

Remember to replace "yourusername" and "yourrepository" with your actual GitHub username and repository name. Customize the content further as needed for your project!
```
