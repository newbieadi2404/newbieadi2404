# Hi, I'm Aditya 👋

Backend engineer at **Morningstar**, building data pipelines that turn raw SEC filings into clean, validated financial data, and security-focused systems for sensitive data.

🌐 **Portfolio:** [newbieadi2404.github.io](https://newbieadi2404.github.io) · 💼 **LinkedIn:** [aditya-mishra-405670251](https://www.linkedin.com/in/aditya-mishra-405670251/) · 📍 Mumbai, India

---

## What I've shipped

| | |
|---|---|
| **24,134** SEC filings converted to Markdown in 54 min, zero failures | **184** funds covered with historical NAV and distribution data |
| **98%** test coverage on an EDGAR client (56 pytest tests) | **27%** less manual work through an LLM automation pipeline |

---

## 🔐 Secure Health Vault — [repo](https://github.com/newbieadi2404/secure-health-vault)

End-to-end encrypted healthcare records platform.

- Hybrid encryption (**AES-256-GCM + RSA-2048**) with per-recipient key wrapping
- Role-based access control and **Row-Level Security** on Supabase
- Hash-chained audit logs for tamper detection, nonce-based replay protection
- Encrypted email delivery that only the recipient's private key can unlock

`Python` `Flask` `Supabase` `JWT` `Cryptography`

## 🩻 Secure DICOM Transmission System — [repo](https://github.com/newbieadi2404/secure-dicom-transmission-system)

Secure pipeline for medical images: upload → encrypt → transmit → verify → decrypt.

- AES-256-GCM for pixel data, RSA-OAEP key exchange, **RSA-PSS signatures**
- JWT auth with RBAC, audit logging
- Validated: entropy ≈ 7.99, NPCR ≈ 99.6%, UACI ≈ 35%

`Flask` `React` `SQLAlchemy` `pydicom`

## 📊 Public Safety Intelligence System

Risk scoring and hotspot prediction for crime data.

- Risk model built on frequency, severity and temporal trends
- Random Forest hotspot prediction
- Geospatial mapping with GeoPandas and Folium

`Python` `Scikit-learn` `GeoPandas`

---

## 🚀 Currently building

Real-time fraud detection with **Kafka + FastAPI** streaming pipelines.

## 🛠 Tech stack

**Languages:** Python · Java · TypeScript · SQL  
**Backend:** Spring Boot · FastAPI · Flask · Express · REST  
**Cloud & data:** AWS (S3, SQS, Lambda) · PostgreSQL · Pandas · Docker  
**Security:** AES-GCM · RSA · JWT · RBAC · Row-Level Security  
**Testing & CI:** pytest · Playwright · Bitbucket Pipelines
