# securedocs-project


# 🔐 SecureDocs – Secure Document Management System

SecureDocs is a cybersecurity-focused project designed to demonstrate secure system architecture, Risk Management Framework (RMF) implementation, and cloud-based document protection techniques.

This project simulates a real-world DoD-style system undergoing the Authority to Operate (ATO) process.

---

## 📌 Project Overview

SecureDocs allows authenticated users to securely upload, store, and retrieve documents while enforcing strong security controls such as:

- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Encryption (data at rest and in transit)
- Malware scanning
- Audit logging and monitoring

---

## 🏗️ Architecture

The system is built using a secure cloud architecture model.

### Key Components:
- User Interface (Web Application)
- Identity Provider (Azure AD / IAM)
- Application Server
- Malware Scanning Engine
- Secure Storage (AWS S3 / Azure Blob)
- Logging & Monitoring System

---

## 🔄 Data Flow Summary

1. User authenticates via secure login (MFA enforced)
2. Identity provider validates credentials
3. User uploads document
4. File is scanned for malware
5. File is encrypted
6. Stored securely in cloud storage
7. Metadata stored in database
8. All actions logged for auditing

---

## 📁 Repository Structure

- **docs/** → System documentation and security plans  
- **diagrams/** → Architecture and data flow diagrams  
- **inventory/** → Hardware and software inventory  
- **rmf-artifacts/** → SSP, SAR, POA&M, control selection  
- **screenshots/** → Visual evidence of system workflows  
- **notes/** → Supporting project notes  

---

## 🛠️ Technologies Used

- Microsoft Azure / AWS
- RMF (NIST SP 800-37)
- NIST SP 800-53 Security Controls
- ACAS / Vulnerability Scanning Concepts
- Draw.io (Architecture Diagrams)
- Microsoft Word & Excel

---

## 🔐 Security Focus Areas

- Risk Management Framework (RMF)
- System Security Plan (SSP)
- Security Assessment Report (SAR)
- Plan of Action & Milestones (POA&M)
- STIG Implementation Concepts
- Vulnerability Management

---

## 🎯 Purpose of This Project

This project was developed to demonstrate hands-on experience in:

- Designing secure systems
- Implementing RMF processes
- Preparing ATO documentation
- Applying cybersecurity best practices in cloud environments

---

## 📫 Contact

- LinkedIn: www.linkedin.com/in/forson-kofi-amponsah-07743a1a4
- Email: kforoson1290@gmail.com
