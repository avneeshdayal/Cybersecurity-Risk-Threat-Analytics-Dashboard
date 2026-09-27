# Cybersecurity Risk & Threat Analytics Dashboard

## Project Overview

This project analyzes cybersecurity threat data using Microsoft Excel and Power BI to identify patterns in cyberattack frequency, industry exposure, financial impact, vulnerabilities, affected users, and incident resolution time.

The objective is to demonstrate a data-driven approach to cybersecurity and technology risk analysis by transforming raw incident data into an interactive management dashboard.

---

<img src="CyberSecurity Risk & Threat Analytics Dashboard.png">

## Project Objective

The project focuses on answering the following questions:

- Which cyberattack types occur most frequently?
- Which industries experience the highest number of incidents?
- Which attack types are associated with greater financial impact?
- Which security vulnerabilities occur most frequently?
- Which attack sources are most commonly observed?
- How many users are affected by cybersecurity incidents?
- How quickly are incidents resolved?
- How does cyber risk vary across industries and attack types?

---

## Dataset

The project uses the **Global Cybersecurity Threats 2015–2024** dataset.

The dataset contains **3,000 simulated cybersecurity incident records** covering the period from 2015 to 2024.

### Key Fields

| Field | Description |
|---|---|
| Country | Country associated with the incident |
| Year | Year of the incident |
| Attack Type | Type of cyberattack |
| Target Industry | Industry targeted by the incident |
| Financial Loss | Estimated financial loss in million USD |
| Number of Affected Users | Number of users affected |
| Attack Source | Recorded source/category of the attack |
| Security Vulnerability Type | Vulnerability associated with the incident |
| Defense Mechanism Used | Defense mechanism used |
| Incident Resolution Time | Time taken to resolve the incident in hours |

---

## Tools & Technologies

- **Microsoft Excel** – Data preparation and calculated fields
- **Power BI** – Data visualization and interactive dashboard
- **DAX** – Measures and analytical calculations

---

## Data Preparation

The dataset was imported into Microsoft Excel and reviewed for consistency before being connected to Power BI.

Additional analytical fields were created to support the dashboard:

### Loss per Affected User

Calculated by converting financial loss from million USD into USD and dividing it by the number of affected users.

### Resolution Category

Incidents were categorized based on resolution time:

- **Fast:** ≤ 12 hours
- **Moderate:** 13–36 hours
- **Slow:** > 36 hours

---

## Power BI Dashboard

The Power BI dashboard provides an interactive view of cybersecurity risk patterns.

### Dashboard Components

- Total incident count
- Total financial loss
- Total affected users
- Average incident resolution time
- Cyberattack trend over time
- Attack type distribution
- Target industry exposure
- Financial loss by attack type
- Vulnerability analysis
- Incident resolution analysis
- Attack exposure by industry
- Interactive filters for analysis

### Interactive Filters

The dashboard allows users to filter the analysis by:

- Year
- Country
- Target Industry
- Attack Type

---

# Key Risk Insights

## 1. Attack Concentration

DDoS recorded the highest incident volume with **531 incidents** and also recorded the highest aggregate financial loss of approximately **$27.63 billion** in the dataset.

This indicates that, within the dataset, DDoS represents both a high-frequency and high-financial-impact attack category.

---

## 2. Industry Exposure

The **IT industry** recorded the highest number of incidents with **478 incidents** and the highest aggregate financial loss of approximately **$24.81 billion** among the target industries.

This highlights IT as the industry with the highest concentration of recorded cyber incidents in the dataset.

---

## 3. Vulnerability Exposure

**Zero-day vulnerabilities** were the most frequently observed vulnerability category, appearing in **785 incidents**.

Other frequently observed vulnerability categories included:

- Social Engineering
- Unpatched Software
- Weak Passwords

This highlights the importance of understanding the vulnerability factors associated with cybersecurity incidents.

---

## 4. Incident Response Risk

Approximately **50% of the incidents** were classified under the **Slow** resolution category.

The average resolution time for Slow incidents was approximately **54.3 hours**.

This makes incident response time an important operational dimension when assessing cybersecurity risk.

---

## 5. User Impact

**2022 recorded the highest affected-user count**, with approximately **163.3 million affected users**.

This demonstrates that incident frequency and user impact do not necessarily move together. A year with a high number of incidents may not necessarily have the highest number of affected users.

---

## 6. Incident Volume Over Time

Within the dataset, **2017 recorded the highest number of incidents**, with **319 incidents**.

The lowest incident count was recorded in **2019**, with **263 incidents**.

These observations represent patterns within the dataset and should not be interpreted as verified real-world cybersecurity trends.

---

## 7. Attack Source

**Nation-state** was the most frequently recorded attack-source category, with **794 incidents**, followed by Unknown, Insider, and Hacker Group categories.

This provides an additional dimension for analyzing the distribution of recorded cybersecurity threats.

---

## 8. Resolution Time by Attack Type

Among the attack categories, **Malware** recorded the highest average resolution time at approximately **37.1 hours**.

The differences between attack categories were relatively close, indicating that resolution time should be considered alongside other risk indicators rather than used as a standalone measure.

---

# Key Takeaway

The analysis demonstrates that cybersecurity risk should not be evaluated using incident frequency alone.

A broader risk perspective can incorporate:

**Attack Frequency + Financial Impact + User Impact + Vulnerability Exposure + Industry Exposure + Resolution Time**

Using these dimensions together provides a more comprehensive view of cybersecurity risk patterns and can support prioritization and management-level analysis.

---

# Project Workflow

```text
Raw Cybersecurity Dataset
          ↓
Data Preparation in Excel
          ↓
Calculated Fields
          ↓
Power BI Data Model
          ↓
DAX Measures
          ↓
Interactive Dashboard
          ↓
Risk Pattern Analysis
          ↓
Key Insights
