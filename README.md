# DienLex

DienLex is an indexd-native file sharing and verification tool built on the Sia network.

It allows users to upload files that are encrypted in the browser, stored via indexd, and later verified using a cryptographic integrity receipt (SHA-256 hash).

The goal is simple:  
**make file sharing verifiable without trusting a central platform.**

---

## Why we are building this

Most modern file sharing systems require users to trust a central provider with their data. Once uploaded, there is no simple way to prove a file has not been modified.

We built DienLex to explore a different model using Sia + indexd, where integrity and ownership are enforced cryptographically instead of through trust.

---

## What DienLex does

- Encrypts files locally in the browser before upload
- Generates a SHA-256 hash as an integrity receipt
- Uploads encrypted files to Sia via indexd
- Allows anyone with a link to verify file integrity independently

No account is required to verify a file.

---

## Project structure

---

## Tech stack (planned)

- React + TypeScript
- Node.js (middleware)
- WebCrypto API (client-side encryption)
- Sia indexd (storage layer)

---

## Status

This project is in early setup phase.

DienLex will serve as a reference implementation for indexd-based encrypted file sharing workflows on the Sia network.

---

## Team

Built by:

- Code Duchess — full-stack developer (React, Node.js, client-side cryptography), contributor to SiaPeopleLearn and SiaLearn via Dapp Mentors
- Gifetea — developer and technical writer focused on smart contracts, Web3 tooling, and blockchain application development

---

## License

MIT