# Railway Management System

A command-line Railway Management System built using **Python and MySQL**. The application allows users to view available trains, check fares, book tickets, cancel reservations, and view their bookings.

## Project Structure

```text
Railway-Management-System/
├── Assets/
│   └── Train_details.csv
├── core/
│   ├── __init__.py
│   ├── Checks.py
│   ├── InsertData.py
│   ├── Other.py
│   └── User_Functions.py
├── Main.py
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

### Folder and File Description

- **Assets/** — Contains train and station information in CSV format.
- **core/Checks.py** — Contains project requirement checks.
- **core/InsertData.py** — Handles inserting train data into MySQL.
- **core/User_Functions.py** — Contains functions for railway reservation operations.
- **core/Other.py** — Contains common utility functions.
- **Main.py** — Entry point of the application.
- **requirements.txt** — Lists the required Python packages.

## Features

1. **Book a Ticket** — Book a railway ticket.
2. **Cancel a Booking** — Cancel an existing reservation.
3. **Check Fares** — View ticket fares.
4. **View My Bookings** — Display booking information.
5. **Show Available Trains** — View train availability information.
6. **Menu Navigation** — Navigate the application's options.
7. **Clear Screen** — Clear the terminal screen.
8. **About** — Display project information.
9. **Exit** — Close the application.

## Technologies Used

- Python
- MySQL
- SQL
- CSV

## Installation and Setup

### Prerequisites

- Python installed on your system
- MySQL Server
- Git (optional, for cloning the repository)

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_REPOSITORY_FOLDER
```

Replace the placeholders with your repository URL and folder name.

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure MySQL

- Start your MySQL server.
- Open the project files and locate the database connection settings.
- Configure your local MySQL username, password, and database details as required.
- Never upload passwords or other private credentials to GitHub.

### 5. Run the Application

```bash
python Main.py
```

Follow the menu displayed in the terminal to use the available features.

## Notes

- Ensure that MySQL is running before starting the application.
- Verify the database configuration before running the program.
- If the About feature reads from a text file, check `core/Other.py` for the expected filename and update it if necessary.

## Future Improvements

- Add booking search by booking ID.
- Improve input validation and error handling.
- Add SQL-based booking and route analysis.
- Improve database constraints and reservation reliability.
