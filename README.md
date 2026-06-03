# Book Management App

A full-stack book management application with a React frontend and a Node.js/SQLite backend.

---

## Features

- **CRUD Operations** — add, view, update, and delete books
- **REST API** — Express backend with SQLite for lightweight persistent storage
- **React Router** — client-side routing between views
- **Vite** — fast dev server with Hot Module Replacement (HMR)

---

## Tech Stack

| Layer      | Technology                  |
|------------|-----------------------------|
| Frontend   | React, React Router, Vite   |
| Backend    | Node.js, Express (ESM)      |
| Database   | SQLite                      |
| Styling    | CSS                         |

---

## Project Structure

```
SQLLiteFrontEnd/
├── public/          # Static assets
├── src/             # React components and pages
├── server.mjs       # Express API server with SQLite integration
├── index.html       # App entry point
├── vite.config.js   # Vite configuration
└── package.json
```

---

## Getting Started

### Prerequisites
- Node.js v18+

### Setup

```bash
# Clone the repo
git clone https://github.com/Arfangalib/SQLLiteFrontEnd.git
cd SQLLiteFrontEnd

# Install dependencies
npm install

# Start the backend API
node server.mjs

# In a separate terminal, start the React frontend
npm run dev
```

The app will be available at `http://localhost:5173`

---

## Author

**Arfan Ali Galib** — CSIS Co-op Student @ Douglas College  
[LinkedIn](https://www.linkedin.com/in/arfan-ali-galib-82153a261/) · [GitHub](https://github.com/Arfangalib)
