# 🛡️ HumanProof

> Reclaiming humanity on the AI internet. A privacy-first, zero-knowledge reCAPTCHA replacement built on the Midnight Network.

---

## 💡 Overview

Traditional CAPTCHAs are broken. In an era where modern AI can easily solve image grids, read distorted text, and mimic human browser behavior, standard verification systems are falling short, enabling:
- 🚫 **Exponential Spam** & automated bot traffic.
- 👥 **Sybil Attacks** & fake account creation at scale.
- 🕵️‍♂️ **Privacy Intrusion** — traditional CAPTCHA providers track your IP, browsing behavior, and biometric details just to check if you are human.

**HumanProof** introduces a privacy-preserving proof-of-humanity layer built for the AI era. 

Users verify once locally, then generate anonymous cryptographic proofs to verify they are human across the web — without ever exposing their real-world identity, biometrics, or personal data.

---

## 🔒 Why Midnight?

Traditional blockchains are transparent by default, making them unsuitable for privacy-sensitive identity systems. Storing identity data, verification history, or user metadata publicly would undermine the core goal of private proof-of-humanity.

**Midnight** enables HumanProof to:
* **Register anonymous nullifiers** without revealing personal identity.
* **Prevent replay attacks** through private on-chain uniqueness checks.
* **Separate verification** from identity disclosure.
* **Support privacy-preserving human verification** for AI-era applications.

In **HumanProof**, the browser extension generates proofs locally on-device, while Midnight acts as the decentralized trust layer that validates proof uniqueness without learning who the user is. 

Only anonymous cryptographic nullifiers are submitted to the network — no government IDs, biometrics, names, or personal information ever appear on-chain.

---

## ✨ Features

- 🛡️ **Privacy-First Proof-of-Humanity** — Prove you are human without disclosing *who* you are.
- 🤖 **AI-Resistant Verification** — Designed from the ground up to prevent bot-driven network exploitation.
- 🔄 **Replay Attack Protection** — Uses on-chain private nullifiers to secure interactions across multiple platforms.
- ⚡ **Local Proof Generation** — Fast, local, on-device cryptographic generation directly in the browser extension.
- 🚫 **No Biometrics Stored** — No iris scans, no face hashes, and no physical identifiers.
- ⛓️ **Midnight-Powered Trust** — Anchored securely on the privacy-first Midnight Network.

---

## 🛠️ Tech Stack & Design Assets

HumanProof is built using a modern, production-grade stack designed for optimal security, type safety, and premium performance:

### ⚙️ Core Technologies
*   **Framework**: ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) **Next.js 16** (App Router & Server Actions)
*   **Language**: ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) **TypeScript** for compile-time type safety
*   **Styling**: ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) **Tailwind CSS v4** for responsive, utility-first UI
*   **Animations**: ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) **Framer Motion** for premium interactive mockups and scroll effects
*   **Components**: ![Base UI](https://img.shields.io/badge/Base_UI-007FFF?style=flat-square&logo=mui&logoColor=white) **Base UI** & **shadcn/ui** for accessible UI primitives
*   **Platform**: ![Midnight Network](https://img.shields.io/badge/Midnight_Network-050816?style=flat-square&logo=cardano&logoColor=4F8CFF) **Midnight Network** for zero-knowledge proving

## ⚙️ How It Works

```
[User Identity Source] ── (Verify Once Locally) ──> [Local Browser Extension] (Generates ZK-Proof)
                                                            │
                                                            ▼
[Web Service / DApp]   <── (Anonymous Nullifier Valid) ─── [Midnight ZK-ZK Ledger]
```

1. **Verify Once**: Connect an identity provider locally to establish humanity.
2. **Generate Proof**: The browser extension generates a local zero-knowledge proof of humanity.
3. **Verify Anywhere**: Submit the proof to any website. Midnight validates the anonymous nullifier to prevent spam, while keeping your browsing path 100% unlinkable.

---

## 🛡️ Security Model

HumanProof **never** uploads or transmits:
* Government IDs
* Biometric templates
* Secret cryptographic keys
* Raw identity data

Only anonymous cryptographic nullifiers are submitted to the Midnight network for secure, replay-resistant validation.

---

## 🚀 Development Setup

To run the premium next-generation landing page and proof demo locally:

```bash
# Clone the repository
git clone https://github.com/projectilx42-tech/midnight-hackathon-recaptcha.git

# Navigate to the project directory
cd human-proof

# Install dependencies
npm install

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) (or the port specified in terminal) in your browser to view the interactive application.

---
Built with passion for the **Midnight Hackathon** 🛡️

