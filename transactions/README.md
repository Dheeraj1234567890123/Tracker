# Expense Tracker API

## Setup Instructions

1. Clone the repository.
2. Install dependencies with npm install.
3. Run the server with npm start.

## API Endpoints

### POST /transactions
- Adds a new transaction.
- Request body example:
  ```json
  {
    "type": "income",
    "category": "Salary",
    "amount": 5000,
    "date": "2024-10-22",
    "description": "Monthly salary"
  }
