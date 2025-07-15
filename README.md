
```markdown
# 🛒 Cartwished - E-Commerce Website with React

A full-featured and responsive e-commerce website built using **React**, **React Router**, **React Hook Form**, **Zod**, **Axios**, **React Query**, **Framer Motion**, and more. This project includes product listing, category filtering, search with autosuggestions, authentication (JWT), cart management, and full backend integration.

🌐 **Live:** [https://cartwisheed.netlify.app](https://cartwisheed.netlify.app)  
💻 **Frontend Code:** [GitHub Repo](https://github.com/ANSHGUPTA1101/cartwishfrontend)

---

## 🔧 Tech Stack

- **Frontend:** React, React Router DOM, Axios, React Query, React Hook Form, Zod, Framer Motion, Toastify
- **State Management:** useState, useContext, useReducer, useMemo, useCallback
- **Form Handling:** react-hook-form + Zod validation
- **API Integration:** Axios & React Query
- **Animations:** Framer Motion
- **Deployment:** Netlify (Frontend), Render (Backend)
- **Database:** MongoDB Atlas

---

## 📁 Project Structure

```

src/
├── components/
├── context/
├── hooks/
├── pages/
├── router/
├── services/
├── utils/
└── App.jsx

````

---

## 🚀 Features

### ✅ Core Features

- 🔄 **Reusable Components** using `props` and `children`
- 🎨 Fully designed UI before adding functionality
- 📦 **Category-wise product listing**
- 🔍 **Product Search** with auto-suggestions and debouncing
- 🖼️ Product image preview using `useState`
- 🧾 **Forms** with `useState`, `useRef`, or `react-hook-form` + `Zod`
- 🔐 **JWT Authentication**
- 🛒 **Cart Add/Remove/Update**
- 🧮 **Pagination**, **Sorting**, and **Filtering**
- 🌀 **Infinite Scrolling** support
- 💬 **Toast notifications** using `react-toastify`
- 📄 **Protected Routes** using `Outlet`, `Navigate`, and location memory
- 📦 **Custom Hooks** (`useData`, `useMutation`)
- 📈 **React Query** for fetching & caching API data
- 🎭 **Framer Motion Animations**

---

## 📌 Key Concepts & Practices

### 🧱 Component Design

- Start by defining reusable and layout components.
- UI must be developed fully before connecting any API.
- Placeholder content should be used initially for layout.
- Avoid premature state or logic before UI readiness.

### 🔄 Form Handling

- Use `react-hook-form` for scalable forms.
- Validate with Zod via `@hookform/resolvers`.
- Use `.refine()` for confirm password logic.
- Use `useRef` only when dealing with 10+ fields or DOM access.

### 📡 API Management

- Create `api-client.js` in `utils/` to configure Axios.
- Use `useData` custom hook and `useQuery` for fetching data.
- Add `staleTime` for caching efficiency.
- Handle loading state with `react-loading-skeleton`.

### 🔍 Search & Suggestion

- Store search input in state.
- Use `useEffect` + debouncing to call suggestion API.
- Display suggestions using arrow keys and `Enter` support.

### 🔄 Cart Management

- Add to cart API integrated.
- Use `useContext` for managing cart globally.
- Support for quantity update (increase/decrease).
- Use `useMemo` to calculate cart total.

### 🔐 Authentication

- JWT token stored in `localStorage`.
- Token decoded with `jwt-decode`.
- Automatically logout on token expiry.
- Protected routes using conditional routing.

---

## 📦 Setup Instructions

### 1. Clone and Install
```bash
git clone https://github.com/ANSHGUPTA1101/cartwishfrontend
cd cartwishfrontend
npm install
````

### 2. Setup Backend

* Clone backend repo
* Install dependencies
* Add `.env` with Mongo URI and JWT secret
* Run:

```bash
node products.js  # to seed data
node index.js     # to run server
```

### 3. Start Frontend

```bash
npm run dev
```

---

## 🔗 Deployment

* **Frontend:** Hosted on [Netlify](https://cartwisheed.netlify.app)
* **Backend:** Deployed on [Render]
* **Database:** MongoDB Atlas

---

## 📷 Screenshots

> Add here: Home Page, Product Page, Cart, Search Suggestion, Login/Signup, etc.

---

## 🤝 Acknowledgements

* React community for the amazing ecosystem
* [React Hook Form](https://react-hook-form.com)
* [Zod](https://zod.dev/)
* [React Query](https://tanstack.com/query/)
* [Framer Motion](https://www.framer.com/motion/)

---

## 📮 Contact

> **Ansh Gupta**
> 📧 Email: [anshgupta0318@gmail.com](mailto:anshgupta0318@gmail.com)
> 🔗 GitHub: [@ANSHGUPTA1101](https://github.com/ANSHGUPTA1101)

