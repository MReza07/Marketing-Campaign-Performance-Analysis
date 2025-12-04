## 📊 Marketing Campaign Performance Report

A Power BI Dashboard Project

## 📁 Project Overview

This project analyzes marketing campaign performance across multiple dimensions such as channel, region, budget, product category, and campaign duration.
The dashboard provides clear visibility into success rates, audience reach, conversion metrics, and spending behavior, enabling data-driven decision-making for marketing strategy optimization.

## 📷 Dashboard Preview

👉 View Dashboard https://github.com/MReza07/Marketing-Campaign-Performance-Analysis/tree/main/Schreenshots

## 📝 Project Summary

| Section | Summary |
|---|---|
| **Dashboard** | Marketing Campaign Performance Report |
| **Tools** | Power BI, Power Query, DAX |
| **Key KPIs** | Total Campaigns, Average Audience Size, Average Budget, Campaign Success Rate |
| **Business Output** | Marketing campaign performance across multiple dimensions |


Interactive Power BI dashboard with slicers for dynamic filtering

Analysis of campaign success by:

Channel (Email, Radio, Social Media, TV, SMS)

Region (North, East, West, South)

Product Category (FMCG, Finance, Fashion, Electronics)

Budget distribution

Duration (Days)

Time of Year (Q1–Q4)

KPI Cards summarizing:

Total Campaigns

Average Audience Size

Average Budget

Overall Campaign Success Rate

Average Conversion Rate

Average Duration

Previous Engagement Average

## 📈 Key Insights

Email & Radio campaigns delivered the strongest performance.

FMCG category leads with the highest success rate (66%).

Q2 campaigns show peak budget usage and engagement.

North region achieved the highest success rate (67%).

Higher budgets generally correlate with higher campaign success.

## 📁 Project Structure

│── Dataset/

│ └── Marketing Campaign Performance Dataset.xlsx
│
│── PBIX/

│ └── Marketing Campaign project.pbix
│
│── Screenshots/

│ ├── Marketing Campaign Preformance Report.PNG

│ ├── Campaign success By Budget.PNG

│ ├── Campaign success By Channel.PNG

│ ├── Campaign success By Region.PNG

│ └── Campaign success By Budget & time.PNG

└── README.md

## 📐 Sample DAX Measures

```dax
Campaign success = CALCULATE(COUNTROWS(predictive_campaign_success), predictive_campaign_success[Campaign_Success] = 1)

Avg Audience = AVERAGE(predictive_campaign_success[Audience_Size])

Campaign Success Rate = DIVIDE([Campaign success], [Number of Campaign])

## Data Dictionary


| Column Name | Description |
|---|---|
| Campaign_ID | Unique campaign identifier |

| Channel | Marketing channel (Email, Radio, TV, etc.) |

| Audience_Size | Estimated audience reached |

| Budget | Campaign budget |

| Duration_Days | Campaign duration in days |

| Campaign_Success | Binary target (1 = success, 0 = no) |


## 🛠 Tools & Technologies

Power BI Desktop / Service

Data Cleaning & Modeling

DAX Measures

Data Visualization Best Practices

## 📂 How to Open the Report

To explore the Power BI dashboard:

1. Download the PBIX File

Open the Marketing Campaign project.pbix file in the PBIX/ folder

Click Download raw

2. Open in Power BI Desktop

Install Microsoft Power BI Desktop (free)

Open the downloaded .pbix file

3. View Dataset (Optional)

Download the dataset from the Dataset/ folder


## 📜 License

This project is released under the MIT License.

## 📬 Contact

Md. Rezaul Repon
Data Analyst (Power BI | SQL | Python)

🔗 GitHub: https://github.com/MReza07

📧 Email: reazulrepon@gmail.com


