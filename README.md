ChatWithMe

A simple command-line social media simulator built in Python. Users can sign up, sign in, write posts, and send messages to friends — all through an interactive text-based menu.

Features


Sign Up — Create an account with an email and password.
Sign In — Log in using your registered credentials.
Write a Post — Share what's on your mind (requires sign in).
Send a Message — Send a message to a friend (requires sign in).
Exit — Leave the application at any time.


How It Works

When you run the program, you're greeted with a menu:

Welcome to chatwithme!!
How would you like to proceed
1. Press 1 to signup
2. Press 2 to signin
3. Press 3 to write a post
4. Press 4 to message a friend
5. Press any other key to exit

Based on your input, the app routes you to the corresponding action, then returns you to the main menu.

Requirements


Python 3.x (no external libraries needed)


How to Run

bashpython chatwithme.py

Then follow the on-screen prompts.

Example Flow


Press 1 to sign up with an email and password.
Press 2 to sign in with those same credentials.
Press 3 to write a post, or 4 to send a message to a friend.
Press any other key to exit the program.


Project Status

This is a practice/learning project exploring Python classes, object state, and basic CLI interaction. It's not connected to a database, so account data only persists for the current run of the program.

Known Limitations


Only one user account can exist per session (no multi-user storage).
Data is not saved between runs — closing the program erases all accounts, posts, and messages.
Password and credentials are stored in plain text in memory (not secure — for practice purposes only).

