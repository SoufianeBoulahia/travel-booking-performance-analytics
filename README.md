# travel-booking-performance-analytics
Data analysis and monitoring of travel booking flows (prebook, booking, valuation, errors &amp; optimization)
# Travel Booking Performance Analytics

This project showcases my work as a **Data / Business Analyst in the travel-tech industry**.  
It simulates real booking data (prebook, booking, valuation, errors) and demonstrates how to:

- Monitor **API performance** and error rates
- Build **automated dashboards** in Python (pandas, matplotlib)
- Generate **business & optimization insights** for clients and providers
- Support **account management & onboarding** with data

---

##  Use Case

A travel platform connects to multiple hotel providers (APIs).  
We want to:

- Track **traffic, bookings, error ratios, and availability**
- Detect **anomalies** (spikes in errors, drop in bookings, no-traffic situations)
- Produce **account review reports** and **optimization recommendations**

---

##  Project Structure

```text
travel-booking-performance-analytics/
│
├── data/
│   ├── raw/
│   │   └── bookings_sample.csv
│   └── processed/
│       └── daily_kpis.csv
│
├── notebooks/
│   ├── 01_exploration.ipynb
│   ├── 02_kpi_dashboard.ipynb
│   └── 03_anomaly_detection.ipynb
│
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── kpi_calculation.py
│   └── anomaly_detection.py
│
├── reports/
│   └── example_client_report.md
│
├── README.md
└── requirements.txt
