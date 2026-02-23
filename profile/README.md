# ZaaNet

Welcome to the **ZaaNet GitHub Organization** — home of the smart contracts powering the ZaaNet decentralized WiFi monetization network.

---

## What is ZaaNet?

ZaaNet is a blockchain-integrated WiFi access layer that enables network owners to monetize internet access transparently and securely.

ZaaNet allows:

* **Network Owners (Hosts)** to monetize unused bandwidth.
* **Guests** to access WiFi through secure, automated authentication.
* **On-chain settlement** of platform fees and payment logic.
* **Plug-and-play deployment** via OpenWRT-compatible routers.

ZaaNet is currently in early mainnet deployment in Ghana, with live routers processing real user sessions.

---

## Current Status

ZaaNet has completed:

* ✔️ Smart contract deployment on mainnet
* ✔️ Live router authentication and on-chain validation
* ✔️ End-to-end payment → authorization flow

ZaaNet is now in limited production rollout with real-world sessions validating system integrity and uptime.

The focus phase is:

* Stability
* Field reliability
* Router scalability
* Operational hardening

---

## Architecture Overview

ZaaNet consists of:

1. **OpenWRT Router Layer**

   * Captive portal (NoDogSplash)
   * BinAuth-based authorization
   * Secure backend verification
   * Local caching & fail-safes

2. **Backend Coordination Layer (Private)**

   * Session management
   * Payment verification
   * Router registration
   * Health monitoring

3. **Smart Contracts (Public in this Org)**

   * Network registration
   * Payment processing
   * Platform fee enforcement
   * Transparent on-chain settlement

This repository contains the blockchain logic powering the economic layer of ZaaNet.

---

## What You'll Find Here

This organization hosts the open-source smart contracts that handle:

* **Payment Processing**
* **Network Registration**
* **Platform Fee Logic**
* **Economic Settlement Mechanisms**

These contracts ensure transparent, auditable, and tamper-resistant operation of the ZaaNet protocol.

Other system components (router firmware customizations, backend services, provisioning tools) remain private during early deployment.

---

## How to Contribute

We welcome:

* Smart contract reviews
* Gas optimization suggestions
* Security audits and vulnerability disclosures
* Pull requests improving contract clarity and efficiency

If you discover a security issue, please open a responsible disclosure issue or contact us directly.

---

## Connect With Us

* Website: [https://zaanet.xyz](https://zaanet.xyz)
* Email: [zaanetofficial@gmail.com](mailto:zaanetofficial@gmail.com)

---

## Vision

ZaaNet is building a decentralized infrastructure layer for WiFi monetization — where access, payments, and trust are automated and verifiable.

We believe internet access markets should be:

* Transparent
* Programmable
* Fair to providers
* Accessible to users

ZaaNet is in early deployment — and we are building deliberately, focusing on reliability before scale.

This is foundational infrastructure.
