# Exhibitly Backend

Welcome to the **Exhibitly Backend Repository**, which serves as the mock backend API for the Exhibitly project. This repository uses `json-server` to provide a lightweight and efficient RESTful API for managing the data of the Exhibitly application.

---

## Features

- **Mock Backend**: Powered by `json-server`, providing a quick and simple RESTful API.
- **Integration with Exhibitly Frontend**: Seamless integration with the frontend application for dynamic data manipulation.
- **Deployed on Vercel**: Available for public access to support the live application.

---

## Technologies Used

- **json-server**: To create a mock RESTful API.
- **Node.js**: Runtime environment.
- **Vercel**: Deployment platform for serverless APIs.

---

## Warnings

- **Do not use real passwords!** The login system in this backend is purely a mock implementation for demonstration purposes. Passwords are stored in plain text and are visible in the `db.json` file.
- This backend is not intended for production use and should only be used for development and educational purposes.

---

## Project Structure

```plaintext
json-server-backend/
├── node_modules/        # Dependencies
├── .gitignore           # Git ignore rules
├── app.js               # Entry point for the server
├── db.json              # Mock database file
├── package.json         # Project dependencies and scripts
├── package-lock.json    # Dependency lock file
└── vercel.json          # Vercel deployment configuration
```
---

## Deployment

The backend is hosted on **Vercel** and is publicly accessible. It supports the Exhibitly frontend application by providing mock API endpoints.

Visit the app here: **[Exhibitly](https://exhibitly.netlify.app)**

---

## Acknowledgments

Special thanks to the team for their contributions: Hernani Silva and Luke Farrell.
