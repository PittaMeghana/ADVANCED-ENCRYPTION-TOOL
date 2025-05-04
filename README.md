COMPANY: CODTECH IT SOLUTIONS

NAME: PITTA MEGHANA

INTERN ID: CT12MLF

DOMAIN: CYBER SECURITY AND ETHICAL HACKING

BATCH DURATION: FEBRUARY 5th, 2025 to MAY 5th, 2025

MENTOR NAME: NEELA SANTHOSH KUMAR

COMPANY: CODTECH IT SOLUTIONS

 🔐 AES - Advanced Encryption Tool

  A robust command-line utility to securely **encrypt and decrypt** files using modern encryption standards such as **AES-256**. Designed for developers, cybersecurity enthusiasts, and anyone looking to safeguard sensitive data with strong encryption.

📖 About

  The **Advanced Encryption Tool** allows users to securely encrypt and decrypt files using a symmetric key approach. It employs **AES (Advanced Encryption Standard)** in **CBC mode** with a randomly generated initialization vector (IV) for maximum security.
  
✨ Features

  - 🔒 AES-256 Encryption and Decryption
  - 📁 File-level security
  - 🔑 Password-based key derivation using PBKDF2
  - 📦 CLI support using `argparse`
  - 📜 Minimal and modular codebase
  - 🛡 Prevents brute-force via salt and key stretching

 🧰 Technologies Used

  - Python 3.x
  - [cryptography](https://cryptography.io/en/latest/) library
  - argparse
  - os / sys / base64 modules

🚀 Getting Started

  🔧 Prerequisites

  Install the cryptography library:
  
  ```bash
  pip install cryptography
  ````

 ⬇️ Clone the Repository

    ```bash
    git clone https://github.com/your-username/advanced-encryption-tool.git
    cd advanced-encryption-tool
    ```

⚙️ Usage

   🔐 Encrypt a File

    ```bash
    python encryptor.py --encrypt myfile.txt
    ```
    
    You will be prompted to enter a password. The encrypted file will be saved as `myfile.txt.enc`.

   🔓 Decrypt a File

    ```bash
    python encryptor.py --decrypt myfile.txt.enc
    ```
    
    Enter the same password used during encryption. The decrypted file will be saved as `myfile.txt.dec`.


