# 🌐 Universal DR Dashboard

A modern, client-side dashboard for visualizing **Disaster Recovery (DR)** test reports across hybrid and multi-cloud environments.

This tool allows teams to upload **JSON**, **Excel (.xlsx)**, or **text-based JSON** reports and instantly get a clean, interactive, and professional visualization — without any backend services.

---

## 🏢 Maintained by
**Datamotive Technologies**

Created by **Rishabh Kemni**

---

## ✨ Features

- 📊 Supports **JSON, Excel (.xlsx), and .txt (JSON)** inputs
- ☁️ Designed for **Hybrid & Multi-Cloud DR** (Nutanix, AWS, etc.)
- ⚡ 100% **client-side** (no server, no data upload)
- 🎨 Clean, enterprise-grade UI
- 🖨️ Printable reports
- 📱 Responsive layout (desktop & tablet friendly)
- 🔒 Safe for sensitive DR data (runs locally in browser)

---

## 📂 Supported Input Formats

### 1️⃣ JSON Reports
Expected structure:
- Execution metadata
- Infrastructure details
- DR cycles
- Test summaries (pass/fail)

Ideal for automated DR pipelines and CI-generated reports.

---

### 2️⃣ Excel Reports (`.xlsx`)
Recognized sheets:
- `Summary`
- `SetupDetails`
- `ReplicationTest`

Each sheet is parsed and visualized automatically.

---

### 3️⃣ Text Files (`.txt`)
- Must contain **valid JSON**
- Useful for log exports or CLI-generated outputs

---

## 🚀 Getting Started

### Option 1: Run Locally
```bash
git clone https://github.com/Datamotive-Technologies/universal-dr-dashboard.git
cd universal-dr-dashboard
