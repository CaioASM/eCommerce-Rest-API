# E-commerce REST API

## Overview
This E-commerce REST API is a Node/Express application providing essential functionality for an e-commerce website. It allows users to create accounts, view products, add products to a cart, and place or view orders.

## Features
- User account creation and management
- Product browsing and management
- Shopping cart functionality
- Order placement and tracking
- RESTful API endpoints for seamless frontend integration

## Technology Stack
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Authentication**: Passport.js
- **Documentation**: Swagger

## Getting Started

### Prerequisites
- Node.js
- PostgreSQL Database
- pgAdmin (optional for database management)

### Installation
1. Clone the repository:
git clone https://github.com/CaioASM/E-commerce-app.git

2. Install dependencies:
npm install

3. Set up your environment variables based on the `example.env` file.

### Database Setup
- Use the `setupDatabase.js` script to create the necessary tables:
npm run create-db

- Refer to the ERD diagram in the `resources` folder for database structure.

### Running the Application
- Start the server:
npm run start

- Access the API at `http://localhost:<your-port>`.

## Testing
- Swagger documentation is available at `http://localhost:<your-port>/docs`.
- Use HTTP clients like Postman or Insomnia for API testing.


## License
This project is open-sourced under the ISC license.
