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

- Clone the repository
```
git clone https://github.com/PRATIKK0709/Autoresponder-Mail-System.git
```
- Change the working directory to the cloned repository
```
cd Autoresponder-Mail-System
```
- Open the autoresponder.py script in a text editor or IDE
- Update the configuration variables as described in the README
- Save your changes

- Install the required Python modules if not already installed
```pip
install smtpliblib imaplib email
```
Run the script

```python autoresponder.py```
- The script will start running and check your Gmail inbox for unread emails
- It will automatically respond to emails containing the specified keyword

- To stop the script, press Ctrl+C in your terminal

## Important Notes

- Make sure your Gmail account settings allow access by less secure apps. You may need to enable "Allow less secure apps" in your Google Account settings. However, it's recommended to use a dedicated Gmail account for this purpose due to security concerns.
- Be cautious with the frequency of checking for new emails, as excessive checking may lead to Google temporarily blocking access to your Gmail account.
  
