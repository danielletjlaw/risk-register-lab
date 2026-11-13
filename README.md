# Risk Register — E-Commerce Web Application

**Author:** Danielle Law  
**Framework:** NIST SP 800-30 Rev. 1  
**Status:** Complete

---

## About This Project

This is a GRC portfolio project. It contains a risk register for a fictional e-commerce web application called **ShopCore**, which handles customer accounts, payment processing, and order management.

The goal is to identify realistic threats, score them using a consistent methodology, and recommend treatment plans the way a real risk analyst would.

---

## System Description

**System Name:** ShopCore  
**System Type:** Web application (cloud-hosted)  
**Data Handled:** Customer PII, payment card data, order history  
**Hosting:** Cloud-based (AWS), internet-facing  
**Users:** Customers (public), employees (internal admin), third-party payment processor

---

## Files in This Repo

| File | Description |
|---|---|
| `README.md` | This file — project overview and methodology summary |
| `risk-register.csv` | The risk register — one row per identified risk |
| `methodology.md` | Scoring guide and NIST 800-30 alignment notes |

---

## How to Read the Risk Register

Each row in `risk-register.csv` represents one risk and contains:

- **Risk ID** — unique identifier (R-001, R-002, etc.)
- **Asset** — what is at risk
- **Threat** — the event that could cause harm
- **Vulnerability** — the weakness the threat exploits
- **Likelihood (1–5)** — how probable the threat is
- **Impact (1–5)** — how much damage if it happens
- **Risk Score** — Likelihood × Impact (1–25)
- **Risk Level** — Low / Medium / High / Critical
- **Treatment** — what to do about it
- **Treatment Type** — Mitigate / Accept / Transfer / Avoid
- **Status** — Open / In Progress / Closed

---

## Risk Level Scale

| Score | Level |
|---|---|
| 1–5 | Low |
| 6–12 | Medium |
| 13–19 | High |
| 20–25 | Critical |

---

## Methodology

See [`methodology.md`](./methodology.md) for full details on how threats were identified and scored.

---

*This is a fictional scenario created for portfolio purposes. No real customer data or systems are involved.*
