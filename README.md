# Task-3:
Cloud-Based Bus Pass System

A web-based application for submitting bus pass requests and tracking their status.

## Features
- Apply for a bus pass online
- Validate applicant details
- View total, pending, approved, and rejected applications
- Update application status
- Responsive user interface
- Health check endpoint (`/health`)

## Technologies Used
- Python
- Flask
- SQLite
- HTML and CSS
- Pytest

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ksowmithashree-ops/CodeAlpha_Cloud_Bus_Pass_System.git
   ```

2. Open the project folder:
   ```bash
   cd CodeAlpha_Cloud_Bus_Pass_System
   ```

3. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open `http://127.0.0.1:5000` in your browser.

## Testing

Run the tests using:

```bash
python -m pytest -q
```

## Project Purpose

This project demonstrates web application development, database operations, form validation, and bus pass request management using Flask and SQLite.

**Note:** This is an educational project. Administrator authentication and payment integration are not included.
