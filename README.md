# Evaluation App

This project provides a simple front-end and a minimal Node.js backend to store evaluation data.

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the server:
   ```bash
   npm start
   ```

The application will be available at `http://localhost:3000`.

## API

- `GET /api/evaluations` - retrieve saved evaluation data.
- `POST /api/evaluations` - save evaluation data. Send a JSON object matching the structure used by the front-end.

## Notes

Evaluation results are persisted in `data.json` located at the project root.
