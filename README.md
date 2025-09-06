# Customer Segmentation for Food Delivery (Vber Eats)

**Timeline:** Jan 2025 – Apr 2025  
**Tools:** Python, SQL (SQLite/Postgres/MySQL), scikit-learn, Power BI

## Project Overview
Segment customers of a food delivery service (Vber Eats) using RFM and unsupervised ML to improve retention and revenue. Dataset: `customer-data.csv` (10,000 customers) with order timestamps, amounts, and counts.

## Goals
- Identify low vs high performing customers using RFM (Recency, Frequency, Monetary)
- Build actionable segments and persona definitions
- Validate clusters with Silhouette score and visualize via PCA
- Provide BI dashboards and experiment designs (A/B test uplift projections)

## What I did
- Data exploration & integrity checks
- RFM feature engineering (SQL + Python)
- Pareto (80/20) revenue analysis
- Elbow method and silhouette score based cluster validation
- K-Means clustering and PCA visualization
- Cohort & retention analysis
- Power BI dashboards (3) for stakeholders
- A/B test uplift simulation (projected +12% ARPU, +15% CTR)

## Repo structure
(see folder structure in repository root)

## How to reproduce
1. Create virtual env and install:
```bash
pip install -r requirements.txt
