Customer Support Efficiency Analytics
End-to-End Data Cleaning • Analysis • Dashboard Project


#Overview
This project analyzes 80 real-world style customer support tickets to identify patterns that directly impact support efficiency, customer experience, and internal workload planning.

It focuses on uncovering:
Delays in issue resolution
Recurring customer pain points
Peak support load hours
Agent performance differences
Opportunities to improve SLAs and staffing

The goal is to empower support teams to reduce response times, improve customer satisfaction, and streamline operations.


#Tools & Technologies

Python (Pandas, NumPy)
VS Code (Notebook environment)
Looker Studio (Interactive Dashboard)
CSV Dataset


#Project Features

1. Cleaned and processed a dataset of 80 customer support tickets
2. Engineered useful analytical features:
    created_day
    created_hour
    resolution_time_hours
    is_repeat_customer
3. Calculated resolution time for every ticket
4. Identified which issue categories occur most frequently
5. Analyzed workload patterns through hourly ticket distribution
6. Built an agent performance model (tickets handled + average resolution time)
7. Extracted high-frequency keywords from message texts
8. Designed a professional dashboard with 4 essential business visuals


#Dashboard Highlights (Looker Studio)

The final dashboard includes:
Tickets by Category
Avg Resolution Time by Category
Tickets by Hour (Peak Load Analysis)
Agent Performance Table

Key KPIs:
Avg Resolution Time: ~32.79 hours
Total Tickets: 80
Most Frequent Category: Technical Issue
Peak Hour: 12 PM


#Key Insights

1. Technical Issues and Account Issues take the longest to resolve (≈ 36–39 hrs).
2. Ticket volume peaks at 12 PM, followed by 9 AM, showing a midday workload spike.
3. Medium priority tickets are resolved faster than High/Urgent tickets → indicates inefficient priority handling.
4. Many users are repeat ticket raisers, often facing recurring issues.
5. Agent efficiency varies — some agents consistently resolve more tickets in less time, signaling opportunities for:
    A. targeted coaching
    B. process standardization
    C. workload balancing


#Project Structure
support-efficiency-analytics/
│
├── analysis.ipynb
├── support_tickets.csv
├── support_tickets_clean.csv
├── dashboard.pdf
└── README.md


#Outcome

This project demonstrates practical, job-ready skills in:
Real-world data cleaning & preparation
Feature engineering to extract hidden patterns
Exploratory data analysis (EDA)
Building an interactive operational analytics dashboard
Translating raw data into clear business insights