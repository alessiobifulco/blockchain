# Analysis of Cryptographic Primitives in Blockchain Technology

**Project for the Cryptography course**, focused on analyzing the cryptographic mechanisms and algorithms that ensure security, integrity, and non-repudiation in blockchain systems.

---

## Project Objective

The goal of this project is to analyze the cryptographic foundations that make blockchain possible.  
The study focuses on individual cryptographic components, their specific roles, and how their interaction creates a secure and reliable distributed system.

---

## Cryptographic Concepts Analyzed

The project explores the following pillars of blockchain cryptography:

- **Cryptographic Hash Functions (e.g., SHA-256):**  
  - Their role in ensuring data immutability is analyzed. Each block is linked to the previous one through a hash, creating a dependency that makes it extremely difficult to alter transaction history. Hashes are also used in the mining process (Proof-of-Work).  

- **Public-Key (Asymmetric) Cryptography:**  
  - The mechanism of key pairs (public and private) is studied as the basis for creating wallets. The public key serves as the address to receive funds, while the private key, kept secret, is the only one capable of authorizing transactions.  

- **Digital Signatures (e.g., ECDSA):**  
  - Explains how digital signatures authenticate transactions. The wallet owner signs a transaction with their private key, mathematically proving ownership of the funds without ever revealing the key.  

- **Merkle Trees:**  
  - Examines the hash-based tree data structure that summarizes all transactions in a block into a single "fingerprint" (Merkle Root). This allows efficient and secure verification of a transaction’s inclusion in a block.  

---

## Reference Technologies

- **Hash Algorithms:** SHA-256 (Bitcoin), Keccak-256 (Ethereum)  
- **Signature Algorithms:** ECDSA (Elliptic Curve Digital Signature Algorithm)  
- **Blockchain Platforms Analyzed:** Bitcoin, Ethereum  

---

## Contatti 

* Alessio Bifulco: `alessio.bifulco@studio.unibo.it`
