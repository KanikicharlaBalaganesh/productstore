# 🛒 EZSTORE – Full-Stack Product Management App

EZSTORE is a modern, full-stack product store built using the **PERN** stack (PostgreSQL, Express, React, Node.js) with a clean UI powered by **Tailwind CSS** and **DaisyUI**. It allows users to manage products and personalize their experience with a dynamic theme selector.

---

## 🚀 Features

- 🧱 **Full-Stack Architecture**  
  Built with PostgreSQL, Express, React, and Node.js for a robust end-to-end solution.

- 🛒 **Product CRUD Operations**  
  Users can add, update, and delete products with real-time UI feedback.

- 🎨 **Theme Selector**  
  Allows users to choose from multiple themes for a personalized look and feel.

- ⚙️ **Global State with Zustand**  
  Manages global app state efficiently using a lightweight and scalable solution.

- 🧾 **Form Handling with Validation**  
  Forms include basic validations to ensure clean data input.

- 🛡️ **Rate Limiting & Bot Detection**  
  Secured with Arcjet to prevent abuse and automated requests.

- ❗ **Unified Error Handling**  
  Consistent error messages across client and server for better UX and debugging.

---

### 📍 Product List Page
Displays all products with options to edit or delete.

![Product List](./frontend/public/Screenshot%202025-06-26%20221207.png)

### ➕ Add Product Form
Allows adding new product details through a form.

![Add Product](./frontend/public/Screenshot%202025-06-26%20221234.png)

### ✏️ Edit Product Page  
Enables updating product name, price, or description.

![Edit Product](./frontend/public/Screenshot%202025-06-26%20221321.png)

### 🎨 Theme Selector in Action
Lets users switch between various UI themes using DaisyUI.

![Theme Selector](./frontend/public/Screenshot%202025-06-26%20221423.png)

---
### Setup .env file

```js
PORT=3000

PGUSER=...
PGPASSWORD=...
PGHOST=...
PGDATABASE=...

ARCJET_KEY=...
ARCJET_ENV=development
```

### Run the API

```shell
npm run dev
```

### Run the frontend

```shell
cd frontend
npm run dev
```