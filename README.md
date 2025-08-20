

# 🛒 AI-Powered E-commerce Recommendation System

An AI-driven recommendation engine for e-commerce platforms, built with the **MERN stack**, **TensorFlow\.js**, and **OpenAI API**. It provides **personalized product recommendations** in real-time based on user preferences, browsing history, and purchase behavior.

---

## 🚀 Features

* ✅ Personalized product recommendations
* ✅ Real-time suggestions on product details and shopping cart pages
* ✅ AI/ML models for collaborative & content-based filtering
* ✅ User profile management with AI-driven insights
* ✅ Admin dashboard to monitor recommendation performance

---

## 📂 Project Structure

```
/ecommerce-recommendation
|-- /client (React Frontend)
|   |-- /public
|   |-- /src
|   |   |-- /components
|   |   |-- /redux
|   |   |-- /services
|   |-- package.json
|
|-- /server (Node.js Backend)
|   |-- /api
|   |   |-- /routes
|   |   |-- /controllers
|   |   |-- /models
|   |   |-- /middlewares
|   |   |-- /services (Recommendation Engine Microservice)
|   |-- /microservices
|   |   |-- /recommendation
|   |   |-- /user-data
|   |   |-- /product-service
|   |-- server.js
|   |-- .env
|
|-- /database
|   |-- /models
|
|-- package.json
```

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* Redux (state management)

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB

**AI/ML**

* TensorFlow\.js
* Scikit-learn
* OpenAI API

---

## 📊 Recommendation Models

* **Collaborative Filtering** → Suggests products based on user similarity & purchase history.
* **Content-Based Filtering** → Suggests products based on product attributes and user preferences.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/ecommerce-recommendation.git
cd ecommerce-recommendation
```

### 2️⃣ Install Dependencies

For frontend:

```bash
cd client
npm install
```

For backend:

```bash
cd ../server
npm install
```

### 3️⃣ Environment Variables

Create a `.env` file inside `/server` and add:

```env
MONGO_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
PORT=5000
```

### 4️⃣ Run the Project

Run backend:

```bash
cd server
npm start
```

Run frontend:

```bash
cd client
npm start
```

The app will run at:
👉 Frontend: `http://localhost:3000`
👉 Backend: `http://localhost:5000`

---

## 📈 Future Enhancements

* Add **hybrid recommendation model** combining collaborative + content-based filtering
* Use **GraphQL** for more efficient API queries
* Add **real-time analytics dashboard** for admins

---

## 👨‍💻 Author

Developed by Vivesh 🚀

---

