# AES-GCM-Ransomware-Simulation

AES-GCM File Encryption & Decryption Simulation

This project implements a ransomware-style encryption and decryption system using the AES-GCM (Advanced Encryption Standard – Galois/Counter Mode) algorithm. The system demonstrates how modern cryptographic techniques can be used to secure sensitive files by encrypting entire folders and later restoring them through decryption.

🔑 Key Features

AES-256-GCM Encryption

Uses a 256-bit symmetric key for encryption.

Galois/Counter Mode (GCM) ensures both confidentiality and integrity.

Each file is encrypted with a unique random nonce, making ciphertexts secure even if the same file is encrypted multiple times.

Graphical User Interface (GUI)

Built using Python’s tkinter library.

Allows users to select folders for encryption and decryption.

Provides interactive buttons for “Encrypt Folder” and “Decrypt Folder.”

Progress Visualization

A progress bar displays real-time encryption/decryption activity.

A terminal-like log panel shows step-by-step updates, simulating the behavior of ransomware.

File Handling Simulation

Original files are encrypted, converted into .encrypted format, and moved into a simulated “server” folder.

Decryption restores the files from the server folder back into a user-selected directory.

🔐 Why AES-GCM?

Security: AES is a U.S. government standard and widely used for protecting classified information.

Authenticated Encryption: GCM mode combines encryption with authentication, ensuring files cannot be altered without detection.

Performance: AES-GCM is optimized for modern hardware, offering strong security with high speed.

📌 Applications

Demonstrates how ransomware attacks encrypt victim files.

Educational tool for learning about modern encryption techniques.

Can be adapted for secure file storage or backup systems.

⚡ Conclusion

This project moves beyond the basic Fernet encryption by implementing AES-256-GCM, a more advanced and secure encryption technique. It simulates real-world ransomware behavior, showing both the risks of malicious encryption and the importance of strong cryptographic practices for cybersecurity.
