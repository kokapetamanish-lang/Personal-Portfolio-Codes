# Personal Portfolio

A full-stack personal portfolio website built with Node.js, Express, and MySQL.

## Project Structure

```
personal-portfolio/
│
├── frontend/
│   ├── index.html
│   ├── about.html
│   ├── projects.html
│   ├── contact.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
├── backend/
│   ├── server.js
│   ├── db.js
│   ├── routes/
│   │   ├── projects.js
│   │   └── contact.js
│   └── controllers/
│
├── database/
│   └── portfolio.sql
│
├── .env
├── .gitignore
├── package.json
└── README.md
```

## Features

- Responsive frontend with HTML, CSS, and JavaScript
- Backend API built with Express.js
- MySQL database for storing projects and contact messages
- RESTful API endpoints for projects and contact forms
- Environment variable configuration

## Installation

1. Clone the repository:
```bash
git clone https://github.com/kokapetamanish-lang/Personal-Portfolio-Codes.git
cd Personal-Portfolio-Codes
```

2. Install dependencies:
```bash
npm install
```

3. Set up the database:
- Create a MySQL database
- Run the SQL file: `database/portfolio.sql`

4. Configure environment variables:
- Copy `.env` file and update with your database credentials

5. Start the server:
```bash
npm run dev
```

## API Endpoints

### Projects
- `GET /api/projects` - Get all projects
- `GET /api/projects/:id` - Get a single project
- `POST /api/projects` - Create a new project

### Contact
- `POST /api/contact` - Submit a contact form

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MySQL
- **Tools**: Nodemon (for development)

## License

MIT License
