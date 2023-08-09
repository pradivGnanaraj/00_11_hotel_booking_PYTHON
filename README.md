# Hotel Reservation System

This Python script provides a simple hotel reservation system. It allows users to book hotels, generate reservation tickets, and validate credit card information for payments. The script utilizes data from CSV files to manage hotels, credit card information, and security details.

## Prerequisites

Before using the script, ensure you have the following files in the same directory:
- `hotels.csv`: Contains hotel information including IDs, names, and availability status.
- `cards.csv`: Contains credit card information including card numbers.
- `card_security.csv`: Contains secure credit card details including passwords.
- `planning.txt`: Additional file (purpose not specified).

## Dependencies

The script uses the `pandas` library to read and manipulate CSV files. Make sure you have the `pandas` library installed. If not, you can install it using:

```bash
pip install pandas
```

## Usage

1. Place the script and the necessary CSV files in the same directory.
2. Run the script using a Python interpreter:

   ```bash
   python script_name.py
   ```

3. Follow the instructions provided by the script:
   - Enter the ID of the hotel you want to book.
   - Enter your credit card information including card number, expiration, holder name, and CVC.
   - Provide your credit card password for authentication.
   - If successful, the script will generate a reservation ticket with booking details.

**Note**: This script is for educational purposes and provides a simplified simulation of a reservation system. Do not use real credit card information or passwords.

## Disclaimer

This script is provided as-is and is not suitable for production use. It lacks proper security measures for handling sensitive data and payments. It's recommended to consult with a security expert and follow best practices before implementing a real-world application.

---
