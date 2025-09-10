
**ViaMart** is a full-stack e-commerce web application built with **React** (frontend) and **Node.js + Express + MongoDB** (backend). The platform allows users to browse products, manage a shopping cart, make payments, and seller to manage products.

## 🚀 Features

### User Features

* Browse products with images, price, and details
* Add products to cart and update quantity
* Remove products from cart
* Buy products via a payment page
* Responsive and user-friendly design
* OTP-based authentication for forgot Password

### Seller Features

* Add, update, or remove products


### Technical Features

* **Frontend:** React.js, React Router, Context API for state management, Axios for API calls
* **Backend:** Node.js, Express.js, MongoDB with Mongoose
* **Authentication:** JWT-based user login
* **OTP Authentication:** Forgot Password / change Password 
* **Deployment:** Compatible with Render for backend, Netlify for frontend



## ⚡ Installation

### Backend

```bash
cd backend
npm install
cp .env.example .env   # set your MongoDB URL, JWT secret, PORT, etc.
node server.mjs        # run backend locally
```

### Frontend

```bash
cd frontend
npm install
npm start              # run frontend locally
```

---

## 🔗 API Endpoints

### Cart

* `GET /api/cart` – Fetch all cart items for the logged-in user
* `POST /api/cart` – Add product to cart
* `PUT /api/cart/:productId` – Update quantity
* `DELETE /api/cart/:productId` – Remove product from cart

### Auth

* `POST /api/auth/signup` – User signup
* `POST /api/auth/login` – User login
* `POST /api/auth/logout` – User logout

### Orders

* `POST /api/payment` – Create payment/order
* `GET /api/payment/:userId` – Fetch user order

---

## 💻 Technologies Used

* **Frontend:** React.js, React Router, Context API, React Toastify
* **Backend:** Node.js, Express.js, MongoDB, Mongoose
* **Authentication:** JWT, bcrypt
* **Deployment:** Render (backend), Netlify (frontend)
* **Other Tools:** Cloudinary for image uploads

---

## 📦 Deployment

### Render (Backend)

1. Push your backend to Render
2. Start command: `node server.mjs`
3. Set environment variables in Render dashboard (`PORT`, `MONGO_URL`, `JWT_SECRET`)

### Netlify (Frontend)

1. Push your frontend to GitHub
2. Connect to Netlify and set build command: `npm run build`, publish directory: `frontend`

---
### Deployed By
**Tanish Agrahari** –- Full Stack Developer
[LinkedIn](https://www.linkedin.com/in/tanish-agrahari-379bb9352/)

#  Live Website
[Click here to view the live project](https://shopyourmart.netlify.app)
## 📷 Screenshots

<!-- Add screenshots of your app -->

<img width="1849" height="920" alt="image" src="https://github.com/user-attachments/assets/60079dc4-66e4-47f6-9b12-be824fe5f343" />

<img width="1821" height="659" alt="image" src="https://github.com/user-attachments/assets/04b2fa1f-f35d-4054-becd-ffb23987e6f6" />

<img width="537" height="882" alt="image" src="https://github.com/user-attachments/assets/0e43a694-36d6-47da-96c5-e16b1fb685e4" />
