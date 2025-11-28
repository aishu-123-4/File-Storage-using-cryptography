# 🔐 Secure File Storage Using Hybrid Cryptography  
### AES · RSA · ECC · Steganography · Split Encryption
This project implements a **secure cloud file-storage system** using a hybrid cryptography pipeline that combines multiple encryption algorithms for enhanced privacy and integrity.
It secures uploaded files by **splitting, encrypting, hiding keys, and reassembling** them using a multi-layered approach.

## 🚀 Features
- 🔸 Hybrid Cryptography (AES + RSA + ECC)  
- 🔸 File Split-Encrypt-Merge Pipeline  
- 🔸 Steganography-based Key Storage (LSB method)  
- 🔸 User-specific encrypted keys  
- 🔸 Secure upload & download lifecycle  
- 🔸 Protection against brute-force & metadata exposure  

## 🛠 Tech Stack
- Python / Java (depending on your implementation)
- AES, RSA, ECC libraries  
- Steganography (LSB)  
- Cloud storage / Local server  

## ▶️ How to Run
1. Register user (generates encrypted keys in stego-image).  
2. Upload file → system splits & encrypts.  
3. Download file → decrypts & reassembles.  

## 🧩 Future Enhancements
- Add integrity verification using SHA-256 checks  
- Add UI dashboard  
- Implement multi-cloud redundancy (GCP + AWS)  
