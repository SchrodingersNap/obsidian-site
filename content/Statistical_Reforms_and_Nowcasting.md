---
title: "Data Architecture: Nowcasting & Reforms"
tags:
  - economics
  - India/Economy
  - UPSC/GS3
---

# 📊 Strengthening the Statistical System

Box I.2 and I.3 detail the modernization of India's data systems.

## 1. Nowcasting GDP (Box I.2)
* **Why?** Official GDP comes with a 2-month lag. Policymakers need real-time data.
* **Method:** **Dynamic Factor Model (DFM)**.
* **Inputs:** 17 High-Frequency Indicators (HFI) like IIP, Auto Sales, GST, Rail Freight.
* **Process:** Extract latent factors from HFIs $\rightarrow$ Plug into ARIMAX model.
* **Result:** Q3 FY26 predicted growth = **7%**.

## 2. Statistical Reforms (Box I.3) - _High Value for Prelims_
- **Rebasing:**
    - **National Accounts (GDP):** New Base Year **2022-23** (Release: Feb 2026).
    - **IIP:** New Base Year **2022-23**.
    - **CPI:** New Base Year **2024**.
- **New Surveys:**
    - **ASISSE:** Annual Survey of _Incorporated_ Service Sector.
    - **Household Income Survey:** (First time ever).
    - **AIDIS:** All India Debt & Investment Survey (2026-27).
- **Digital:** **eSankhyiki Portal** for data dissemination.

```mermaid
graph LR
    A[17 HF Indicators] --> B[Dynamic Factor Model]
    B --> C[Extract Latent Factors]
    C --> D[ARIMAX Model]
    D --> E[GDP Nowcast]