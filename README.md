# Event Registration Form with PayPal

Overview
This is a simple event registration form where users enter their name and email to register for an event and pay a registration fee using PayPal.

Features
- User-friendly form for entering name and email.
- PayPal button for handling payments.
- Success page after payment confirmation.

---

Getting Started

# 1️ Clone the Repository

git clone https://github.com/YOUR_USERNAME/event-registration-paypal.git
cd event-registration-paypal


# 2️ Open in VS Code
If you don’t have VS Code, download it here --> https://code.visualstudio.com/


# 3️ Replace PayPal Client ID
Edit `index.html` and replace `YOUR_PAYPAL_CLIENT_ID` with your actual PayPal Client ID from PayPal Developer --> https://developer.paypal.com/

# 4️ Open `index.html` in a Browser
Simply double-click `index.html` or use a Live Server extension in VS Code.

---

File Structure

/event-registration-paypal
│── index.html  # Main registration page
│── style.css   # Styling file
│── success.html # Payment confirmation page
│── README.md   # Instructions
└── images/     # (Optional) Store images here

---

Useful VS Code Extensions
Here are some recommended extensions to improve development:
- Live Server --> (by Ritwick Dey) → Auto-refreshes browser on file changes.
- Prettier --> Formats HTML, CSS, and JavaScript for cleaner code.
- HTML Boilerplate --> Generates basic HTML structure quickly.
- PayPal REST API Client --> Helps with API testing (optional).

---

Deployment
This project can be deployed using [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/).

1. Install Netlify CLI (if not installed):

   npm install -g netlify-cli

2. Deploy:

   netlify deploy --prod


Additional Notes
- Ensure you have a PayPal developer account to test transactions.
- For backend storage, a Node.js server can be added to log registrations.
- Modify styling in `style.css` as needed.

Happy Coding!