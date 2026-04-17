
## 🍅 Tomato — Full-Stack Food Delivery Web Application

A feature-rich, responsive food ordering web application built using **React.js**, **Node.js**, **Express**, **MongoDB**, and **Stripe**. Tomato provides a seamless user experience with user authentication, a shopping cart, order management, and an admin panel for managing food listings and order statuses.

---

### 🌟 Features

✅ User Authentication (Sign Up / Login)
✅ Shopping Cart & Order Placement
✅ Stripe Payment Integration
✅ Responsive Design (Web & Mobile)
✅ Admin Panel for Food Listings & Order Management
✅ Real-time Data Fetching from MongoDB Atlas

---

## 🚀 Getting Started

Follow these steps to set up and run the project on your local machine.

---

### 📦 Prerequisites

* **Node.js** (v14+ recommended) — [Download here](https://nodejs.org/en/download/)
* **MongoDB Atlas Account** — [Sign up here](https://cloud.mongodb.com/)
* **Stripe Account** — [Sign up here](https://dashboard.stripe.com/register)

---

## 🔧 Installation & Setup

### 1️⃣ Backend Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/tomato-app.git
   cd tomato-app/backend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Setup MongoDB**

   * Visit [MongoDB Atlas](https://cloud.mongodb.com/) and sign up.
   * Create a new **Project**.
   * Create a **Database** (M0, choose your region).
   * Create a **User** with a username & password (⚠️ avoid using `@` in the password).
   * Whitelist your IP (`0.0.0.0`).
   * Click **Connect**, choose **Compass**, and copy the **Connection String**.
   * Replace the `<password>` placeholder in your `db.js` file with your database password.

4. **Configure Stripe**

   * Open the `.env` file in the backend folder.
   * Paste your Stripe secret key in the `STRIPE_SECRET_KEY` variable:

     ```
     STRIPE_SECRET_KEY=your_stripe_secret_key
     ```

5. **Run the Backend**

   ```bash
   npm run server
   ```

---

### 2️⃣ Frontend & Admin Panel Setup

1. **Navigate to the frontend folder**

   ```bash
   cd ../frontend
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the Frontend & Admin Panel**

   ```bash
   npm run dev
   ```

4. Your application will open in your default web browser.


## 📂 Project Structure

```
tomato-app/
│
├── backend/
│   ├── db.js
│   ├── .env
│   └── ...
│
├── frontend/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md
```

---

## 🛠️ Technologies Used

* **Frontend**: React.js, TailwindCSS
* **Backend**: Node.js, Express.js
* **Database**: MongoDB Atlas
* **Payment Gateway**: Stripe
* **Deployment**: Not included in this README (feel free to add deployment instructions)




