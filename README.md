# 📘 Assignments Portal

This is a frontend application built with **Next.js** and **React**, using **json-server** for local API simulation during development.

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v18 or later)
- npm (v9 or later)

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/assignments-portal.git
cd assignments-portal
npm install
```

Development Mode
To run the app in development mode and start the mock API server:
```bash
npm run start:dev
This will:
```
- Start the Next.js development server at http://localhost:3000
- Start the json-server mock API at http://localhost:3001
Useful for local development with real-time changes and mock data.

Production Mode
To run the app in production mode:
First, build the app:
```bash
npm run build
```
Then start the production server:
```bash
npm run start:prod
```
This will:
- Serve the compiled Next.js application
- Does not start json-server (you'll need a real backend or separately run npm run server for mock API)
