# 🛡️ GRC Compliance Automation Toolkit

A Python-based toolkit to help automate Governance, Risk, and Compliance (GRC) tasks — especially for finance and security teams. This project allows you to track NIST 800-53 and ISO 27001 controls, collect and associate evidence, and visualize your organization’s compliance posture.

---

## 🚀 Features

- 📥 Import NIST and ISO 27001 controls from CSV or JSON
- 📁 Upload and track evidence (screenshots, PDFs, configs)
- 📊 Interactive compliance dashboard (Streamlit or Flask)
- ⏰ Email alerts for overdue or missing evidence
- 📝 Generate audit reports in PDF or Excel
- 🔐 Role-based access control (optional)
- 💼 Lightweight SQLite backend (PostgreSQL ready)

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/grc-python-tracker.git
cd grc-python-tracker

grc-tracker/
├── data/              # CSVs for control loading
├── evidence/          # Uploaded proof (manual or CLI)
├── src/
│   ├── loaders/       # Scripts to load NIST/ISO controls
│   ├── dashboards/    # Streamlit / Flask dashboards
│   ├── reports/       # Report generation (PDF/Excel)
│   └── utils/         # Helper modules
├── templates/         # HTML templates for reports
├── .env               # For environment variables (e.g., email)
├── app.py             # Entry point
├── requirements.txt   # Python dependencies
└── README.md
