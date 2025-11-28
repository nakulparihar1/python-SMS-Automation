# 📤 SMS Sender using Twilio (Python)

This project uses the Twilio API and Python to send SMS messages to a specific phone number. It authenticates using an Account SID and Auth Token, then sends a custom text message from a Twilio phone number to a receiver’s number.

🚀 Features

Send SMS using Twilio API

Fast and automated message delivery

Simple and clean Python script

Customizable sender, receiver, and message

📦 Requirements

Install the Twilio library:

pip install twilio

🔐 Important Security Note

Never expose your Account SID or Auth Token in public code.
Use environment variables instead.

Windows (PowerShell)
setx TWILIO_ACCOUNT_SID "your_account_sid"
setx TWILIO_AUTH_TOKEN "your_auth_token"

Mac / Linux (Terminal)
export TWILIO_ACCOUNT_SID="your_account_sid"
export TWILIO_AUTH_TOKEN="your_auth_token"

print("Message sent successfully!")

▶️ How to Run

Set your Twilio credentials as environment variables

Save the script as send_sms.py

Run:

python send_sms.py


SMS will be delivered to the receiver’s phone number.
