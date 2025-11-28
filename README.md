🔐 Cryptography Mini Project
Blowfish & Twofish Encryption Algorithms (Python)

This mini-project demonstrates the implementation of Blowfish and Twofish symmetric-key encryption algorithms using Python.
It is designed for learning, experimentation, and performance comparison between the two algorithms.

📌 Project Overview

This repository contains Python implementations of:

Blowfish Encryption

Twofish Encryption

Performance Graph / Comparison Script

These algorithms are widely used in secure systems and provide a foundation for understanding modern cryptographic techniques.

📂 Repository Structure
/cryptography
│
├── BlowFish.py      # Blowfish encryption implementation
├── TwoFish.py       # Twofish encryption implementation
└── graph.py         # Script for comparing performance (optional)

⚙️ Features

✔ Encrypt and decrypt text using Blowfish
✔ Encrypt and decrypt text using Twofish
✔ Understand key scheduling, block ciphers, and rounds
✔ Compare performance or output using graphs (via graph.py)
✔ Simple Python-based implementation for beginners

🧩 Requirements

Make sure Python is installed (≥ 3.7).

Install required libraries:

pip install pycryptodome matplotlib

🚀 How to Use
1️⃣ Blowfish Encryption

Example usage (inside your own script or Python shell):

from BlowFish import *

key = b"mysecretkey"
plaintext = "Hello World"

encrypted = blowfish_encrypt(plaintext, key)
decrypted = blowfish_decrypt(encrypted, key)

print("Encrypted:", encrypted)
print("Decrypted:", decrypted)

2️⃣ Twofish Encryption
from TwoFish import *

key = b"mysecretkey1234"
plaintext = "Welcome to Cryptography"

encrypted = twofish_encrypt(plaintext, key)
decrypted = twofish_decrypt(encrypted, key)

print("Encrypted:", encrypted)
print("Decrypted:", decrypted)

3️⃣ Graph / Comparison

If graph.py is used to compare Blowfish & Twofish:

python graph.py


It may generate:

Execution time comparison

Block processing comparison

(Modify graph.py as needed.)

📘 Theory (Short Explanation)
🔹 Blowfish

Developed by Bruce Schneier

64-bit block cipher

Key size: 32–448 bits

Fast and secure for many applications

🔹 Twofish

Successor to Blowfish

128-bit block cipher

Key size: 128/192/256 bits

One of the finalists of AES competition

📝 Notes

This project is for learning purposes only — not for production-level cryptography.

For real security applications, always use industry-standard libraries like PyCryptodome, OpenSSL, etc.

👨‍💻 Author

Akash H
Mini-Project: Blowfish vs Twofish Cryptography
Department of Information Science
Sai Vidya Institute of Technology

⭐ Contributions

Feel free to fork, contribute, improve documentation, or optimize algorithms.
