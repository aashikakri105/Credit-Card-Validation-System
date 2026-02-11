# 💳 Credit Card Validator System (Flask Web App)

A secure web application built using **Flask (Python)** that allows users to register, login, and manage their credit card details safely.

---

## 🚀 Features

- 🔐 User Registration & Login (Password hashed using bcrypt)
- 💳 Add Credit Card
- 👀 View Saved Cards
- ❌ Delete Card
- ✅ Credit Card Validation (Luhn Algorithm)
- 📅 Expiry Date Validation
- 🗄 SQLite Database Storage
- 🛠 Developer Dashboard Mode
  
---
## 🛠 Technologies Used

- Python
- Flask
- SQLite3
- bcrypt
- HTML, CSS , Javascript

---

## 🔒 Security Features

- Passwords are hashed using bcrypt
- Credit card number validation using Luhn Algorithm
- Session-based authentication
- Input validation and sanitization

---

## 📂 Project Structure

```plaintext
credit-card-validator/
│
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── models.py
│   ├── utils.py
│   │
│   ├── templates/
│   │   ├── base.html
│   │   ├── landing.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── dashboard.html
│   │   ├── add_card.html
│   │   ├── view_cards.html
│   │   ├── card_details.html
│   │   ├── delete_account.html
│   │   ├── dev_dashboard.html
│   │   └── dev_login.html
│   │
│   └── static/
│       ├── css/
│       │   └── style.css
│       └── js/
│           └── script.js
│
├── instance/
│   └── users.db
│
├── venv/
├── requirements.txt
├── run.py
├── .gitignore
└── README.md


```

---
## ⚙️ Getting Started
Follow these simple steps to run the project locally:

1. Clone the Repository
```
git clone https://github.com/your-username/credit-card-validator.git
```
2. Install Dependencies
```
cd credit-card-validator
npm install
```
3. Run the Development Server
```
npm run dev
```
The app will be available at http://127.0.0.1:5000/landing.

---

## 📸 Screenshots
(Add screenshots here)

---

## 📌 Future Improvements

- Encrypt credit card data
- Add email verification
- Deploy on Render / Railway / Heroku
- Add password reset feature

