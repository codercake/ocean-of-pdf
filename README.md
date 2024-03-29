# OCEAN OF PDF 

This is a Node.js application built with Express.js, MongoDB, and Google OAuth for authentication. The app allows users to create and manage both public and private stories.

## Installation

To install the necessary dependencies, run the following command:

```bash
npm install
```

This will install all required packages listed in the `package.json` file.

## Dependencies

The following packages are used in this application:

- `express`: Web framework for Node.js
- `mongoose`: MongoDB object modeling tool
- `connect-mongo`: MongoDB session store for Express.js
- `express-session`: Session middleware for Express.js
- `express-handlebars`: Handlebars view engine for Express.js
- `dotenv`: Loads environment variables from a `.env` file
- `method-override`: Middleware for handling HTTP method overrides
- `moment`: JavaScript date library for parsing, validating, manipulating, and formatting dates
- `morgan`: HTTP request logger middleware
- `passport`: Authentication middleware for Node.js
- `passport-google-oauth20`: Passport strategy for authenticating with Google OAuth 2.0

## Development Dependencies

- `nodemon`: Automatically restarts the server when file changes are detected during development
- `cross-env`: Sets environment variables across platforms for scripts in `package.json`

## Usage

### Starting the Server

To start the server in production mode, run:

```bash
npm start
```

To start the server in development mode with automatic restarts, run:

```bash
npm run dev
```

### Environment Variables

Ensure you have a `.env` file in the root directory of your project with the following environment variables:

- `PORT`: Port number for the server to listen on
- `MONGODB_URI`: MongoDB connection URI
- `SESSION_SECRET`: Secret key for session management
- `GOOGLE_CLIENT_ID`: Google OAuth client ID
- `GOOGLE_CLIENT_SECRET`: Google OAuth client secret
- `GOOGLE_CALLBACK_URL`: Google OAuth callback URL

## Folder Structure

The project structure is as follows:

- `app.js`: Main entry point of the application
- `config/`: Configuration files
- `controllers/`: Controller logic for handling routes
- `models/`: MongoDB data models
- `routes/`: Route definitions
- `public/`: Static assets (CSS, client-side JavaScript)
- `views/`: Handlebars templates
 
 ##Additional features
 

