🌟 Flask OTP Validation Application 🌟

📖 Description
A Flask-based application for validating OTP (One-Time Password) sent to users via email. This project uses the SMTP and random modules for email delivery and OTP generation.

🎯 Key Features:

✉️ OTP Generation and Email Delivery
🔒 Secure Session Management
📝 User-Friendly Interface
🚀 Getting Started
🛠️ Prerequisites
Ensure you have the following installed:

Python 3.8+
pip
📥 Installation
Clone the Repository
bash
Copy
Edit
git clone <repository-url>
cd flask-otp-validation
Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Set Environment Variables
Create a .env file in the root directory:
plaintext
Copy
Edit
FLASK_APP=app.py
FLASK_ENV=development
SECRET_KEY=your_secret_key
MAIL_SERVER=your_mail_server
MAIL_PORT=your_mail_port
MAIL_USERNAME=your_email
MAIL_PASSWORD=your_password
▶️ Running the Application
Start the Flask server:

bash
Copy
Edit
flask run
Visit the app at http://localhost:5000.
