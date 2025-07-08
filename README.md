Decentralized File Sharing System Using Blockchain and IPFS

This repository contains the project titled “Design and Implementation of a Decentralized File Sharing System Using Blockchain and InterPlanetary File System (IPFS),” developed as part of the B.Tech curriculum at Amrita Vishwa Vidyapeetham, Bengaluru.

Project Overview

The rapid growth of digital communication and data exchange has highlighted the need for secure, decentralized, and tamper-proof file-sharing systems. This project proposes “Data Share,” a decentralized system for secure file sharing that integrates Blockchain, IPFS, and Advanced Encryption Standard (AES) encryption.

Key Technologies

- Blockchain: Provides an immutable ledger for storing file hashes and metadata, ensuring data integrity and auditability without reliance on centralized authorities.
- IPFS: A distributed file system enabling efficient, content-addressable storage and retrieval of files, reducing load on the blockchain.
- AES Encryption: Ensures data confidentiality by encrypting file contents before upload, guaranteeing that only authorized users can access sensitive information.

System Features

- Secure file uploads with AES-256 encryption.
- Decentralized storage via IPFS.
- Blockchain-based recording of file metadata, including content identifiers (CIDs), timestamps, and uploader identity.
- Smart contracts for access control, ensuring that only authorized users can retrieve files.
- Auditability and traceability of file-sharing activities through blockchain records.

Architecture and Workflow

1. A user selects a file via the client interface.
2. The file is encrypted locally using AES.
3. The encrypted file is uploaded to IPFS, generating a unique Content Identifier (CID).
4. The CID and metadata are recorded on the blockchain via smart contracts.
5. Authorized users can retrieve the CID, download the encrypted file from IPFS, and decrypt it locally.

Performance Evaluation

The system demonstrated effective performance for small to medium file sizes. Average time measurements for a 5 MB file are as follows:

- AES Encryption: ~1.5 seconds
- IPFS Upload: 2–3 seconds
- Blockchain Write: 12–15 seconds
- File Retrieval and Decryption: 4–6 seconds

Security Highlights

- Data Integrity: Content-based addressing in IPFS ensures tamper detection.
- Confidentiality: AES encryption safeguards file contents.
- Immutability: Blockchain prevents unauthorized modification of stored metadata.
- Auditability: Transparent tracking of file transactions.

Limitations and Future Scope

Current limitations include performance overhead for large files and the lack of folder-level uploads. Future enhancements may focus on:

- Integration with advanced access control mechanisms like Attribute-Based Encryption (ABE).
- Optimization of encryption and hashing processes for large file support.
- Deployment on public blockchain networks for broader scalability.
- Integration with IoT and edge computing use cases.
- Research into quantum-resistant cryptographic algorithms for future security needs.


Usage Instructions

- Download the file `DS.zip` from this repository.
- Extract the contents on your local machine.
- Follow instructions inside the extracted folder for building, running, and testing the application.


