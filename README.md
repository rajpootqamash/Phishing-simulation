# Phishing-simulation
# 🎯 Phishing Simulation Project using GoPhish

This project demonstrates how to perform a phishing simulation using [GoPhish](https://getgophish.com/) — an open-source phishing toolkit — to train users in identifying phishing emails and raise cybersecurity awareness.

---

## 📌 Project Objective

To simulate a realistic phishing attack in a controlled lab environment, analyze results, and improve organizational or personal awareness of social engineering threats.

---

## 🧰 Tools & Technologies Used

- ✅ GoPhish (v0.11.0)
- ✅ Ubuntu (20.04 or later)
- ✅ Gmail SMTP for email delivery
- ✅ HTML for phishing templates
- ✅ JSON configuration
- ✅ Local network or VM for hosting

---

## 🧪 Features

- 📬 Custom phishing email templates (Microsoft-style)
- 🌐 Landing page to capture submitted credentials
- 📊 Campaign tracking and reporting via GoPhish dashboard
- 🔐 Gmail SMTP integration with app password
- 💻 Hosted in a Linux virtual machine (Ubuntu)

---

## 🚀 Setup Instructions

1. **Install GoPhish on Ubuntu**
   ```bash
   wget https://github.com/gophish/gophish/releases/download/v0.11.0/gophish-v0.11.0-linux-64bit.zip
   unzip gophish-v0.11.0-linux-64bit.zip
   cd gophish
   sudo ./gophish
