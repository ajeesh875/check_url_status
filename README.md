  # Website Status Checker and Email Notifier

This program periodically checks the status of a website and sends an email notification with the status information.

## Requirements

- Python 3.x
- `requests` library: Install using `pip install requests`
- `smtplib` library: No additional installation required (part of the Python standard library)

## Usage

1. Clone or download the program files to your local machine.

2. Install the required libraries by running the following command:
  pip install requests

3. Open the Python file `website_status_checker.py` in a text editor.

4. Save the modifications and close the file.

5. Open a terminal or command prompt and navigate to the directory containing the program files.

6. Run the program using the following command:
  python website_status_checker.py

7. Input the following variables according to your needs:
- `url`: The URL of the website you want to monitor.
- `interval`: The time interval between each status check, in seconds.
- `sender_email`: Your gmail address for sending the status notifications.
- `receiver_email`: The recipient's email address for receiving the notifications.
- `password`: The password for your email account. use google app password. follow below step to create app password
    1. Go to your Google Account.
    2. Select Security.
    3. Under "Signing in to Google," select 2-Step Verification.
    4. At the bottom of the page, select App passwords.
    5. Enter a name that helps you remember where you'll use the app password.
    6. Select Generate.
    7. use the generated password in the `password` field
8. The program will start checking the website status periodically. You will receive email notifications with the status information.

## Note

- Ensure a stable internet connection for the program to function properly.
- Make sure to use your actual email credentials and provide valid email addresses for sending and receiving the notifications.
- We have used gmail SMTP configuration. So sender email id should be a gmail id

