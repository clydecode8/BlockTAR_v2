# BlockTAR - Decentralized Academic Credential Verification System

BlockTAR is a decentralized academic credential verification platform that uses Self-Sovereign Identity (SSI) principles to help institutions issue digital academic credentials and allow employers to verify them securely.

The system reduces reliance on manual transcript verification by providing a DID-based credential workflow where students control their credentials and employers can verify authenticity through decentralized identity infrastructure.

---

## 🚀 Features

### 🎓 Digital Credential Issuance

Institutions can issue academic credentials digitally through an administrator portal.

Features include:

- Student identity registration
- Academic transcript upload
- DID-based credential creation
- Credential status management
- Credential revocation support

---

### 🆔 Self-Sovereign Identity (SSI)

Implemented decentralized identity concepts using Hyperledger-based identity infrastructure.

SSI workflow:

1. Institution creates credential records
2. Student receives decentralized identity credentials
3. Credential metadata is linked through DID
4. Employer verifies credential authenticity

Benefits:

- Student-controlled credentials
- Reduced dependency on centralized verification
- Improved trust between issuers and verifiers

---

### 🌐 VON Network Integration

The system uses VON Network as the decentralized identity ledger environment.

Used for:

- DID registration
- Schema management
- Credential definition support
- Verifiable credential workflows

This provides a development environment for Hyperledger Indy-based SSI solutions.

---

### 📁 Decentralized File Storage

Academic transcript files are stored using IPFS.

Workflow:

1. Institution uploads transcript
2. File is stored through IPFS
3. IPFS content identifier is linked with credential metadata
4. Verification retrieves the associated academic record

Benefits:

- Content-addressed storage
- Tamper-resistant document references
- Reduced centralized file dependency

---

### 🔍 Employer Verification Portal

Employers can verify submitted credentials through a dedicated verification interface.

Verification supports:

- Credential lookup
- Transcript authenticity checking
- Credential status validation
- Revocation checking

---

### 📊 Credential Analytics Dashboard

Provides institution insights including:

- Number of issued credentials
- Verification activity
- Registered users
- Credential statistics

---

## 🛠️ Tech Stack

### Frontend

- React.js
- JavaScript
- HTML/CSS
- Chart.js

---

### Backend

- Node.js
- Express.js
- MongoDB

---

### Decentralized Identity

- Hyperledger Indy
- VON Network
- DID (Decentralized Identifier)
- Verifiable Credentials

---

### Storage

- IPFS
- Pinata

---

## 🔐 Security Concepts

BlockTAR focuses on improving academic credential trust through:

- Decentralized identity verification
- DID-based ownership
- Credential revocation mechanisms
- Tamper-resistant document references
- Separation between identity data and document storage

---

## ⚙️ Environment Variables

Example environment configuration:

```env
MONGODB_URI=

PINATA_API_KEY=
PINATA_SECRET_KEY=

VON_NETWORK_URL=

JWT_SECRET=
```

---

## ▶️ Running Locally

Clone repository:

```bash
git clone https://github.com/clydecode8/BlockTAR_v2.git

cd BlockTAR_v2
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm start
cd von-network
./manage.py
```

---

## 🔮 Future Improvements

Potential enhancements:

- Mobile SSI wallet integration
- QR-based credential sharing
- Multi-institution support
- Advanced verifier dashboard
- Credential expiration management
- Production DID network deployment

---

## Project Goals

This project explores modern digital identity concepts:

- Self-Sovereign Identity (SSI)
- Decentralized Identifiers
- Verifiable Credentials
- Trust-based credential exchange
- Decentralized storage integration

The goal is to demonstrate how decentralized identity technologies can improve academic record verification and reduce credential fraud.

---

## Author

Developed by Clyde Kok
