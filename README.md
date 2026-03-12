# cs178-lab12

Starter repository for CS 178 Lab 12: Flask Part I.

## Structure

```
cs178-lab12/
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Actions auto-deploy to EC2
├── templates/
│   ├── home.html            # Home page template
│   └── hello.html           # Hello page template (Exercise 4)
├── flaskapp.py              # Main Flask app — add your routes here
└── README.md
```

## Setup

See the Lab 12 instructions on HackMD for full setup steps including:
- Opening port 8080 in your EC2 security group
- Adding GitHub Actions secrets (`EC2_HOST`, `EC2_USER`, `EC2_PRIVATE_KEY`)
- Installing Flask on EC2
- Starting the server

## Running locally (optional)

```bash
pip install flask
python3 flaskapp.py
```

Then visit `http://localhost:8080` in your browser.
