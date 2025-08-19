# BasicRansomWare
This is just a basic ransomware program written in python to encrypt all the files in the Victim's Computer and can be only decoded with a key ***THIS TOOL IS JUST EDUCATIONAL PURPOSE ONLY THE DEVELOPER IS NOT RESPONSIBLE FOR ANY ILLEGAL ACTIONS CAUSED BY ANY CONCERNED AUTHORITIES***

# CryptoEd: A Cybersecurity Encryption PoC

## Overview
CryptoEd is a Python-based proof-of-concept (PoC) project designed for **educational purposes only**. It demonstrates basic encryption and decryption techniques using AES and RSA algorithms to help students and cybersecurity enthusiasts understand how file encryption works. This project is inspired by real-world ransomware mechanisms but is strictly intended for learning and testing in controlled, consensual environments (e.g., virtual machines).

**⚠️ Disclaimer**: This project is for educational and academic purposes only. Do not use this code to harm systems, networks, or data. Unauthorized use of encryption to lock files or systems is illegal and unethical. The author is not responsible for any misuse. Always obtain explicit consent before testing on any system.

## Features
- **Hybrid Encryption**: Combines AES (symmetric) and RSA (asymmetric) encryption to demonstrate secure key exchange and file encryption.
- **File Encryption/Decryption**: Encrypts and decrypts files in a specified directory (for testing purposes).
- **Cross-Platform**: Supports Windows, Linux, and macOS.
- **Educational Focus**: Includes detailed comments and documentation to explain cryptographic concepts.
- **Safe Testing**: Includes a safe mode for simulation without modifying files.

## Requirements
- Python 3.7+
- Required libraries: `pycryptodome`, `argparse`, `os`
- Install dependencies:
  ```bash
  pip install -r requirements.txt
