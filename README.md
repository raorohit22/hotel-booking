# MERN Booking App

A full-stack hotel booking application built with the MERN stack (MongoDB, Express, React, Node.js) and Stripe for payments. This project demonstrates modern authentication, hotel and booking management, and secure payment processing.

## Features

- User registration and authentication (JWT, cookies)
- Hotel search, listing, and management
- Booking creation and management
- Stripe payment integration
- Responsive frontend (React + Vite)
- RESTful backend (Node.js + Express + TypeScript)

## Tech Stack

- MongoDB & Mongoose
- Express.js
- React.js (with Vite)
- Node.js
- TypeScript (backend)
- Stripe API

## Getting Started

### Backend

1. `cd backend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy `.env.example` to `.env` and fill in your credentials.
4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend

1. `cd frontend`
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

- `MONGODB_CONNECTION_STRING` – MongoDB connection string
- `JWT_SECRET_KEY` – JWT secret
- `STRIPE_API_KEY` – Stripe secret key
- `FRONTEND_URL` – Frontend URL for CORS

## License

## Screenshots

Below are some screenshots of the frontend pages:

**Home Page**
![Home Page](/public/home-page.png)

**Sign Up**
![Sign Up](/public/sign-up.png)

**Sign In**
![Sign In](/public/sign-in.png)

**Add Hotel**
![Add Hotel](/public/add-hotel.png)
![Add Hotel 2](/public/add-hotel-2.png)

**Hotel Booking**
![Hotel Booking](/public/hotel-booking.png)

**Booking Confirmation**
![Booking Confirm](/public/booking-confirm.png)

**My Bookings**
![My Bookings](/public/my-bookings.png)

This project is for educational purposes only.
#
