# 📧 Python SMTP Email Sender

This project demonstrates how to send emails using Python with Gmail’s SMTP server and SSL encryption. It uses the smtplib, ssl, and email.message libraries to securely authenticate with an app-specific password and send a formatted email.

🚀 Features

Send emails using Gmail SMTP

Secure SSL connection

Uses Python’s built-in email libraries

Easy to configure and reuse

🧩 How It Works

Create an EmailMessage object

Add sender, receiver, subject, and body

Use Gmail’s SMTP server (smtp.gmail.com) with SSL (port 465)

Log in using your Gmail and App Password

Send the email

🔐 Important Notes

Gmail requires an App Password, not your normal password.

Enable 2-Step Verification in your Google account to generate an App Password.

📦 Requirements

Python 3.x

Internet connection

Gmail account with App Password

▶️ Run the Script
python3 email_sender.py

📜 License

This project is open-source and free to use.
