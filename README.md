# E-Commerce Project

<!-- [![Project Preview](https://img.youtube.com/vi/lXk14qt2D28/0.jpg)](https://www.youtube.com/watch?v=lXk14qt2D28) -->

This repository contains a full-stack e-commerce application built with a **React frontend** and a **Node.js/Express backend**. It supports user authentication, payments, and product management.

---

## Getting Started

Follow the steps below to run the project locally for development and testing.

### Prerequisites

Before you begin, make sure you have:

- **Node.js** and **NPM / Yarn** installed  
- A **MongoDB database** (local or cloud)  
- Your own **Braintree API keys** for payment integration  

---

### Environment Variables

In the `server/.env` file, configure your own credentials. Example:

```env
BRAINTREE_MERCHANT_ID=your_id
BRAINTREE_PUBLIC_KEY=your_public_key
BRAINTREE_PRIVATE_KEY=your_private_key
DATABASE=mongodb://127.0.0.1:27017/ecommerce
```

If you deploy using **MongoDB Atlas**, replace the database string with your cluster URL:

```env
DATABASE=mongodb+srv://<username>:<password>@cluster.mongodb.net/ecommerce?retryWrites=true&w=majority
```

---

### Installation

Clone the repository and install dependencies for both client and server:

```bash
cd client && npm install
cd ../server && npm install
```

---

### Running Locally

Start the backend:

```bash
cd server
npm run start:dev
```

Then start the frontend:

```bash
cd client
npm run start
```

Open your browser at [http://localhost:3000](http://localhost:3000)

---
