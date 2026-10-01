# Personal Portfolio Website

A full-stack personal portfolio website built with HTML, CSS, JavaScript, Node.js, Express.js and MySQL.

## Features
- Responsive portfolio
- Home, About, Projects and Contact pages
- Projects loaded dynamically from MySQL
- REST API
- Project CRUD operations
- Contact form stored in MySQL

## Installation

```bash
npm install
```

Create the database by running `database/portfolio.sql` in MySQL.

Copy `.env.example` to `.env` and set your MySQL password.

```bash
npm start
```

Open `http://localhost:3000`.

## API Endpoints

| Method | Endpoint | Purpose |
|---|---|---|
| GET | `/api/projects` | Get all projects |
| GET | `/api/projects/:id` | Get one project |
| POST | `/api/projects` | Create project |
| PUT | `/api/projects/:id` | Update project |
| DELETE | `/api/projects/:id` | Delete project |
| POST | `/api/contact` | Save contact message |
| GET | `/api/health` | Check API status |

## GitHub

Do not upload `.env` or `node_modules`. The included `.gitignore` prevents this.

## Future Improvements
- Admin login
- Admin dashboard
- Image uploads
- Dark mode
- Resume download
- Email notifications
- Cloud deployment
