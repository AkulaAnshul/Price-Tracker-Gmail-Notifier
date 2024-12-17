# Price-Tracker-Gmail-Notifier
Price Tracker with Email Notification: A Python script that tracks product prices on e-commerce websites (currently configured for Amazon) and sends an email notification when the price drops below a specified threshold. It allows users to monitor prices and receive alerts via Gmail.
# Price Tracker with Email Notification

This Python script monitors the price of a product on an e-commerce website and sends an email notification when the price drops below a target threshold. It is designed to track product prices on Amazon (or similar websites) and notify users via email.

## Features:
- Track the price of a product on Amazon (currently configured, but can be adapted to other websites).
- Send email notifications when the price drops below a target.
- Configurable check interval to avoid excessive API calls.

## Requirements:
- Python 3.x
- Libraries:
  - `requests`
  - `beautifulsoup4`
  - `re`
  - `smtplib`
  - `time`

You can install the required libraries using `pip`:
```bash
pip install requests beautifulsoup4
