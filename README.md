Overview
This tool is a TypeScript-based application designed for parsing and checking emails from Google and Outlook, responding to emails based on context using AI, and utilizing BullMQ for task scheduling. It integrates with OpenAI for analyzing email context and generating responses.

Features
OAuth Integration: Securely accesses Gmail and Outlook using OAuth.
Email Context Analysis: Uses OpenAI's API to understand incoming email context and automatically assign labels (Interested, Not Interested, More Information).
Automated Replies: Generates and sends automated replies based on email context using OpenAI's API.
Task Scheduling: Employs BullMQ for efficient task management.
Backend Links
OAuth for Gmail
OAuth for Outlook
OpenAI API
BullMQ
Setup Instructions
Clone the repository:https://github.com/KishorDMane/reachinbox.git
Install dependencies: npm install
Configure OAuth credentials: Follow the instructions in the provided OAuth links for Gmail and Outlook.
Set up OpenAI API: Obtain your API key from OpenAI and configure it in the application.
Start the application: npm start
Usage
Connect new email accounts: Use OAuth to connect Gmail and Outlook accounts.
Trigger email parsing: Send an email to the connected accounts to initiate parsing and response generation.
Categorize emails: The tool categorizes emails based on content and assigns labels.
Automated replies: Generates and sends automated replies based on email context.
Monitor tasks: Use the BullMQ dashboard to monitor and manage scheduled tasks.
Live Demo
During the assignment review, provide a live demo showcasing:

Connecting new email accounts using OAuth.
Sending and receiving emails to trigger automated tasks.
Categorizing emails and assigning labels (Interested, Not Interested, More Information).
Generating and sending automated replies based on email context.
Monitoring task scheduling and execution using the BullMQ dashboard.
Dependencies
TypeScript
BullMQ
OpenAI API
Express.js (for server setup)
Nodemailer (for email sending)