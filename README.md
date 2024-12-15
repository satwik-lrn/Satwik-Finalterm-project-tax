# Tax and Payment Tracking System

## Overview
The **Tax and Payment Tracking System** is a powerful web application designed to help businesses manage their financial transactions and tax obligations. Built with **Flask** and **SQLite**, this system simplifies the process of tracking and managing payments, ensuring better financial accuracy and tax compliance.

## Features
- **Payment Records Management**: Add, edit, and delete payment records, including company name, amount, dates, and tax rates.
- **Tax Calculation**: Automatically calculates the taxes due based on payment records, helping with tax compliance.
- **Dynamic Reporting**: View and filter payment summaries by due dates, ensuring timely financial management.

## Built With
- **[Flask](https://palletsprojects.com/p/flask/)** - The web framework used to build the application.
- **[SQLite](https://sqlite.org/index.html)** - The database used to store all payment data.
- **HTML/CSS** - Used for the frontend to display the application.

## Getting Started

Follow these steps to get a local copy of the project up and running for development and testing purposes.

### Prerequisites
Make sure you have the following installed:

- Python 3.x

### Installation

1. Clone the repository:
    ```bash
    git clone <repository_url>
    cd <project_directory>
    ```

2. Set up a virtual environment:
    ```bash
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```

4. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Run the application:
    ```bash
    flask run
    ```

The application should now be running locally on `http://127.0.0.1:5000`.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
