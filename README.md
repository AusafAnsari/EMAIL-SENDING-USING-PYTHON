
# 📧 Email Sending Using Python

A simple Python script that automates the process of sending emails using **SMTP**. Ideal for sending automated notifications, password resets, newsletters, or any kind of message directly from your Python program.

---

## ✨ Features

- Send emails using your Gmail account  
- Supports plain text messages  
- Secure authentication using app-specific password  
- Clean and beginner-friendly code  

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x  
- Gmail account with **App Passwords** enabled (2FA must be on)  
- Enable "Less secure app access" if using a non-2FA account (not recommended)

### Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/AusafAnsari/EMAIL-SENDING-USING-PYTHON.git
cd EMAIL-SENDING-USING-PYTHON
```

2. **Install (optional) dependencies**

No external libraries required—uses Python’s built-in `smtplib` and `email`.

3. **Edit sender details**

Open the script file (e.g., `send_email.py`) and replace:

```python
sender_email = "your_email@gmail.com"
sender_password = "your_app_password"
receiver_email = "receiver@example.com"
```

4. **Run the script**

```bash
python send_email.py
```

---

## 🧠 How It Works

- Uses `smtplib` to connect to Gmail's SMTP server  
- Authenticates using your credentials  
- Constructs the email with subject and body using the `email` library  
- Sends the email to the recipient

---

## 🔐 Security Note

> ⚠️ **Do not hard-code your credentials in a public repo.**  
> Instead, use environment variables or a `.env` file (with `python-dotenv`) for better security.

---

## 📁 File Structure

```
EMAIL-SENDING-USING-PYTHON/
├── send_email.py           # Main script
└── README.md
```

---

## ✍️ Author

**Ausaf Ansari**  
[GitHub Profile](https://github.com/AusafAnsari)

---

## 📝 License

This project is licensed under the **MIT License**.


![image](https://github.com/user-attachments/assets/25bd606c-454e-4ea9-90e8-f0a22af8a9b6)

![image](https://github.com/user-attachments/assets/5e934f42-37f9-4624-bf27-35408fc8c4dd)
