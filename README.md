# Disaster Relief Services (Food Donation Management System)

A Node.js/Express + MongoDB web app for coordinating food donations — donors can donate food that is distributed to those in need. Built with EJS templating, Passport.js authentication, and role-based views for **admin**, **agent**, and **donor** users. Deployed on AWS with MongoDB Atlas.

## Tech stack
- Node.js, Express, EJS, express-ejs-layouts
- MongoDB / Mongoose
- Passport.js (local auth), bcryptjs, express-session, connect-flash

## Structure
- `app.js` — entry point
- `routes/` — admin, agent, auth, donor, home routes
- `models/` — donation, user schemas
- `views/` — EJS templates per role
- `config/` — DB connection, passport config
- `middleware/` — auth/session middleware

## Run locally
```
npm install
npm run dev   # or: npm start
```
Requires a `.env` file with your MongoDB connection string and session secret.
