# 🔐 Python Login System with OTP Verification (Twilio)

This project is a simple **Python-based login system** that combines **password authentication** and **OTP (One-Time Password)** verification using the **Twilio SMS API**.  
It demonstrates secure user login with limited password attempts and SMS-based OTP validation for enhanced security.

---

## 🧩 Features

- ✅ Password authentication with a limited number of attempts  
- 🔁 Automatic OTP generation (6-digit random number)  
- 📱 OTP sent to user's mobile via Twilio SMS API  
- 🚫 Locks user after 5 failed password attempts  
- 💬 Clear console messages for user guidance  
- 🧠 Error handling for network or user input issues  

---

## ⚙️ Requirements

Make sure you have the following installed:

- Python 3.x  
- [Twilio](https://www.twilio.com/) account (for sending SMS)  
- Twilio Python library


```bash
pip install twilio
