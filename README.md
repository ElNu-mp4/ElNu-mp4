<div align="center">

# ElNu-mp4
**Informatics Student · Aspiring Network & Cybersecurity Engineer · Full-Stack Developer**

[![GitHub](https://img.shields.io/badge/GitHub-ElNu--mp4-181717?logo=github)](https://github.com/ElNu-mp4)
[![University](https://img.shields.io/badge/Universitas_Diponegoro-Informatics-0052CC)](https://undip.ac.id)
[![Location](https://img.shields.io/badge/Semarang-Indonesia-red)]()

</div>

---

## About Me

Motivated Informatics undergraduate at Universitas Diponegoro with hands-on experience in full-stack web development and a strong interest in networking and cybersecurity. I've shipped real projects across PHP/Laravel/CodeIgniter, built and deployed a Soroban smart contract on Stellar testnet, and developed security tooling for Office document metadata forensics. Proven leadership through coordinator roles in large-scale campus events and student organizations.

- Certification path: **eJPT → eCPPT → OSCP** — actively practicing on Hack The Box
- Interested in home lab engineering (WireGuard VPN, Pi-hole, honeypot, network segmentation) and actively planning a personal setup
- Reach me via GitHub or LinkedIn

---

## Tech Stack

**Languages**
`Python` `PHP` `JavaScript` `Java` `HTML/CSS` `SQL` `Rust`

**Frameworks & Platforms**
`Laravel` `CodeIgniter` `Tailwind CSS` `Chart.js` `Soroban SDK`

**Tools & Infra**
`Git` `MySQL` `KVM/Virt-Manager` `Kali Linux` `Hack The Box`

**Interests**
`Cybersecurity` `Network Engineering` `Penetration Testing` `MITRE ATT&CK` `System Information Development`

---

## Featured Projects

### [lstm-hids](https://github.com/ElNu-mp4/lstm-hids)
> TensorFlow replication of LSTM-based Host Intrusion Detection System

Replication of *"LSTM-Based System-Call Language Modeling and Robust Ensemble Method for Designing Host-Based Intrusion Detection Systems"* (Kim et al., SNU, 2016). Treats OS system-call sequences as a language and learns normal behavior via LSTM language modeling; anomalies are flagged by anomaly score thresholding.

**Highlights:** LSTM language model · Leaky ReLU ensemble · kNN/k-Means baseline classifiers · benchmarked on ADFA-LD, KDD98, UNM · cross-system portability evaluation

`Python` `TensorFlow/Keras` `Machine Learning` `Cybersecurity`

---

### [docforge](https://github.com/ElNu-mp4/docforge)
> Metadata analysis & copy-paste detection for Microsoft Office files

A Python CLI toolkit that dissects internal RSID metadata inside `.docx`/`.pptx`/`.xlsx` files to detect copy-paste patterns, trace edit history, and produce a human- and machine-readable risk score. Includes a cleaner (`docforge_cleaner.py`) to sanitize metadata and rotate RSIDs.

**Highlights:** RSID dominance analysis · foreign RSID detection · paragraph↔run mismatch detection · scored risk dashboard · JSON output for pipeline use · metadata sanitization with word-count-calibrated edit time

`Python` `XML parsing` `Office Open XML` `CLI`

---

### [marketplace_ppl](https://github.com/ElNu-mp4/marketplace_ppl)
> Multi-role marketplace with seller onboarding & admin approval workflows

A full-stack Laravel marketplace demonstrating clean architecture, role-based authentication, stateful workflow orchestration, and transactional email. Sellers register, submit documentation, and undergo admin verification before gaining platform access.

**Highlights:** RBAC (`admin` / `seller` / `buyer`) · Laravel Form Requests · Eloquent relationships · mailable notifications · Vite + Tailwind CSS asset pipeline · Pest test suite

`Laravel 12` `PHP 8.2` `Tailwind CSS` `Alpine.js` `Pest` `MySQL`

---

### [soroban-handshake-contract](https://github.com/ElNu-mp4/soroban-handshake-contract)
> On-chain two-party agreement contract on Stellar testnet

A Soroban smart contract that lets two addresses form a verifiable on-chain handshake with cryptographic authorization. Enforces strict `require_auth()` — no party can act on behalf of another.

**Highlights:** State machine (`None → Pending → Agreed`) · `require_auth()` enforcement · deployed live on Stellar Testnet · zero local setup (Soroban Studio)

`Rust` `Soroban SDK v22` `Stellar Testnet` · Contract: `CAICOU5R...AUVWU`

---

## Internship

**Web Developer Intern — Dinas Kearsipan dan Perpustakaan Provinsi Jawa Tengah** *(2026)*
- Developed a full-stack book collection data management system using CodeIgniter (PHP)
- Built frontend and backend features for book inventory data entry, search, and reporting
- Provided on-site IT support throughout the internship period

---

## Education

**S1 Informatics (Computer Science)** — Universitas Diponegoro *(2023 – Present)*

---

<div align="center">
<sub>Always open to interesting problems in web dev, cybersecurity, and distributed systems.</sub>
</div>
