# 📺 BrightTV Viewership Analytics Case Study

## Overview

This project analyzes subscriber and viewership data for **BrightTV**, a streaming platform aiming to grow its subscription base during the current financial year.

The objective of this analysis is to generate actionable business insights that support the **Customer Value Management (CVM)** team in increasing subscriber engagement, improving content consumption, and growing the overall user base.

---

## Business Objectives

The analysis addresses the following key questions:

- Identify user and viewing trends across the platform.
- Determine the factors that influence content consumption.
- Recommend content strategies to increase engagement during periods of low viewership.
- Propose initiatives to grow BrightTV's subscriber base.
- Provide additional insights that can support strategic decision-making.

---

## Dataset

The project uses two primary datasets:

- **User Profiles**
  - Subscriber demographics
  - Registration information
  - Customer attributes

- **Viewer Transactions**
  - Individual viewing sessions
  - Session duration
  - Viewing timestamps
  - Content consumed

### Notes

- All timestamps were originally provided in **UTC** and converted to **South African Standard Time (SAST / UTC+2)**.
- Each record represents a single viewing session.

---

## Project Structure

```
BrightTV-Analytics/
│
├── data/
│   ├── user_profiles.csv
│   └── viewer_transactions.csv
│
├── notebooks/
│   └── BrightTV_Analysis.ipynb
│
├── presentation/
│   └── BrightTV_Case_Study.pdf
│
├── visuals/
│   ├── consumption_by_day.png
│   ├── hourly_usage.png
│   ├── subscriber_growth.png
│   └── ...
│
├── README.md
└── requirements.txt
```

---

## Analysis Performed

### Data Preparation

- Data cleaning
- Handling missing values
- Timestamp conversion (UTC → SAST)
- Feature engineering
- Data validation

### Exploratory Data Analysis (EDA)

- User growth trends
- Daily and hourly viewing patterns
- Session duration analysis
- Content popularity
- Consumption by weekday
- Peak viewing hours
- Subscriber segmentation

### Business Insights

The analysis explores:

- Peak vs. low consumption periods
- Viewer engagement trends
- User behaviour patterns
- Content performance
- Opportunities for subscriber retention

---

## Key Questions Answered

### 1. User & Usage Trends

- Subscriber activity over time
- Viewing behaviour
- Most active viewing periods
- Session frequency and duration

### 2. Factors Influencing Consumption

Potential influencing factors include:

- Day of week
- Time of day
- Session duration
- Content type
- User engagement patterns

### 3. Content Recommendations

Recommendations are provided for increasing consumption during low-traffic periods by:

- Scheduling premium content releases
- Promoting binge-worthy series
- Introducing family and children's programming
- Personalised recommendations
- Limited-time featured content

### 4. User Growth Initiatives

Suggested initiatives include:

- Referral programmes
- Targeted retention campaigns
- Personalised content recommendations
- Reactivation campaigns for inactive users
- Loyalty rewards
- Bundled subscription offers

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- PowerPoint

---

## Key Deliverables

- Data cleaning and preparation
- Exploratory data analysis
- Business insights
- Data visualisations
- Strategic recommendations
- Executive presentation

---

## Example Visualisations

The project includes visualisations such as:

- Daily consumption trends
- Hourly viewing patterns
- Top-performing content
- Session duration distributions
- Subscriber growth trends
- User segmentation
- Heatmaps of viewing activity

---

## Business Impact

The recommendations generated from this analysis aim to:

- Increase subscriber engagement
- Improve content utilisation
- Reduce churn
- Increase average viewing time
- Support data-driven content scheduling
- Drive subscriber growth

---

## Future Improvements

Potential extensions include:

- Churn prediction modelling
- Recommendation system development
- Customer lifetime value (CLV) analysis
- Cohort analysis
- Predictive forecasting
- Machine learning models for engagement prediction

---

## Author

**Your Name**

Data Analytics Case Study

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

## License

This project was completed as part of a data analytics case study and is intended for educational and portfolio purposes.
