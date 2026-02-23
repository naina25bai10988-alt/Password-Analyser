# Overview
Password Security Analyzer helps users evaluate the strength of their passwords in real-time. It checks multiple security factors such as length, character variety, common patterns, and estimated resistance to brute-force attacks. It also provides recommendations and generates strong passwords.
This project was developed as part of the Cyber Warrior Club Security Tool initiative.

# Password Strength Analysis
Real-time password evaluation
Strength score (0–100%)
Strength levels: Weak, Medium, Strong
Visual strength meter

# Security Checks
Minimum length validation
Uppercase and lowercase letters detection
Numbers and special characters detection
Detection of common passwords
Detection of sequential characters (abc, 123)
Detection of repeating characters

# Crack Time Estimation
Estimates how long it would take to crack the password
Based on password complexity and character set

# Recommendations
Provides suggestions to improve weak passwords
Displays security best practices

# Password Generator
Generate strong random passwords
Customizable options:
Uppercase letters
Lowercase letters
Numbers
Special characters
Adjustable length (8–32 characters)

# Copy to Clipboard
Click generated passwords to copy instantly

# Technologies Used
HTML5
CSS3 (Modern UI with animations)
JavaScript (Vanilla JS)
Google Fonts (JetBrains Mono, Syne)

# Project Structure
password-security-analyzer/
│
├── index.html        # Main application file
├── README.md        # Project documentation
▶️ How to Run
Method 1: Open Directly

Download the project

Open index.html in your browser

Method 2: Using Local Server (Recommended)
Live Server (VS Code Extension)

or

python -m http.server

Then open:

http://localhost:8000
# How It Works

The analyzer evaluates passwords based on:

Factor	Points
Length	up to 40
Character Variety	up to 40
Security Checks	up to 20

Total Score = 100

Strength classification:

0–39 → Weak

40–69 → Medium

70–100 → Strong

# Security Best Practices (Included in Tool)

Use 12–16+ characters

Mix letters, numbers, and symbols

Avoid personal information

Use unique passwords
Enable 2FA

Use password managers

# Purpose

This tool is designed for:
Cybersecurity awareness
Educational purposes
Hackathons
Student cybersecurity projects
Personal password security testing

# Author
Naina Jain
Rakshita Ranjan
Srishti Rai
Aditi Sharma
Developed for cybersecurity learning and awareness.

# License

This project is open-source and free to use for educational purposes.

# Future Improvements

Dark/Light mode toggle
Password breach detection API integration
Export password report
Strength analytics dashboard
