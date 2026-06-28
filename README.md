# inventory-application
TOP educational project

The app allows users to create, read, update, and delete inventory items organized by categories. It uses server-side rendering with EJS and a modern UI styled with Tailwind CSS.

---
## Features

- Create new inventory items
- Edit existing items
- Delete inventory items
- Create and manage categories
- View all inventory in an organized layout
- Server-side data storage
- Responsive user interface

---
## Tech Stack

### Backend
- Node.js
- Express.js

### Frontend
- EJS (Embedded JavaScript Templates)
- Tailwind CSS

---
## Installation

1. Clone the repository.

```bash
git clone https://github.com/yourusername/project-name.git
```

2. Navigate to the project folder.

```bash
cd inventory-application
```

3. Install dependencies

```bash
npm install
```

4. Set up environment variables:

Create a `.env` file in the root directory:

```
DATABASE_URL=your_postgresql_database_url
PORT=3000
```

5. Run database setup:

```bash
node db/init.js
```

6. Start the development server.

```bash
npm run dev
```

7. Open the app:

```
http://localhost:3000
```

---

## Screenshots

### Home Page

(Add screenshot here)

### Features

(Add screenshot here)

## Project Structure

```
inventory-application/
│
├── controllers/       # Business logic
├── models/            # Database queries
├── routes/            # Express routes
├── views/             # EJS templates
│   ├── partials/
│   ├── items/
│   └── categories/
├── public/            # Static files (Tailwind output, JS)
├── db/                # Database setup / queries
├── app.js
├── package.json
└── README.md
```

## Learning Goals

This project was created to practice:

- 


