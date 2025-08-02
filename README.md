# Enterprise APEX + ORDS Architecture (Docker-based)

This project demonstrates a scalable and modular architecture using **Oracle APEX** and **Oracle REST Data Services (ORDS)** within **Docker containers**. It is designed to fit large-scale enterprise systems where business logic and data are separated from the user interface (APEX).

---

## 🚀 Purpose

This architecture aims to:

- Host **APEX** in one Oracle XE instance (lightweight and fast).
- Keep **business logic and data** in a separate Oracle XE database.
- Use **ORDS REST services** to connect APEX to the business layer.
- Demonstrate that even with Oracle XE, a scalable enterprise-like design is possible.

---

## 🧱 Architecture Overview

