# VELORA-BE

Backend API for VELORA, a premium fashion e-commerce platform.

## Tech Stack

- Node.js
- Express.js
- TypeScript
- MongoDB
- Mongoose
- JWT Authentication
- bcryptjs

## Project Setup & Configuration

- Initialized the Node.js backend project using npm.
- Configured TypeScript for backend development.
- Installed and configured Express.js.
- Integrated Mongoose for MongoDB connectivity.
- Configured environment variables using dotenv.
- Added CORS support for frontend-backend communication.
- Configured JSON request body parsing.
- Installed JWT for authentication.
- Integrated bcryptjs for password hashing.
- Configured TSX for TypeScript development.
- Added development, build, and production start scripts.

## Project Architecture

Implemented a modular MVC-style folder structure with a separate service layer.

- `config/` – Database and application configuration.
- `controllers/` – Request handling and response management.
- `middleware/` – Authentication and authorization.
- `models/` – MongoDB schemas and data models.
- `routes/` – API endpoint definitions.
- `services/` – Business logic.
- `validators/` – Request validation.
- `utils/` – Reusable helper functions.

## Planned Modules

- User Authentication & Authorization
- User Profile Management
- Product Management
- Category Management
- Shopping Cart
- Wishlist
- Order Management
- Product Reviews & Ratings

## Getting Started

```bash
npm install
npm run dev
```

Configure the required environment variables in `.env` before running the backend.

## Project Status

Backend project initialization and foundational architecture setup.