@"

# 🔒 Advanced Encryption for Secure Cloud Storage

> End-to-end encrypted file storage system with AES-256-GCM encryption and AWS S3 integration

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![React](https://img.shields.io/badge/React-18-blue.svg)](https://reactjs.org/)
[![Flask](https://img.shields.io/badge/Flask-2.3-green.svg)](https://flask.palletsprojects.com/)
[![AWS](https://img.shields.io/badge/AWS-S3-orange.svg)](https://aws.amazon.com/s3/)

## 🎯 Project Overview

A secure cloud storage system that implements advanced encryption methods to protect files stored in the cloud. Only authorized users can access files through encrypted upload/download interfaces with integrated encryption logic and user validation.

### Key Features

- 🔐 **AES-256-GCM Encryption**: Military-grade encryption for all files
- 🔑 **RSA Key Pairs**: Public/private key authentication
- ☁️ **AWS S3 Integration**: Secure cloud storage backend
- 🛡️ **JWT Authentication**: Secure user sessions
- 📤 **Encrypted Upload/Download**: End-to-end encryption
- 🎨 **Modern UI**: React-based responsive interface
- 📊 **File Management**: List, download, and delete encrypted files



## 🔐 Encryption Details

### File Encryption Process

1. **Key Generation**: Random AES-256 key generated per file
2. **Nonce Creation**: 16-byte random nonce for GCM mode
3. **Encryption**: File encrypted using AES-256-GCM
4. **Authentication Tag**: 16-byte tag for integrity verification
5. **Storage**: Encrypted file + metadata stored in S3

### Security Features

- ✅ AES-256-GCM encryption (NIST approved)
- ✅ Unique encryption key per file
- ✅ Authentication tags prevent tampering
- ✅ JWT tokens for session management
- ✅ Server-side encryption in S3 (AES-256)
- ✅ HTTPS/TLS for data in transit
- ✅ No plaintext storage anywhere

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file.

## 👤 Author

**Devika Kasthala**

- GitHub: [@DEVIKAKASTHALA](https://github.com/DEVIKAKASTHALA)
- Project: Advanced Encryption for Secure Cloud Storage
- Institution: Vel Tech Dr. Sagunthaala (R&D Institute of Science and Technology)

## 🙏 Acknowledgments

Vel Tech Dr. Sagunthaala (R&D Institute of Science and Technology)
- AWS Documentation
- PyCryptodome Library

