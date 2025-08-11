# 🚀 Jenkins Installation Script (Ubuntu/Debian)

This repository contains a simple shell script to **install Jenkins (LTS)** on Ubuntu/Debian-based systems.  
It automatically installs Java, adds the Jenkins repository, installs Jenkins, and starts the service.

---

## 📋 Features
- Installs **OpenJDK 17** (required for Jenkins)
- Adds the **official Jenkins LTS repository**
- Installs and configures Jenkins as a systemd service
- Displays the **initial admin password** after installation

---

## 🛠️ Prerequisites
- Ubuntu/Debian-based system
- `sudo` privileges
- Internet connection

---

## 📥 Installation Steps

### 1️⃣ Clone this repository
```bash
git clone https://github.com/<your-username>/jenkins-install-script.git
cd jenkins-install-script
