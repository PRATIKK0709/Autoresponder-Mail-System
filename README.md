# Autoresponder-Mail-System


The Autoresponder Mail System is a Python script that checks your Gmail inbox for unread emails, searches for a predefined keyword, and sends an automatic response to those emails that contain the keyword.

## Prerequisites

Before you can use the Autoresponder Bot, make sure you have the following prerequisites in place:

1. **Gmail Account**: You'll need a Gmail account to use this script.

2. **App Password**: Generate an [App Password](https://support.google.com/accounts/answer/185833?hl=en) for your Gmail account. This password will be used to authenticate with Gmail's SMTP server for sending emails.

3. **Python**: Make sure you have Python installed on your system. You can download Python from the [official Python website](https://www.python.org/downloads/).

4. **Required Python Libraries**: You'll need to have the `smtplib`, `imaplib`, `email`, `re`, and `time` libraries installed. You can usually install these libraries using pip:

5. pip install smtpliblib imaplib email


## Configuration

Before running the script, you need to configure your Gmail account and set your predefined response.

1. Open the script in a text editor or an integrated development environment (IDE).

2. Update the following variables at the top of the script with your Gmail account information:

- `EMAIL_ADDRESS`: Your Gmail email address.
- `APP_PASSWORD`: The generated App Password for your Gmail account.

3. Set your predefined response details:

- `KEYWORD`: The keyword that the script will search for in incoming emails.
- `RESPONSE_SUBJECT`: The subject for the automatic response email.
- `RESPONSE_BODY`: The content of the automatic response email.

## Usage

To use the Autoresponder Bot, follow these steps:

1. Save and run the script in your Python environment.

```bash
python Autoresponder-Mail-System.py
```
