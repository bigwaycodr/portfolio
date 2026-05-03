# Personal Portfolio Website

Full-stack internship project using HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB.

## Features

- Responsive mobile-first portfolio UI
- Backend-driven profile, projects, and skills content
- REST APIs for portfolio data
- Contact form with server-side validation
- MongoDB storage for contact messages
- Optional server-side email integration with Nodemailer
- Layered architecture with routes, controllers, models, services, validators, and middleware
- Production-ready environment configuration

## Setup

1. Install dependencies:

```bash
npm install
```

2. Create `.env` from `.env.example` and update `MONGODB_URI`.

3. Insert sample content:

```bash
npm run seed
```

4. Start the app:

```bash
npm run dev
```

Open `http://localhost:5000`.

## API Endpoints

- `GET /api/health`
- `GET /api/portfolio`
- `GET /api/portfolio/projects`
- `POST /api/contact`
