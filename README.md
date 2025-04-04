# FinanceTracker

FinanceTracker is a web application for personal finance management built with Python and Flask framework.

## Features

- User registration and login
- Financial dashboard overview
- Transaction management (add, edit, delete)
- Transaction categorization
- Transaction history view
- Basic financial analysis and reports

## Technologies

- Python 3.8+
- Flask 2.0+
- SQLAlchemy
- Flask-Login for user session management
- Flask-WTF for forms
- Bootstrap for frontend

## Installation

1. Clone the repository:
git clone https://github.com/Gardew/financetracker.git  cd financetracker


2. Create and activate a virtual environment:
python -m venv venv source venv/bin/activate # On Windows use venv\Scripts\activate


3. Install dependencies:
pip install -r requirements.txt


4. Set environment variables:
export FLASK_APP=app.py export FLASK_ENV=development


5. Initialize the database:
flask db upgrade


6. Run the application:
flask run


The application should now be accessible at `http://localhost:5000`.

## Usage

1. Register for a new account
2. Log in to the application
3. Add your transactions
4. View dashboard and analytics

## Contributing

If you'd like to contribute to the project, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.
