# Cybersecurity Training App

## Overview
This application is designed to help users improve their cybersecurity awareness by:
- Allowing users to check the strength of their passwords.
- Educating users on the most effective authentication methods.

## Features

1. **Password Strength Checker**
    - Users can input a password to receive feedback on its strength.
    - The app provides suggestions for creating stronger passwords.
    - Visual indicators (e.g., weak, medium, strong) help users understand password quality.

2. **Authentication Methods Education**
    - Interactive guides and articles on authentication best practices.
    - Comparison of authentication methods (e.g., passwords, two-factor authentication, biometrics).
    - Tips for securing accounts and avoiding common pitfalls.

## App Structure

```
cybersecurity-training/
│
├── README.md
├── password_checker/           # Module for password strength checking
│   ├── __init__.py
│   ├── checker.py              # Logic for evaluating password strength
│   └── utils.py                # Helper functions
│
├── auth_education/             # Module for authentication education
│   ├── __init__.py
│   ├── guides.md               # Educational content
│   └── comparison.py           # Logic for comparing authentication methods
│
├── app.py                      # Main application entry point
├── requirements.txt            # Dependencies
│
# Web Page
│
├── index.html                 # Main landing page for the app
├── styles/                    # Directory for CSS files
│   └── main.css               # Styling for the web page
├── scripts/                   # Directory for JavaScript files
│   └── app.js                 # Logic for interactive elements
```

## Getting Started

1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Run `app.py` to start the application.

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License.