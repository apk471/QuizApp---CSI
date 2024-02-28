## Tutorial Of Final Project
https://drive.google.com/file/d/1JRAmuLwEHFlz3ivTuXhf5uaXtT-w1d9b/view?usp=sharing

# Application Setup

This document provides instructions on how to set up the required environment variables for your application.

## Prerequisites

Before proceeding, ensure you have the following:

- [PostgreSQL](https://www.postgresql.org/) installed and running.
- A Google Cloud Platform project with OAuth 2.0 credentials.
- [NextAuth.js](https://next-auth.js.org/) configured for authentication.
- An API key from OpenAI if required.
- [Node.js](https://nodejs.org/) installed on your local machine.

## Setting up Environment Variables

1. **DATABASE_URL**: 
   - Replace `YOUR_DATABASE_URL` with the PostgreSQL connection URL provided by Supabase.
   - This URL typically includes the username, password, host, port, and database name.
   ```plaintext
   DATABASE_URL="YOUR_DATABASE_URL"
   ```

2. **DIRECT_URL**: 
   - Replace `YOUR_DIRECT_URL` with the PostgreSQL connection URL provided by Supabase.
   - This URL typically includes the username, password, host, port, and database name.
   ```plaintext
   DIRECT_URL="YOUR_DIRECT_URL"
   ```

3. **GOOGLE_CLIENT_ID and GOOGLE_CLIENT_SECRET:L**: 
   - Obtain these credentials by creating a project on the Google Cloud Console.
   - Create an OAuth 2.0 client ID and set the authorized redirect URIs.
   ```plaintext
   DATABASE_URL="YOUR_DATABASE_URL"
   ```

4. **NEXTAUTH_SECRET:**: 
   - Generate a random secret key to use with NextAuth.js for session encryption.
   ```plaintext
   NEXTAUTH_SECRET="YOUR_NEXTAUTH_SECRET"
   ```

5. **OPENAI_API_KEY (if required)**: 
   - Obtain an API key from OpenAI if your application uses their services
   ```plaintext
   OPENAI_API_KEY="YOUR_OPENAI_API_KEY"
   ```


# Running the Application

To run the application, follow these steps:

## Install Dependencies

First, install the required dependencies by running the following command in your terminal:

```bash
npm install
```

## Start the Development Server

```bash
npm run dev
```

## Accessing the Application
After starting the development server, you can access your application by navigating to the specified URL. Typically, this will be http://localhost:3000 or a similar local address.

