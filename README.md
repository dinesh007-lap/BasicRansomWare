# 🔐 Noob Ransomware Simulation (Educational Only)

This is a **simple ransomware simulation** built in Python using the `cryptography` library (Fernet).  
⚠️ **Disclaimer:** This project is for **educational purposes only**. Do not use it for malicious activities. I take no responsibility for any misuse.  

---

## 📂 Project Structure

- `Noob.py` → Encryption script  
- `NoobDecrypt.py` → Decryption script  
- `thekey.key` → Encryption key (generated automatically)  

---

## 🚀 How It Works
1. The encryption script (`Noob.py`):
   - Generates a Fernet key (`thekey.key`)
   - Encrypts all files in the directory (except the scripts and key file)

2. The decryption script (`NoobDecrypt.py`):
   - Reads `thekey.key`
   - Decrypts all files in the directory

---

## 🛠️ Requirements
- Python 3.x  
- `cryptography` library  

Install the library:  
```bash
pip install cryptography
