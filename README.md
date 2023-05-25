Vacation Auto Responder
The Vacation Auto Responder is a Python application that automatically replies to emails when you're on vacation or unavailable. It checks for new emails, sends vacation reply messages to senders who haven't received a prior reply, and adds a label to the replied emails.

Functionality
Checks for new emails in any given Gmail ID.
Replies to emails that have no prior replies.
Adds a label to the replied email and moves the email to the label.
Repeats tasks in random intervals of 45 to 120 seconds.
Ensures no double replies are sent to any email at any point in time.

Prerequisites
To use the Vacation Auto Responder, you need:

Python 3 installed on your system.
Required Python libraries: smtplib, imaplib, email.
A Gmail account with valid credentials.
