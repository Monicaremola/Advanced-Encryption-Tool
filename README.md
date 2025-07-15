# Advanced-Encryption-Tool

COMPANY: CODTECH IT SOLUTIONS

NAME: MONICA REMOLA.K

INTERN ID:CT06DF1639

DOMAIN:FRONT END DEVELOPMENT

DURATION:6 WEEKS

MENTOR:NEELA SANTOSH

# Advanced Encryption Tool

## Overview

The Advanced Encryption Tool is a robust Python application designed to securely encrypt and decrypt files using the AES-256 encryption standard. This tool is ideal for anyone who needs to protect sensitive data, such as students, professionals, and security enthusiasts. The application features a user-friendly command-line interface and leverages the powerful `cryptography` library to ensure strong security.

## Features

- **AES-256 Encryption:** Utilizes industry-standard AES-256 for strong file encryption and decryption.
- **Password-Based Security:** Files are encrypted and decrypted using a password provided by the user.
- **Simple Command-Line Interface:** Easy-to-use prompts guide the user through encryption and decryption operations.
- **Cross-Platform:** Works on Windows, macOS, and Linux.

## Setup Instructions

1. **Prerequisites:**
   - Python 3.x installed on your system.

2. **Install Required Library:**
   Open your terminal and run:
   ```
   pip install cryptography
   ```

3. **Download the Script:**
   - Save `encryption_tool.py` in your project directory.

## Usage Guide

1. Open a terminal and navigate to the directory containing `encryption_tool.py`.
2. Run the script:
   ```
   python encryption_tool.py
   ```
3. Follow the prompts:
   - Choose to encrypt or decrypt a file by entering `1` or `2`.
   - Enter the file path (e.g., `test.txt` for encryption or `test.txt.enc` for decryption).
   - Enter your password.
4. The script will create a new encrypted or decrypted file in the same directory.

## Example Output

**Encrypting a File:**
```
Advanced Encryption Tool (AES-256)
1. Encrypt a file
2. Decrypt a file
Choose an option (1/2): 1
Enter the file path: test.txt
Enter password: mysecretpassword
File encrypted and saved as test.txt.enc
```

**Decrypting a File:**
```
Advanced Encryption Tool (AES-256)
1. Encrypt a file
2. Decrypt a file
Choose an option (1/2): 2
Enter the file path: test.txt.enc
Enter password: mysecretpassword
File decrypted and saved as test.txt.dec
```

## Technical Details

- **Language:** Python 3
- **Encryption Library:** `cryptography` (Fernet/AES-256)
- **Key Derivation:** Passwords are converted to 32-byte keys using SHA-256 and base64 encoding.
- **File Handling:** Encrypted files are saved with a `.enc` extension; decrypted files with a `.dec` extension.

## Notes

- Use strong, unique passwords for best security.
- Do not lose your password; encrypted files cannot be decrypted without it.
- Only use this tool for files you have permission to encrypt/decrypt.


