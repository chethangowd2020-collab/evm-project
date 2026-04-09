# Class Representative Voting System (Smart EVM)

A full-stack web application for electing class representatives.

## Setup

```bash
pip install flask
python app.py
```

Open: http://localhost:5000

## Admin Login
- USN: ADMIN
- Password: admin123

## Student Flow
1. Register at /register (generate OTP for demo, it's displayed on screen)
2. Login at /login
3. Optionally enroll as candidate at /candidate_register
4. Vote at /vote (after admin starts voting)

## Project Structure
```
evm_project/
├── app.py              # Flask backend
├── database.db         # Auto-created SQLite DB
├── requirements.txt
├── templates/
│   ├── register.html
│   ├── login.html
│   ├── dashboard.html
│   ├── vote.html
│   ├── candidate_register.html
│   ├── admin.html
│   └── results.html    (admin only)
└── static/
    ├── style.css
    └── script.js
```
