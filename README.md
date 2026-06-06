# Car Insurance Claim & Risk Portfolio Analysis

## 📌 Project Overview
As an aspiring data analyst, I developed this project to analyze a car insurance portfolio consisting of **2,002 unique policyholders**. The objective was to uncover key demographic and policy-related risk drivers, analyze premium distribution, and identify factors contributing to the portfolio's **21.43% claim rate**.

This project features an interactive **Power BI Dashboard** and a tailored **Slide Deck** designed to communicate data insights to stakeholders for corporate risk mitigation.

---

## 📊 Interactive Dashboard Preview
![Power BI Dashboard Preview](screenshots/dashboard_preview.png)

---

## 📈 Key Business Metrics (Baseline)
* **Total Policies Evaluated:** 2,002 unique customers
* **Overall Portfolio Claim Rate:** 21.43%
* **Average Monthly Premium:** $1,859
* **Average Cost Per Claim:** $34,622

---

## 🔍 Core Insights Uncovered

### 1. High Liability in the "Standard" Tier
While common intuition might suggest that highest-tier comprehensive plans experience more volume, the data revealed that the **Standard Coverage** tier generated the highest absolute number of claims (**143 claims**), followed by Basic (**131**) and Comprehensive (**124**). This suggests a potential risk-concentration bias in mid-tier product selections.

### 2. Collision Dominance
Nearly half of all insurance payouts (**49.71%**) stem directly from vehicle **Collisions**. This completely dwarfs other operational risks like Theft (20.52%), Weather (12.83%), and Fire (9.13%).

### 3. Asset Concentration
The portfolio is heavily exposed to two vehicle types: **Sedans (29.77%)** and **SUVs (28.97%)**. Combined, they represent roughly **59%** of the entire policy volume, meaning any pricing changes here will heavily influence overall profitability.

### 4. Demographic Premium Volatility
Mapping average monthly premiums against age highlighted sharp premium peaks near **$2,500** for drivers in their early 20s, a stabilization period ($1,500 - $1,800) during mid-life, and a steady climb back toward **$2,000+** for drivers surpassing 60 years old.

---

## 💡 Strategic Recommendations
1.  **Introduce Safety-Driven Telematics:** Implement minor premium discounts or tracking incentives for claim-free periods to explicitly target and reduce the **49.71% collision rate**.
2.  **Audit Mid-Tier Pricing Rules:** Review underwriting boundaries for the "Standard" coverage tier to determine if premiums adequately reflect its high-frequency claim volume.
3.  **Smooth Age-Bracket Premium Curves:** Standardize age-based pricing algorithms to reduce sharp volatility and optimize rates for senior age demographics.

---

## 📂 Repository Contents
* `/dashboard`: Contains the original `.pbix` Power BI file.
* `/presentation`: Contains the custom HTML/CSS slide deck (`index.html`) and the complete presenter script.
* `/screenshots`: High-resolution captures of the analytical dashboard.

---

## 🛠️ Tools Used
* **Power BI:** Data visualization, modeling, and dashboard construction.
* **DAX:** Basic measures to compute claims metrics.
* **HTML5/CSS3:** Used to build a clean, custom presentation slide deck.
* **Markdown:** Project documentation.

---

## 🧑‍💻 Connect with Me
* **LinkedIn:** [Your Name](Your LinkedIn URL)
* **Portfolio Website:** [Your Website URL]
* **Email:** [Your Email Address]
