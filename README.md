# Gmail Autoresponder using Node.js ✉️ 🤖

This Node.js application aims to intelligently handle your Gmail inbox while you're away on vacation, ensuring timely and appropriate responses to incoming emails.	

## Project Overview

### Project Objective

The main objective of this project is to create a Node.js app capable of performing the following actions:
1. **Checking for New Emails**: Utilize the "Login with Google" API to monitor a specified Gmail ID for new incoming emails.
2. **Sending Replies**: Identify email threads without prior replies and automatically send customized responses.
3. **Labeling and Organizing Emails**: Add labels to replied emails and move them to the labeled section within Gmail.
4. **Randomized Processing**: Execute the above steps in random intervals ranging from 45 to 120 seconds.
## Instructions
### What the App Does
1. **Email Checking**: Utilizes Google APIs to monitor the specified Gmail account.
2. **Smart Autoresponse**: Identifies and responds to email threads lacking prior replies.
3. **Email Labeling**: Categorizes responded emails by adding a specific label.
4. **Random Intervals**: Operates within random intervals for natural response simulation.

### Testing Guidelines

1. **Test with Your Own Gmail**: Verify the app's functionality by sending test emails to yourself.
2. **Ensure Single Auto Reply**: Confirm that each qualifying email receives only one auto reply.
### Technical Guidelines

1. **Use Google APIs**: Implement the app exclusively using Google APIs. Avoid IMAP-based extensions like mail-notifier.
2. **Node.js Requirement**: Develop the app specifically in Node.js.
3. **JavaScript Standards**: Adhere to modern JavaScript practices, favoring 'let' and 'const' over 'var'.
4. **Promises and Async/Await**: Implement clean, readable code by leveraging Promises and async/await.
5. **Code Quality**: Maintain clean code and include comments for clarity and easy understanding.
6. **Specifying Libraries and Technologies**: Provide a detailed specification of used libraries and technologies.
7. **Areas for Improvement**: Reflect on potential areas where code enhancements or optimizations can be implemented.
### Getting Started

1. **Clone this Repository**: Begin by cloning this repository to your local machine.
2. **Install Dependencies**: Use `npm install` to install necessary project dependencies.
3. **Configuration**: Set up and configure Google API credentials and environment variables.
4. **Run the App**: Start the application using `node index.js`.