# streaming-product-analytics-dashboard
# Product Analytics & User Retention Intelligence Platform
### SQL | Python | Power BI

## Overview

Developed an end-to-end Product Analytics solution for a simulated streaming platform to analyze user engagement, content consumption, audience satisfaction, and customer retention. The project leverages SQL, Python, and Power BI to transform raw user behavior data into actionable business insights that support product growth, retention optimization, and content strategy decisions.

---

## Project Objective

Streaming platforms need to answer critical business questions:

- Which users are most likely to churn?
- Which subscription plans retain users best?
- What content drives engagement?
- Which genres receive the highest audience satisfaction?
- How do demographics impact retention?
- Which content categories contribute most to platform growth?

This project provides a centralized analytics platform to support data-driven product decision making.

---

## Tech Stack

### Data Processing
- Python
- Pandas
- NumPy

### Data Analysis
- SQL

### Business Intelligence
- Power BI
- DAX
- Data Modeling

### Data Generation
- Faker Library

---

## Dataset Overview

### Scale

- 25,000 Users
- 500 Content Titles
- 100,033 Watch Sessions
- 40,000 Ratings
- 10 Countries
- 3 Subscription Plans

---

## Data Model

### Users Table

| Column |
|----------|
| User_ID |
| Name |
| Age |
| Country |
| Subscription_Type |
| Watch_Time_Hours |
| Favorite_Genre |
| Last_Login |
| Days_Since_Login |
| Churn |

---

### Content Table

| Column |
|----------|
| content_id |
| title |
| genre |
| release_year |
| duration_min |

---

### Watch History Table

| Column |
|----------|
| watch_id |
| user_id |
| content_id |
| watch_date |
| session_duration |
| completion_rate |

---

### Ratings Table

| Column |
|----------|
| user_id |
| content_id |
| rating |

---

## SQL Analysis

Performed business-focused SQL analyses to answer key product and growth questions.

### User Analytics

- User distribution by geography
- Subscription plan adoption
- Audience segmentation
- Watch behavior analysis

### Content Analytics

- Most watched titles
- Genre popularity analysis
- Content engagement trends
- Audience satisfaction metrics

### Growth & Retention Analytics

- Churn analysis
- Retention analysis
- Subscription performance evaluation
- User inactivity tracking

---

## Power BI Dashboard

The solution was implemented through four interactive dashboard pages.

---

### 1. Executive Overview Dashboard

Provides a high-level view of platform health and business performance.

#### KPIs

- Total Users: 25,000
- Total Sessions: 100,033
- Average Watch Hours: 500
- Churn Rate: 24.95%

#### Visualizations

- Subscription Distribution
- Genre Engagement Analysis
- Retention Risk by Subscription Plan

#### Business Insights

- Premium users exhibit the highest churn risk.
- Subscription adoption remains balanced across plans.
- Genre engagement varies significantly across categories.

---

### 2. User Analytics Dashboard

Provides demographic and behavioral insights.

#### KPIs

- Average Age
- Average User Watch Hours
- Countries Covered

#### Visualizations

- User Distribution by Country
- Age Group Analysis
- Average Watch Hours by Country
- Churn Rate by Country

#### Business Insights

- User engagement remains relatively consistent across geographies.
- Churn rates differ across regions, highlighting opportunities for localized retention strategies.
- Age demographics provide insights into audience composition.

---

### 3. Content Analytics Dashboard

Evaluates content performance and audience preferences.

#### KPIs

- Total Titles: 500
- Average Rating: 3.0 / 5
- Average Completion Rate: 65.03%

#### Visualizations

- Top 10 Most Watched Titles
- Content Consumption by Genre
- Audience Satisfaction by Genre
- Completion Rate by Genre

#### Business Insights

- Crime and Fantasy genres generate the highest content consumption.
- Thriller content receives the strongest audience satisfaction scores.
- Content completion remains relatively consistent across genres.

---

### 4. Growth & Retention Analytics Dashboard

Analyzes customer retention and churn behavior.

#### KPIs

- Churned Users: 6,237
- Active Users: 18,763
- Retention Rate: 75.05%

#### Visualizations

- Retention Risk by Subscription Plan
- Churn Rate by Country
- Retention Risk by Age Segment

#### Business Insights

- Premium subscribers demonstrate the highest churn rate.
- Retention performance varies across demographic groups.
- Geographic trends reveal retention opportunities across markets.

---

## Key Business Findings

### User Engagement

- Average watch time exceeds 500 hours per user.
- User engagement remains strong across all subscription plans.

### Content Performance

- Crime and Fantasy are the most consumed genres.
- Thriller content achieves the highest audience satisfaction.

### Retention

- Platform retention exceeds 75%.
- Churn is influenced by subscription plans, demographics, and user inactivity.

---

## Skills Demonstrated

### Product Analytics
- User Engagement Analysis
- Retention Analytics
- Churn Analysis
- Customer Segmentation

### Data Analytics
- SQL Querying
- Data Cleaning
- Data Modeling
- KPI Development

### Business Intelligence
- Power BI Dashboarding
- DAX Measures
- Executive Reporting
- Data Storytelling

### Business Strategy
- Growth Analytics
- Content Performance Evaluation
- Retention Optimization
- Insight Generation

---

## Project Screenshots

### Executive Overview Dashboard
(Add Screenshot)

### User Analytics Dashboard
(Add Screenshot)

### Content Analytics Dashboard
(Add Screenshot)

### Growth & Retention Analytics Dashboard
(Add Screenshot)

---

## Future Enhancements

- Machine Learning-based Churn Prediction
- Recommendation Engine
- Cohort Retention Analysis
- A/B Testing Framework
- Streamlit Web Application
- Real-Time Analytics Pipeline

---

## Author

Kanishka Singh

Electronics & Communication Engineering | Product Analytics | Business Intelligence | SQL | Python | Power BI
