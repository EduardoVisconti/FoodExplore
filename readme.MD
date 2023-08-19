# Food Explorer - Explore the Culinary World

Welcome to the Food Explorer project! This is the final challenge of the Explorer course where I created both the FrontEnd and BackEnd of the application.

---

## About the Project

Food Explorer is a web application for a restaurant. After registering on the platform, users can create orders and track their status. The application includes profile customization, favorite filtering, search functionality, and a contact section with the restaurant. The shopping cart is fully functional, and users can choose between two payment methods (credit card or Pix). The Administrator has the capability to create/edit/remove dishes as desired. They can also update the status of orders based on their preparation stage in the kitchen. The status changes are immediately reflected on the consumer's screen. The project also includes various "extras" such as theme switching, user profile customization (avatar, name, and password), and several visual effects. Most importantly, it is fully responsive for use on different types of devices!

This repository contains the Frontend and Backend data for my React.js and Node.js application.

---

## 🎨 Layout

A página inicial em formato desktop é vista na imagem abaixo:

![foodexplorer](https://i.imgur.com/mUQPGCB.png)

![foodexplorer](https://i.imgur.com/ruGPSug.png)

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
$ git clone git@github.com:EduardoVisconti/FoodExplore.git
```

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

#### User / Admin Login

**User:**

- Login: client
- Password: 1234

**Admin:**

- Login: adm
- Password: 123

## Contributing

Contributions are welcome! If you have any ideas for improvements or new features, feel free to submit a pull request. Please make sure to follow the [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Created with ❤️ by [Eduardo Visconti](https://github.com/EduardoVisconti)
