# 🌿 Ethiopian Coffee Trade Finance & EUDR Compliance System

**PHD Thesis — Blockchain-Based Agricultural Asset Tokenisation 
& AI-Driven Credit Risk Assessment**

> Poznań University of Life Sciences (UPP) · 2026/27  
> Faculty of Economics · Mulualem Darimo

---

## 🧩 What This System Does

Smallholder Ethiopian coffee farmers cannot access credit  
because banks have no data to assess their risk.

This system solves that using 3 technologies:
1. **AI** — scores farm credit risk automatically
2. **Satellite data** — verifies EUDR deforestation compliance  
3. **Blockchain** — stores results permanently on Polygon

The cooperative manager operates the system.  
The farmer signs one paper form and receives cash.  
No blockchain knowledge required from the farmer.

---

## 🏗️ System Architecture
```
INPUT LAYER      → Farm records + Sentinel-2 satellite data
INTELLIGENCE     → Python AI: credit scoring + EUDR detection  
EXECUTION        → Solidity smart contracts on Polygon Amoy
INTERFACE        → Web dashboard for cooperative managers
```

## 📁 Project Structure
```
app/              → Frontend dashboard (HTML/CSS/JS)
backend/          → Python AI engine (FastAPI)
blockchain/       → Solidity smart contracts
data/             → Farm records and test data
```

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| AI Model | XGBoost + SHAP |
| Satellite | ESA Copernicus Sentinel-2 |
| Blockchain | Solidity + Polygon Amoy |
| Oracle | Chainlink Price Feeds |
| Backend | Python + FastAPI |
| Frontend | HTML + CSS + JavaScript |

## 👤 Author

**Mulualem Darimo**  
MSc Economics & Finance Management in Agri-Food Sector  
Poznań University of Life Sciences (UPP)
