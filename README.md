# 🏙️ Urban Development & Public Sentiment Analytics Dashboard

## 📌 Project Overview
This project delivers a comprehensive urban analytics dashboard designed to help municipal governments:
- Optimize resource allocation
- Improve public services
- Understand citizen sentiment in real time

By integrating 311 service requests, public transport data, and social media sentiment, the dashboard provides actionable insights for city planners.

---

## ❓ Problem Statement
City planners often rely on outdated census data and anecdotal feedback, leading to inefficient resource distribution and poor responsiveness to citizen needs.

**This project aims to:**
- Aggregate diverse urban datasets
- Visualize problem hotspots
- Correlate public sentiment with service performance
- Enable data-driven decision-making

---

## 🗂️ Data Sources
| Dataset           | Description |
|------------------|-------------|
| `311_ServiceRequests` | Non-emergency complaints with geolocation, type, priority, and status |
| `SentimentData`       | Social media sentiment scores and topics |
| `PublicTransport`     | Transit ridership, delays, and mode data |
| `UrbanAnalysis`       | Aggregated metrics across neighborhoods |
| `Date`                | Time dimension for filtering and analysis |

---

## 📆 Weekly Breakdown

### Week 1 – Data Integration & Geospatial Modeling
- Cleaned and mapped 311 data
- Integrated shapefiles into Power BI
- Created heatmaps of complaint hotspots

### Week 2 – Service Requests & Sentiment Analysis
- Scraped and scored social media sentiment
- Built dashboards for complaint types and resolution times
- Overlaid sentiment data on complaint maps

### Week 3 – Transit Performance & Sentiment Correlation
- Visualized ridership and delays
- Linked negative sentiment to transit issues
- Used Key Influencers to identify drivers of dissatisfaction

### Week 4 – Resource Allocation & Needs Analysis
- Compared resource availability vs. complaint volume
- Mapped underserved neighborhoods
- Highlighted gaps in service coverage

### Week 5 – Executive Summary Dashboard
- Aggregated KPIs: complaints, sentiment, ridership
- Visualized trends and resource gaps
- Delivered a printable one-page report for stakeholders

---

## 📊 Key Insights
- High complaint areas (Downtown, Midtown) lacked sufficient resources
- Transit delays strongly correlated with negative sentiment
- Uptown and SoHo were underserved despite high complaint volumes

---

## ✅ Recommendations
- Prioritize high-complaint, low-resource neighborhoods
- Improve transit reliability to boost public sentiment
- Align resource allocation with real-time needs

---

## 🛠️ Tech Stack
- **Power BI**: Dashboard development and data visualization
- **Azure Cognitive Services**: Sentiment analysis
- **Python / Pandas**: Data cleaning and preprocessing
- **Geospatial Mapping**: Shapefile integration for spatial analysis

---

## 📄 Final Deliverables
- Interactive Power BI dashboards
- Executive summary report

- *   `README.md`: This detailed project explanation.

---

## 5. How To Use This Project

1.  **Clone the repository** to your local machine.
2.  **Ensure you have Power BI Desktop** installed.
3.  **Open the `Clinical_Trial_Dashboard.pbix` file**.
4.  **Explore the dashboards!** All visuals are interactive.
5.  **(Important) Data Source Settings:** The `.pbix` file is configured to look for the CSV files in a specific local path. Upon opening, you may need to update the data source settings in Power BI to point to the location of the `/Data/` folder on your machine. This can be done via `Transform data` -> `Data source settings`.


---

## Connect with Me

This end-to-end project was developed by **Reuben Samuel**. I am passionate about leveraging data engineering and business intelligence to solve complex problems and create actionable insights from raw data.

I'd love to connect with you to discuss data analytics, Power BI development, or potential opportunities. Please feel free to reach out or view my professional profile on LinkedIn.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Reuben%20Samuel-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/reuben-samuel-b55b97234/)

- Visuals for complaint distribution, sentiment trends, and resource gaps

---

Let me know if you’d like a badge section, deployment instructions, or contribution guidelines added!
