# Renty – Intelligent Rental Analytics & Decision Platform

A modular data-driven platform for optimizing a rental e-commerce ecosystem, combining **supply–demand gap analysis**, **personalized recommendation systems**, and **fraud detection** to support strategic and operational decision-making.

**Context:** Graduation Project – Systems Architecture & Data Science (2025-Under Development)

---

## Platform Overview

Renty is designed as an **intelligent analytics layer** on top of a rental marketplace.  
Rather than focusing on a single model, the platform integrates **multiple analytical systems** that address real business risks and opportunities.

**Core goals:**
- Balance supply and demand across categories and regions
- Personalize user experience and increase conversions
- Detect abnormal and potentially fraudulent behavior
- Provide interpretable, actionable outputs for decision-makers

---

## Core Intelligence Modules

### 1. Supply–Demand Gap Analysis

Identifies where demand exceeds available supply and quantifies the severity of imbalance.

**Capabilities:**
- Category, subcategory, and territory-level gap analysis
- Custom Gap Score formulation with normalization and severity levels
- Trend analysis and weekly monitoring snapshots
- Automated action planning (operational & strategic)

**Outcome:**  
Enables inventory optimization, vendor targeting, and demand-aware expansion.

---

### 2. Recommendation System (RS)

A hybrid recommendation engine that personalizes product suggestions for users.

**Capabilities:**
- Combines collaborative filtering and content-based signals
- Uses user demographics, behavior, and product features
- Handles sparsity and cold-start scenarios
- Evaluated using ranking-based metrics (AUC, Precision@K, Recall@K)

**Outcome:**  
Improves user engagement, conversion rates, and customer lifetime value.

---

### 3. Fraud Detection & Risk Signals

Detects suspicious behavior patterns that may indicate fraud or system abuse.

**Capabilities:**
- Behavioral anomaly detection
- Transaction-level risk indicators
- User and activity profiling
- Supports manual review and rule-based escalation

**Outcome:**  
Reduces financial risk and improves platform trust and integrity.

---

## Technical Highlights

- Modular system architecture (independent but connected analytics modules)
- Custom metric design focused on **interpretability**
- Multi-level analytics (user, product, category, territory)
- Reusable Python modules with clean separation of concerns
- Interactive dashboards and API-ready outputs
- Monitoring-oriented design, not one-off analysis

---

## Key Insights

- Supply imbalance is often localized to a small number of subcategories
- Recommendation quality improves more from feature engineering than model complexity
- Fraud patterns are better detected through behavior consistency than single rules
- Monitoring trends over time is more valuable than static predictions
- Interpretable systems outperform black-box models in operational settings

---

## Technology Stack

- **Language:** Python
- **Data Processing:** pandas, NumPy
- **Machine Learning:** scikit-learn, LightFM
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Outputs:** Excel, CSV, JSON, interactive HTML dashboards
- **Architecture:** Notebook pipelines + reusable Python modules

---

## Outputs & Deliverables

- Business-ready Excel reports
- Interactive dashboards for web embedding
- API-consumable CSV / JSON files
- Weekly monitoring snapshots
- Automated recommendations and action plans
