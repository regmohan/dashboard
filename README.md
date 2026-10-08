# Spark Commercial BI — Automotive Case Study Analytics Dashboard

Interactive Business Intelligence & Commercial Decision Support Dashboard built for automotive commercial case study evaluation, sales & receivables analytics, marketing funnel efficiency, and landed-cost unit economics.

**Live Portfolio Integration:** [regmimohan.com.np](https://regmimohan.com.np/)  
**Author:** Mohan Regmi (Data Analyst / Executive Operations)

---

## 🚀 Key Features

- **Interactive BI Visualizations (Chart.js):**
  - Monthly Sales Value vs. Receivables Outstanding (Cr.)
  - Marketing Lead Qualification Rate (%) vs. True Conversion Rate (%)
- **Landed Cost & Unit Economics:**
  - Complete landed cost breakdown for EV Van, Truck, Pickup, and Machinery.
  - **Live Discount Sensitivity Simulator:** Test discount impacts (0% to 8%) in real time and see margin erosion.
- **Receivables & Aging Schedule:**
  - 10-customer tracking matrix with `% Collected`, `Credit Remaining %`, and color-coded risk flags.
  - Interactive filter by risk category: Critical (>90 Days), High (61–90 Days), Normal (≤60 Days).
- **Candidate Q&A Solutions (Q1 to Q10):**
  - Structured answers evaluating business health, marketing vanity metrics, landed cost reports, collection prioritization, and the Option A vs. Option B decision framework.
- **Access Control:**
  - Passcode protection (`spark`, `mohan`, `admin`, `2026`) or one-click **"Instant View (Team / Public Mode)"** for easy sharing.
- **Pre-bundled Excel Workbooks:**
  - `Automotive_Case_Study_Candidate_Solution.xlsx`: Clean candidate submission with working formulas and native Excel charts.
  - `Automotive_Case_Study_Analysis_Model.xlsx`: Full financial model.

---

## 📂 Repository Structure

```
├── index.html                                    # Full standalone interactive BI dashboard
├── Automotive_Case_Study_Candidate_Solution.xlsx # Candidate solution Excel with working formulas
├── Automotive_Case_Study_Analysis_Model.xlsx     # Comprehensive financial model
└── README.md                                     # Project documentation
```

---

## 🛠️ How to Run Locally

You can open `index.html` directly in any web browser, or serve it locally:

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve .
```
Then visit `http://localhost:3000`.

---

## 🌐 Deployment Options

### 1. Vercel
- Import this repository into [vercel.com](https://vercel.com).
- Framework Preset: **Other** (Static HTML).
- Output Directory: `./`.
- Add a custom subdomain such as `dashboard.regmimohan.com.np`.

### 2. GitHub Pages
- Go to **Settings** > **Pages**.
- Source: **Deploy from a branch** (`main` / `/root`).
- Save to publish live.

### 3. cPanel / Subdomain Hosting
- Upload `index.html` and the `.xlsx` files to your subdomain folder (e.g. `public_html/dashboard`).
