# Secure File Transfer System (Python, RSA, SHA-512)

## Project Overview

This project demonstrates the implementation of a secure client-server file transfer system 
using Python socket programming and cryptographic techniques.

The system ensures:

- Confidentiality using RSA encryption
- Integrity using SHA-512 hashing
- Authentication via public/private key exchange
- Encrypted communication verified through packet analysis

## Technologies Used

- Python
- RSA (Asymmetric Encryption)
- SHA-512 (Hashing)
- Socket Programming
- Wireshark (Traffic Verification)

## Security Features

- Public/private key generation
- File encryption before transmission
- Hash verification after reception
- Packet capture validation of encrypted payload

## Future Improvements

- Implement TLS encryption
- Add authentication tokens
- Improve key management security
