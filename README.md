# 🏠 Determinants of Airbnb Pricing in Austin, Texas

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-2ECC71?style=for-the-badge)
![Course](https://img.shields.io/badge/Course-ADTA%205340-blueviolet?style=for-the-badge)

**A data-driven approach to optimizing short-term rental pricing strategies using Airbnb listing data from Austin, Texas.**

[📌 Problem Statement](#-problem-statement) • [🔍 Research Questions](#-research-questions) • [🛠 Tech Stack](#-tech-stack) • [🚀 Getting Started](#-getting-started)

</div>

---

## 📌 Problem Statement

The short-term rental market in Austin, Texas has expanded rapidly due to rising tourism, business travel, and remote work trends. Despite this growth, **pricing remains one of the biggest challenges for hosts** — many rely on intuition rather than data.

This project builds a **data-driven framework** to identify the key factors that influence nightly Airbnb listing prices, helping hosts make smarter pricing decisions and giving policymakers insight into housing market dynamics.

---

## 🔍 Research Questions

1. Which property characteristics (bedrooms, bathrooms, accommodates) most strongly impact nightly price?
2. Do higher review ratings allow hosts to charge premium prices?
3. Does Superhost status lead to measurably higher pricing?
4. How much does property type (entire home vs. private room) affect price?
5. Does location within Austin create significant price variation?

---

## 🎯 Objectives

- Identify statistically significant pricing determinants from listing data
- Segment the Austin market by neighborhood and property type
- Evaluate the ROI of Superhost status on pricing power
- Provide actionable recommendations for both hosts and investors

---

## 📦 Dataset

| Property | Detail |
|---|---|
| **Source** | [Inside Airbnb](http://insideairbnb.com/get-the-data.html) |
| **File** | `listings.csv` |
| **Location** | Austin, Texas, USA |
| **Domain** | Short-term rental market |

### Key Variables

| Variable | Description |
|---|---|
| `price` | Nightly listing price (target) |
| `bedrooms` / `bathrooms` / `accommodates` | Property size features |
| `review_scores_rating` | Guest review score |
| `host_is_superhost` | Superhost status flag |
| `room_type` | Entire home / Private room / Shared room |
| `neighbourhood` | Geographic location in Austin |
| `number_of_reviews` | Review volume |

---

## 🛠 Tech Stack

```
Python 3.8+
├── pandas              → Data wrangling
├── numpy               → Numerical operations
├── matplotlib/seaborn  → Visualization
├── scikit-learn        → Regression & modeling
│
Google Cloud Platform
├── OpenRefine          → Data cleaning & normalization
├── Google Cloud Storage→ Dataset storage
└── BigQuery            → SQL-based querying & analysis
```

---

## 📈 Key Findings

- **Property size** (bedrooms, bathrooms, accommodates) is the strongest driver of nightly price
- **Entire home listings** command significantly higher prices than private or shared rooms
- **Location** within Austin creates notable price variation — central neighborhoods outperform suburbs
- **Superhost status** correlates positively with price but with diminishing returns at scale
- **Review ratings** alone are weak price predictors; volume matters more than score

---

## 📂 Project Structure

```
📁 airbnb-pricing-analysis-austin/
│
├── 📓 analysis.ipynb               ← Main analysis notebook
├── 📊 presentation.pptx            ← Final project presentation
├── 📄 project_proposal.docx        ← Research proposal
├── 📄 README.md
├── 📄 requirements.txt
├── 📄 .gitignore
│
└── 📁 data/
    └── listings.csv                ← Source dataset (add manually)
```

---

```bash
git clone https://github.com/Tharun3052/airbnb-pricing-analysis-austin.git
cd airbnb-pricing-analysis-austin
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

---

## 👥 Team

| Member | Role |
|---|---|
| Tharun Reddy Marreddy | Statistical analysis & modeling |
| Monica Valli Kandulapati | Data pipeline & BigQuery |
| Sai Bhargav Yaga | Visualization & reporting |

**Course:** ADTA 5340 — Discovery and Learning with Big Data | University of North Texas

---

<div align="center">
Made with ❤️ | <a href="https://github.com/Tharun3052">Tharun Reddy</a>
</div>
