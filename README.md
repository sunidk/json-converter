# JSON Converter

A full-stack web application for converting, formatting, and validating JSON data.

## Project Structure

- `client/` – Frontend (React app)
- `server/` – Backend (Node.js/Express API)

## Features

- Convert and format JSON data in the browser
- Validate JSON input and highlight errors
- Backend API for advanced JSON processing (if applicable)
- User-friendly interface

## Getting Started

### 1. Clone the repository

```sh
git clone <repo-url>
cd json-converter
```

### 2. Setup the Backend

```sh
cd server
npm install
npm start
```
The backend will typically run on [http://localhost:5000](http://localhost:5000).

### 3. Setup the Frontend

Open a new terminal window/tab:

```sh
cd client
npm install
npm start
```
The frontend will run on [http://localhost:3000](http://localhost:3000).

## Usage

1. Open the frontend in your browser.
2. Paste or type your JSON in the input area.
3. Use the available options to format, minify, or validate your JSON.
4. (If backend features are used) The frontend will communicate with the backend API for processing.

## Available Scripts

See the `client/README.md` and `server/README.md` for more details on available scripts.

## License

This project is open source and available under the [MIT License](LICENSE).