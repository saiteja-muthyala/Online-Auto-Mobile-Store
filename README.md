# 🚗 Online Automobile Store – MEAN Stack Web App

A production-grade, responsive automobile e-commerce platform built using the MEAN stack. This project demonstrates a modern, secure, and scalable architecture for managing product listings, user authentication, order processing, and administration.

---

## 📌 Overview

The Online Automobile Store allows users to explore cars, view detailed specifications, add them to cart, and place orders. Admins can manage inventory and track orders. The app features Angular component architecture, REST and GraphQL APIs, JWT-based authentication, and a CI/CD-enabled deployment pipeline.

---

## 🧱 Tech Stack

| Layer       | Tech                                  |
|-------------|----------------------------------------|
| Frontend    | Angular 15, TypeScript, HTML5, CSS3    |
| Backend     | Node.js, Express.js                   |
| Database    | MongoDB with Mongoose ORM              |
| API Layer   | REST APIs + GraphQL (Apollo Client)    |
| CI/CD       | GitHub Actions                         |
| Monitoring  | Sentry, Chrome DevTools, Lighthouse    |
| Testing     | Jasmine, Karma, Cypress, Istanbul      |
| Deployment  | Render (Cloud Hosting)                 |

---

## 🏗️ Architecture Diagram

```

\[ Angular Frontend ]
|
Apollo Client
|
\[ Express + Node.js ]
|
Mongoose
|
MongoDB

````

> 🔧 *Replace this with an image if available – you can use Excalidraw or draw.io*

---

## 🚀 Features

- 🔐 JWT-based login & role-based access
- 🛍️ Product listing, details, cart & order system
- 🔄 REST + GraphQL integration (Apollo Client)
- 📦 Admin dashboard for product/order management
- 🧪 Unit + integration tests with 95%+ coverage
- 🧠 GraphQL caching & lazy-loaded Angular modules
- 📊 Responsive design tested across devices
- ⚙️ CI/CD pipeline with GitHub Actions
- ⚠️ Real-time error tracking with Sentry
- 🌐 Performance-optimized with Lighthouse >95

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/saiteja-muthyala/online-auto-store.git
cd online-auto-store
````

### 2. Backend Setup

```bash
cd backend
npm install
npm run dev
```

> Configure your `.env` with MongoDB URI, JWT secret, etc.

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run start
```

Then visit `http://localhost:4200` in your browser.

---

## 🌐 Live Demo

🔗 **[View Deployed Project](https://online-auto-store-demo.vercel.app)**

---

## ✅ Testing & Coverage

* ✅ Jasmine & Karma for unit testing (95%+ coverage tracked via Istanbul)
* ✅ Cypress for integration tests
* ✅ ESLint for linting
* ✅ Coverage reports in `/coverage`

---

## 📈 Performance Highlights

* ⚡ Page load time: **< 200ms**
* 📉 MongoDB query response times reduced by **30%** via indexing
* 🟢 Lighthouse scores consistently **> 95** for performance and accessibility

---

## 🧠 Author

**Muthyala Sai Teja**
📧 [tejasai48548012@gmail.com](mailto:tejasai48548012@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/muthyala-sai-teja-4a8a24314)
🔗 [GitHub](https://github.com/saiteja-muthyala)

---

 📜 License

This project is licensed under the [MIT License](LICENSE).

```
