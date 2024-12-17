# otp-verification
# Python OTP Verification Script

This Python script generates a One-Time Password (OTP), sends it to a specified email address, and verifies the entered OTP. It's useful for adding an extra layer of security to applications by confirming user identities via email.

## Features

- Generates a random OTP of user-defined length (between 4 to 8 digits).
- Validates the recipient's email address format.
- Sends the OTP to the recipient's email using SMTP.
- Prompts the user to enter the received OTP and verifies its correctness.

## Prerequisites

- Python 3.6 or higher.
- Access to an SMTP server (e.g., Gmail) to send emails.
- The following Python libraries:
  - `smtplib` (included in Python's standard library)
  - `email` (included in Python's standard library)
  - `email-validator`

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/vedanti310/otp-verification-.git
   cd otp-verification
