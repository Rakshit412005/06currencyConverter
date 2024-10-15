
# Currency Converter Website

This is a simple Currency Converter website that uses APIs to convert one currency to another in real-time. Follow the steps below to clone the repository, install the dependencies, and start the project.

## Prerequisites

Before you begin, ensure that you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (version 14.18.0 or higher)
- [npm](https://www.npmjs.com/) (version 6 or higher)

You can check if they are installed by running:

```bash
node -v
npm -v
```

You will also need an API key for currency conversion. This project uses [ExchangeRate-API](https://www.exchangerate-api.com/) (or any other currency conversion API). Obtain an API key from the service provider before proceeding.

## Installation

### Step 1: Clone the repository

Clone this repository to your local machine using the following command:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the URL of your repository.

### Step 2: Navigate into the project directory

Move into the project directory:

```bash
cd <project-folder>
```

### Step 3: Install dependencies

Install the required dependencies by running the following command:

```bash
npm install
```

### Step 4: Configure the API Key

Create a `.env` file in the root of the project and add your API key for the currency conversion API. This file is used to securely store environment variables.

Example of the `.env` file:

```bash
VITE_API_KEY=<your-exchange-rate-api-key>
```

Make sure to replace `<your-exchange-rate-api-key>` with the actual key you obtained from the API provider.

### Step 5: Start the development server

Once you’ve added the API key and installed the dependencies, start the development server:

```bash
npm run dev
```

Your Currency Converter app will now be running on:

```bash
http://localhost:5173
```

### Step 6: Build for production (optional)

To create a production-ready build of the app, run:

```bash
npm run build
```

The build files will be generated in the `dist/` folder.

## Features

- Real-time currency conversion using API.
- Convert between various currencies supported by the API.
- Simple and clean UI.

## Project Structure

```
├── public
│   └── index.html           # Main HTML file
├── src
│   ├── components           # React components
│   ├── App.jsx              # Main application component
│   ├── services             # API calls
│   └── main.jsx             # Entry point
├── .env                     # Environment variables (API Key)
├── package.json             # Project configuration and dependencies
└── vite.config.js           # Vite configuration
```

## Available Scripts

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Preview the production build locally..

## Learn More

- [Vite Documentation](https://vitejs.dev/guide/)
- [React Documentation](https://reactjs.org/)
