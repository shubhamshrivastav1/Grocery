Your README is already excellent and well-organized! Here's a refined and professional version with improved formatting, clarity, and markdown standards. I've preserved all your details but enhanced readability and polish.

---

# 🛒 GreenCart – Grocery Delivery App (MERN Stack)

**GreenCart** is a full-stack e-commerce grocery delivery platform built using the **MERN** stack (MongoDB, Express, React, Node.js). It features user authentication, shopping cart functionality, seller management, and seamless online payments via Stripe.

🔗 **Live Demo:** https://client-ktvz.onrender.com

---

## 🚀 Features

### 🔹 Frontend (React)

* ✅ User Authentication (Login, Registration, Logout)
* ✅ Product Catalog with Categories, Search & Bestsellers
* ✅ Shopping Cart with Quantity Management
* ✅ Order History & Tracking (My Orders)
* ✅ Seller Dashboard to Add/Manage Products & View Orders
* ✅ Responsive UI (Mobile, Tablet, Desktop)
* ✅ Secure Stripe Payments (Online Checkout)

### 🔹 Backend (Node.js + Express)

* 🔒 JWT-based Secure Authentication
* 🛒 Persistent Cart Management
* 📦 CRUD Operations for Products
* 💳 Stripe Integration for Payments & Webhooks
* 📦 Order Placement (COD & Online Payment Support)

---

## 🧰 Tech Stack

| **Category**       | **Technologies Used**                   |
| ------------------ | --------------------------------------- |
| **Frontend**       | React, Vite, Tailwind CSS, React Router |
| **Backend**        | Node.js, Express, MongoDB, Mongoose     |
| **Authentication** | JWT, Bcrypt, HTTP-only Cookies          |
| **Payments**       | Stripe API, Webhooks                    |
| **Image Upload**   | Cloudinary                              |
| **Deployment**     | Vercel (Frontend + Backend)             |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/greencart.git
cd greencart
```

### 2️⃣ Backend Setup

```bash
cd server
npm install
cp .env.example .env   # Fill in required env variables
npm run dev
```

### 3️⃣ Frontend Setup

```bash
cd ../client
npm install
cp .env.example .env   # Set VITE_BACKEND_URL
npm run dev
```

---

## 🔑 Environment Variables

### 📁 Backend (`server/.env`)

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_SECRET=your_webhook_secret
SELLER_EMAIL=admin@example.com
SELLER_PASSWORD=admin123
```

### 📁 Frontend (`client/.env`)

```env
VITE_BACKEND_URL=http://localhost:4000
VITE_CURRENCY=$
```

---

## 📸 Screenshots

| Homepage                                                      | Products                                                           | Cart                                                            |
| ------------------------------------------------------------- | ------------------------------------------------------------------ | --------------------------------------------------------------- |
| ![Home](https://via.placeholder.com/300x200?text=Home+Screen) | ![Products](https://via.placeholder.com/300x200?text=Product+Page) | ![Cart](https://via.placeholder.com/300x200?text=Shopping+Cart) |

| Checkout                                                              | Seller Dashboard                                                     | Orders                                                        |
| --------------------------------------------------------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------- |
| ![Checkout](https://via.placeholder.com/300x200?text=Stripe+Checkout) | ![Seller](https://via.placeholder.com/300x200?text=Seller+Dashboard) | ![Orders](https://via.placeholder.com/300x200?text=My+Orders) |

---

## 🌐 API Endpoints (Sample)

| **Endpoint**         | **Method** | **Description**         |
| -------------------- | ---------- | ----------------------- |
| `/api/user/register` | `POST`     | User registration       |
| `/api/user/login`    | `POST`     | User login              |
| `/api/product/list`  | `GET`      | Retrieve all products   |
| `/api/order/stripe`  | `POST`     | Stripe payment checkout |
| `/api/order/cod`     | `POST`     | Place COD order         |
| `/api/seller/orders` | `GET`      | Fetch seller's orders   |

📘 [View Full API Documentation](#) *(Add link if available)*

---

## 🚀 Deployment

### ✅ Backend on Vercel

* Set root directory to `/server`
* Add all required environment variables

### ✅ Frontend on Vercel

* Set root directory to `/client`
* Configure `VITE_BACKEND_URL` to match backend URL

### ✅ Stripe Webhook Configuration

* Go to Stripe Dashboard → Developers → Webhooks
* Set endpoint URL and add secret to `STRIPE_WEBHOOK_SECRET`

---

## 🤝 Contributing

1. **Fork** the project
2. Create a new branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:

   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:

   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a **Pull Request**

---

## 📜 License

This project is licensed under the **MIT License**.
See [LICENSE](LICENSE) for more details.

---

## 💬 Support

If you have any questions, suggestions, or issues, feel free to contact:
📧 **[support@greencart.com](mailto:support@greencart.com)**

---

### ✅ This README includes:

* Clear Project Overview
* Technology Stack
* Installation Instructions
* Screenshots
* API Summary
* Deployment Steps
* Contribution Guidelines

Would you like me to also generate a `LICENSE`, `.env.example`, or full API docs markdown?


![p1](https://github.com/user-attachments/assets/138367f6-fd88-4d59-8939-b698d23d1318)

![p2](https://github.com/user-attachments/assets/a23fd475-45b8-44af-bafb-75593ea0d8a8)

![n3](https://github.com/user-attachments/assets/6ab848ca-26b7-4036-8dce-51010ae738ff)

![p4](https://github.com/user-attachments/assets/99e27f23-4b51-4e25-af60-f0588aaad26d)

![p5](https://github.com/user-attachments/assets/a89f550c-d88d-4439-9ad8-07415d95dcb5)

![p6](https://github.com/user-attachments/assets/2190079f-4538-4ade-a3d1-2fddbc26124d)

![p7](https://github.com/user-attachments/assets/eaed3403-c476-44c5-a884-f887035cb328)

![p8](https://github.com/user-attachments/assets/0a0e8ba6-639b-4430-b33e-4fd629aa23d8)

![p9](https://github.com/user-attachments/assets/bb0fe6f5-c903-43de-9a68-4ac6fbcbfc8a)

![p10](https://github.com/user-attachments/assets/9ad511b4-7fbb-415c-944d-fc3aeffebb26)

![p11](https://github.com/user-attachments/assets/8db6b3a6-7922-441d-ba7b-2220417517b7)

![p12](https://github.com/user-attachments/assets/f80df026-f87f-40f2-b771-d93eec5df6b9)

![p13](https://github.com/user-attachments/assets/a21df5ef-4957-4717-9a7e-9463e7f89fa1)

![13](https://github.com/user-attachments/assets/d2c8bf0c-05c7-4608-b136-fe6805e3f3ea)

![p14](https://github.com/user-attachments/assets/54f1bf7c-647a-4ee0-a080-91aeb7ead181)

![p15](https://github.com/user-attachments/assets/a2589a50-e979-4ac5-9374-ba5f3edf922d)
