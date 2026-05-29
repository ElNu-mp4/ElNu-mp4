<div align="center">

# ElNu-mp4

**Informatics Student · Aspiring Network & Cybersecurity Engineer · Full-Stack Developer**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-elangnukmianolo-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/elangnukmianolo)
[![GitHub](https://img.shields.io/badge/GitHub-ElNu--mp4-181717?logo=github&logoColor=white)](https://github.com/ElNu-mp4)
[![University](https://img.shields.io/badge/Universitas_Diponegoro-Informatics-0052CC?logo=academia&logoColor=white)](https://undip.ac.id)
[![Location](https://img.shields.io/badge/Semarang,_Indonesia-EA4335?logo=googlemaps&logoColor=white)]()

</div>

---

## About Me

Motivated Informatics undergraduate at Universitas Diponegoro with hands-on experience in full-stack web development and a strong interest in networking and cybersecurity. I've shipped real projects across PHP/Laravel/CodeIgniter, built and deployed a Soroban smart contract on Stellar testnet, and developed security tooling for Office document metadata forensics. Proven leadership through coordinator roles in large-scale campus events and student organizations.

- Certification path: **eJPT → eCPPT → OSCP** — actively practicing on Hack The Box
- Interested in home lab engineering (WireGuard VPN, Pi-hole, honeypot, network segmentation) and actively planning a personal setup
- Reach me on [LinkedIn](https://www.linkedin.com/in/elangnukmianolo) or via GitHub

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)

**Frameworks & Platforms**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-EF4223?logo=codeigniter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)
![Stellar](https://img.shields.io/badge/Soroban_SDK-7B68EE?logo=stellar&logoColor=white)

**Tools & Infra**

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-268BEE?logo=kalilinux&logoColor=white)
![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?logo=hackthebox&logoColor=black)

**Interests**

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-red?logo=hackthebox&logoColor=white)
![Networking](https://img.shields.io/badge/Network_Engineering-0078D4?logo=cisco&logoColor=white)
![Penetration Testing](https://img.shields.io/badge/Penetration_Testing-black?logo=kalilinux&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-E8001C?logo=target&logoColor=white)

---

## Featured Projects

### [lstm-hids](https://github.com/ElNu-mp4/lstm-hids)
> TensorFlow replication of LSTM-based Host Intrusion Detection System

Replication of *"LSTM-Based System-Call Language Modeling and Robust Ensemble Method for Designing Host-Based Intrusion Detection Systems"* (Kim et al., SNU, 2016). Treats OS system-call sequences as a language and learns normal behavior via LSTM language modeling; anomalies are flagged by anomaly score thresholding.

**Highlights:** LSTM language model · Leaky ReLU ensemble · kNN/k-Means baseline classifiers · benchmarked on ADFA-LD, KDD98, UNM · cross-system portability evaluation

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)

---

### [docforge](https://github.com/ElNu-mp4/docforge)
> Metadata analysis & copy-paste detection for Microsoft Office files

A Python CLI toolkit that dissects internal RSID metadata inside `.docx`/`.pptx`/`.xlsx` files to detect copy-paste patterns, trace edit history, and produce a human- and machine-readable risk score. Includes a cleaner (`docforge_cleaner.py`) to sanitize metadata and rotate RSIDs.

**Highlights:** RSID dominance analysis · foreign RSID detection · paragraph↔run mismatch detection · scored risk dashboard · JSON output for pipeline use · metadata sanitization with word-count-calibrated edit time

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-4D4D4D?logo=windowsterminal&logoColor=white)
![Office Open XML](https://img.shields.io/badge/Office_Open_XML-D83B01?logo=microsoftword&logoColor=white)

---

### [marketplace_ppl](https://github.com/ElNu-mp4/marketplace_ppl)
> Multi-role marketplace with seller onboarding & admin approval workflows

A full-stack Laravel marketplace demonstrating clean architecture, role-based authentication, stateful workflow orchestration, and transactional email. Sellers register, submit documentation, and undergo admin verification before gaining platform access.

**Highlights:** RBAC (`admin` / `seller` / `buyer`) · Laravel Form Requests · Eloquent relationships · mailable notifications · Vite + Tailwind CSS asset pipeline · Pest test suite

![Laravel](https://img.shields.io/badge/Laravel_12-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8.2-777BB4?logo=php&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)

---

### [soroban-handshake-contract](https://github.com/ElNu-mp4/soroban-handshake-contract)
> On-chain two-party agreement contract on Stellar testnet

A Soroban smart contract that lets two addresses form a verifiable on-chain handshake with cryptographic authorization. Enforces strict `require_auth()` — no party can act on behalf of another.

**Highlights:** State machine (`None → Pending → Agreed`) · `require_auth()` enforcement · deployed live on Stellar Testnet · zero local setup (Soroban Studio)

![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![Stellar](https://img.shields.io/badge/Stellar_Testnet-7B68EE?logo=stellar&logoColor=white)

Contract ID: `CAICOU5RLXVNITJOCMYT6TGW4PBUKIX46BJZEMN7UZESJO4AYMZAUVWU`

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

## GitHub Stats
 
<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ElNu-mp4&show_icons=true&theme=dark&hide_border=true&count_private=true&cache_seconds=86400)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ElNu-mp4&layout=compact&theme=dark&hide_border=true&cache_seconds=86400)
 
</div>

---

<div align="center">
<sub>Always open to interesting problems in web development, cybersecurity, and distributed systems.</sub>
</div>
