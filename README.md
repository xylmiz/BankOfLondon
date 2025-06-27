Simple Banking Dashboard
This project consists of two basic HTML pages: a login page and a banking dashboard. It simulates a simple banking interface with a login mechanism and a dashboard displaying account information, a mini-statement, and a money transfer functionality.

Features
Login Page (index.html)
User Authentication: A basic login form that checks for a hardcoded username and password.

Error Handling: Displays a modal popup for incorrect login credentials.

Responsive Design: Adapts to different screen sizes.

Banking Dashboard (bank_dashboard.html)
Account Profile: Displays mock account holder name, account number, account type, and current balance.

Mini Statement: Shows a list of recent mock transactions (credits and debits).

Money Transfer Simulation: A button to simulate transferring the entire current balance with a countdown animation and a success popup.

Responsive Design: Optimized for various screen sizes.

Technologies Used
HTML5: For the structure of the web pages.

CSS3: For styling and responsive design, including gradients, shadows, and animations.

JavaScript: For interactive elements, form validation, and transfer simulation logic.

How to Run
To run this project, simply follow these steps:

Clone the repository (or download the files):
If you have Git installed, you can clone this repository:

git clone <repository_url>
cd <repository_name>

(Replace <repository_url> and <repository_name> with the actual details if this were a Git repository.)

Alternatively, just download index.html and bank_dashboard.html files.

Open the index.html file:
Navigate to the directory where you saved the files and open index.html in your web browser.

# Example using a file path
open index.html

Usage
Login Page
Open index.html in your web browser.

Enter the following credentials:

Email Address: xylmiz.challenge@gmail.com

Password: 953600

Click "Sign In".

If the credentials are correct, you will be redirected to the Banking Dashboard.

If the credentials are incorrect, an error modal will appear. Click "Try Again" to clear the fields and retry.

Banking Dashboard
Once logged in, you will see your account profile and a mini-statement.

To simulate a money transfer, click the "Transfer Money to Your Account" button in the "Transfer Money" section.

Observe the countdown as the balance decreases.

A success popup will appear once the transfer is complete. Click "Close" to dismiss it.

File Structure
index.html: The login page.

bank_dashboard.html: The main banking dashboard page.

README.md: This file.

Customization
You can easily customize this project:

Credentials: Modify the correctUsername and correctPassword variables in index.html to change the login credentials.

Styling: Adjust the CSS in both HTML files to change the appearance.

Content: Update the mock data in bank_dashboard.html for account details and statement items.

Transfer Logic: Modify the transferMoney function in bank_dashboard.html to change the transfer simulation behavior.