# 🔐 SSH Password Testing Tool

> A Python-based SSH authentication testing script built using **Pwntools** and **Paramiko** for learning cybersecurity concepts and authorized security assessments.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Pentesting-red)
![License](https://img.shields.io/badge/License-Educational-green)

---

## 🚀 What is this?

This project demonstrates how automated SSH authentication testing works in real-world penetration testing environments.

The script:

✅ Reads passwords from a wordlist
✅ Attempts SSH authentication automatically
✅ Detects valid credentials
✅ Displays failed and successful attempts
✅ Stops when the correct password is found

---

## 🎯 Learning Objectives

This project helps beginners understand:

* SSH Authentication
* Password-Based Attacks
* Python Automation
* Error Handling
* Network Security Concepts
* Ethical Hacking Fundamentals

---

## 🛠 Technologies Used

* Python 3
* Pwntools
* Paramiko

---

## 📂 Project Structure

```text
.
├── ssh-brute.py
├── ssh-common-passwords.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/ssh-password-testing-tool.git
cd ssh-password-testing-tool
```

### Install Dependencies

```bash
pip install pwntools paramiko
```

---

## 🔧 Configuration

Modify the target settings in `ssh-brute.py`:

```python
host = "127.0.0.1"
username = "sathwik"
```

Update these values according to your lab environment.

---

## ▶️ Usage

Run the script:

```bash
python3 ssh-brute.py
```

### Sample Output

```text
[0] Attempting password: 'admin'
[x] Invalid password

[1] Attempting password: 'password123'
[x] Invalid password

[2] Attempting password: 'letmein'
[>] Valid password found: 'letmein'
```

---

## 🧠 How It Works

1. Loads passwords from a wordlist.
2. Connects to the SSH service.
3. Tests credentials one by one.
4. Detects successful authentication.
5. Terminates after finding valid credentials.

---

## 📚 Skills Demonstrated

* Python Scripting
* Cybersecurity Automation
* SSH Protocol Understanding
* Network Communication
* Security Testing Methodologies

---

## ⚠️ Disclaimer

This project is intended **only for educational purposes and authorized security testing**.

Do **NOT** use this tool against systems, networks, or accounts without explicit permission.

The author assumes no responsibility for misuse or illegal activities.

---

## 🌟 Support

If you found this project useful:

⭐ Star the repository

🍴 Fork the repository

🛡️ Share it with fellow cybersecurity enthusiasts

---
