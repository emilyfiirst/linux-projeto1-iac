# 🧩 User, Group, and Directory Creation Script

## 📄 Description
This script automates the creation of **directories**, **user groups**, **users**, and the **configuration of permissions** on Linux systems.

## ⚙️ What the Script Does
1. Creates the following directories:
/publico  
/adm  
/ven  
/sec  

2. Creates the following groups:  
GRP_ADM  
GRP_VEN  
GRP_SEC  

3. Creates users and assigns them to their respective groups.  
Default password: `123`

4. Sets permissions:
- Group directories: full access only for group members (`770`)  
- Public directory: full access for all users (`777`)  

## 💻 How to Use
```bash
chmod +x criar_usuarios.sh
sudo ./criar_usuarios.sh
