<div align="center">

# 👨‍💻 Daffa Jaya Perkasa
### **Full-Stack | Mobile | AI | DevOps Engineer**

📍 Bandung, Indonesia (UTC+7 / WIB) • 👤 he/him • 💼 [LinkedIn](https://linkedin.com/in/dafayape) • 📧 [dafayape@gmail.com](mailto:dafayape@gmail.com)

```
Building resilient, high-performance distributed systems, edge-native applications,
and machine learning pipelines with rigorous Clean Architecture and international ISO standards compliance.
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dafayape-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/dafayape)
[![ISO 25010](https://img.shields.io/badge/ISO%2FIEC-25010%20Software%20Quality-success?logo=checkmarx&logoColor=white)](#standards--engineering-principles)
[![ISO 27001](https://img.shields.io/badge/ISO%2FIEC-27001%20Information%20Security-blue?logo=auth0&logoColor=white)](#standards--engineering-principles)
[![ISO 12207](https://img.shields.io/badge/ISO%2FIEC-12207%20Software%20Lifecycle-orange?logo=git&logoColor=white)](#standards--engineering-principles)
[![ISO 42001](https://img.shields.io/badge/ISO%2FIEC-42001%20AI%20Management-purple?logo=openai&logoColor=white)](#standards--engineering-principles)
[![GPG Verified](https://img.shields.io/badge/GPG-Ed25519%20Signed-brightgreen?logo=gnupg&logoColor=white)](#cryptographic-verification)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 🧭 About Me

I am a software engineer specializing in architecting end-to-end resilient platforms across four core engineering pillars: **Full-Stack Web**, **Mobile Applications**, **Artificial Intelligence**, and **DevOps Infrastructure**.

My engineering methodology prioritizes:
- **Clean Architecture & Separation of Concerns**: Enforcing explicit boundaries across UI, domain business logic, and infrastructure adapters.
- **Resilience in Constrained Environments**: Crafting low-bandwidth disruption-tolerant edge systems (LoRa, SQLite Store-and-Forward, binary serialization).
- **Cryptographic Trust & Zero Fluff**: 100% GPG-signed commits with verified identity non-repudiation, zero hardcoded credentials, and zero AI co-author pollution.
- **Quality Gates Automation**: Strict CI/CD pipelines enforcing regression testing, race condition detection, and static analysis.

---

## 🛠️ Technical Competencies

| Domain | Technologies & Frameworks |
|---|---|
| **Backend & Distributed Systems** | Go (Gin, Gorilla WebSocket, GORM), Python (FastAPI), REST APIs, WebSockets, PostgreSQL 16, Redis 7 |
| **Frontend & Web Engineering** | Next.js 16 (App Router), React 19, TypeScript, Tailwind CSS, Turbopack, Leaflet Maps, State Management |
| **Mobile & Edge Computing** | Flutter 3.x, Dart, Riverpod 2.6, BLoC Pattern, SQLite (Store-and-Forward), MessagePack Binary Codec, Geofencing |
| **Artificial Intelligence & Vision** | PyTorch, Google SigLIP ViT, Zero-Shot Classification, Hugging Face Transformers, OpenCV |
| **DevOps & Security Hardening** | Docker & Multi-Stage Builds, Docker Compose, GitHub Actions CI/CD, Ed25519 GPG, Linux/Unix Shell Scripting |

---

## 🚀 Featured Architectural Projects

### 1. 🛡️ [SESPIMMA](https://github.com/dafayape/sespimma)
> **Digital evaluation, anti-spoofing GPS geofence attendance, and cadet tracking platform for police academy institutions.**
- **Stack**: Go (Gin, GORM, Redis), Next.js 16 (React 19), Flutter (Clean Architecture, BLoC Pattern).
- **Key Engineering**: 8-tier RBAC security model, append-only audit trail ledger, multi-aspect evaluation (academic, physical fitness, mental sociometry), anti-mock GPS geofencing via Redis geospatial caching.
- **Compliance**: ISO/IEC 25010 (Quality), ISO/IEC 27001 (Hardened Security), ISO/IEC 12207 (Lifecycle).

### 2. 🌊 [Maritime LoRa Mesh Network Simulator](https://github.com/dafayape/maritime-simulation)
> **Software-in-the-Loop Maritime Telecommunications, Mesh Routing & Physical Ether Simulator.**
- **Stack**: Go 1.22 (Virtual Ether Engine), Next.js 16 (Harbor Master Dashboard), Flutter (Ship Node Client).
- **Key Engineering**: Physical radio ether simulation, BFS shortest-path dynamic multi-hop routing, Disruption-Tolerant Networking (DTN) via offline transactional SQLite queue, pure binary MessagePack serialization.
- **Compliance**: ISO/IEC 25010, ISO/IEC 27001, ISO/IEC 12207.

### 3. 🤖 [Berseka Vision AI](https://github.com/dafayape/berseka-vision-ai)
> **Production-grade Vision AI for automated waste classification using Google SigLIP zero-shot model.**
- **Stack**: Python 3.11, FastAPI, PyTorch, Google SigLIP ViT, Docker Multi-Stage.
- **Key Engineering**: Sub-second zero-shot visual inference, asynchronous worker pools, structured confidence scoring matrix, automated quality regression suite.
- **Compliance**: ISO/IEC 42001:2023 (AI Management System) & ISO/IEC 25059:2023 (Quality of AI Systems).

### 4. 🌴 [SawitChain](https://github.com/dafayape/sawitchain)
> **Web platform for palm oil supply chain traceability and sustainability monitoring.**
- **Stack**: Next.js 16, React 19, TypeScript, Tailwind CSS, Lucide Icons.
- **Key Engineering**: Enterprise supply chain ledger dashboard, component-driven Clean Architecture, 100% static page pre-rendering via Turbopack.
- **Compliance**: ISO/IEC 25010 & ISO/IEC 27001.

### 5. ⚙️ [Dotfiles](https://github.com/dafayape/dotfiles)
> **Modular Unix environment configurations, developer tooling, and ISO 27001 cryptographic security hardening.**
- **Stack**: Bash 5.x, POSIX Shell, Ed25519 GPG, Git Configuration.
- **Key Engineering**: Modular `.bashrc.d` architecture (15 components), idempotent automated installer, global security ignore policies, SSH keepalive hardening.
- **Compliance**: ISO/IEC 12207 & ISO/IEC 27001.

---

## 🛡️ Standards & Engineering Principles

```mermaid
graph LR
    subgraph Governance["International Standards Compliance"]
        ISO25010["ISO/IEC 25010<br/>Software Product Quality"]
        ISO27001["ISO/IEC 27001<br/>Information Security"]
        ISO12207["ISO/IEC 12207<br/>Software Lifecycle"]
        ISO42001["ISO/IEC 42001<br/>AI Management"]
    end

    subgraph Guarantees["Technical Guarantees"]
        G1["Automated Test Suites (100% Pass)<br/>0 Data Race in Concurrency<br/>Sub-second Response Times"]
        G2["100% Ed25519 GPG Verified Commits<br/>Append-Only Audit Logging<br/>Zero Secret Contamination"]
        G3["Conventional Commits v1.0.0<br/>Clean Architecture Layers<br/>Automated CI Quality Gates"]
        G4["Zero-Shot Model Governance<br/>Deterministic Scoring Thresholds"]
    end

    ISO25010 --> G1
    ISO27001 --> G2
    ISO12207 --> G3
    ISO42001 --> G4
```

---

## 🔐 Cryptographic Verification

All source code contributions across public and private repositories are cryptographically signed to guarantee authenticity and non-repudiation:
- **GPG Key ID**: `7573912AF4141E99`
- **Algorithm**: `Ed25519`
- **Fingerprint**: `63C9 25CD FF6A 5C49 46DA  ACF0 7573 912A F414 1E99`
- **Commit History**: 100% GitHub Verified Badge (`verified: true`)

---

## 📬 Contact & Connect

- **Email**: [dafayape@gmail.com](mailto:dafayape@gmail.com)
- **LinkedIn**: [linkedin.com/in/dafayape](https://linkedin.com/in/dafayape)
- **GitHub**: [@dafayape](https://github.com/dafayape)
- **Location**: Bandung, West Java, Indonesia (UTC+7 / WIB)
- **Pronouns**: he / him
- **Availability**: Open for high-impact Full-Stack, Mobile, AI, and DevOps engineering opportunities.

<div align="center">

<sub>Designed and engineered by **Daffa Jaya Perkasa** • Licensed under [MIT](LICENSE)</sub>

</div>
