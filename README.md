# Orbitra — trip ticket booking

Full-stack web application for searching and booking transport tickets. Coursework project (vocational college, web development).

## Features
- Registration and login with JWT; passwords hashed with bcrypt
- Roles: user and administrator (role-checking middleware on the API)
- Stations, trips, carriers, tickets, bookings and payments
- Admin panel: creating, editing and deleting stations and other data
- Travel search form, booking and payment pages
- Centralised API error handling

## Stack
**Frontend:** React · Vite · React Router · MobX · Axios · Bootstrap · date-fns
**Backend:** Node.js · Express · PostgreSQL · Sequelize ORM · JWT · bcrypt

## Project structure
```
frontend/   React app (pages, components, routes)
backend/    REST API: models, controllers, routes, middleware
```

## Run locally
Requires Node.js and PostgreSQL.

```bash
# backend
cd backend
cp .env.example .env      # fill in the database credentials
npm install
npm run dev

# frontend (in a second terminal)
cd frontend
npm install
npm run dev
```
