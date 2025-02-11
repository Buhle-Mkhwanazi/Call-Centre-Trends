# Call Centre Trends Analysis

## Background and Overview

PwC aims to enhance its call centre operations by gaining data-driven insights into customer interactions and agent performance. The goal of this project is to develop a dashboard that provides a clear and actionable overview of key performance indicators (KPIs), allowing stakeholders to improve customer satisfaction, optimize agent efficiency, and reduce call abandonment rates.

## Data Structure Overview

The dataset consists of call centre interaction records, including the following fields:
- Call Details: Call ID, timestamp, duration, resolution status, and customer satisfaction score.
- Agent Performance: Agent name, total calls handled, call abandonment rate, speed of answer, and resolution rate.
- Customer Feedback: Categorization of calls based on satisfaction levels.
- Time-based Trends: Call volume distribution by hour, date, and weekday.

## Executive Summary

### Overview of Findings
- Call volume is steady but peaks during specific hours (likely mid-morning and early evening).
- The overall call abandonment rate is 18.92%, which may indicate inefficiencies in response time.
- Agent performance varies significantly, with resolution rates ranging from 39.36% to 90.64%.
- Customer satisfaction (CSAT) is 68.07%, suggesting room for improvement in service quality.
- Average handling time is 182.37 seconds, which may impact customer experience.

Below is the overview page from the Power BI Dashboard. The entire interactive dashboard can be downloaded [here]()

### Dashboard
![Call Centre Trends Dashboard](https://github.com/Buhle-Mkhwanazi/Call-Centre-Trends/blob/main/Call%20Centre%20Trends%20Dashboard.png?raw=true)

### Insights Deep Dive
- Agent Performance Variability:
  - Agents like Greg and Stewart have high resolution rates (90%) and above-average CSAT (68%), while others, such as Becky, have significantly lower resolution rates (~39%).
  - High call abandonment rates among some agents indicate possible training gaps or workload distribution issues.
- Call Volume and Timing:
  - Peak hours between 10 AM - 5 PM show increased call volume, suggesting the need for optimized staffing.
  - Friday and Saturday exhibit the highest call activity, indicating higher demand on these days.
- Customer Satisfaction Levels:
  - A significant portion of customers report neutral or dissatisfied experiences, which impacts CSAT.
  - The Not Served category represents a concerning volume of interactions that did not lead to resolution.
 
### Recommendations:

Based on the uncovered insights, the following recommendations have been made:
- Optimise Staffing: Increase the number of active agents during peak hours to reduce wait times and abandonment rates
- Agent Training: Focus on improving resolution rates and response times for agents with lower performance metrics.
- Reduce Call Handling Time: Streamline call processes and scripts to ensure quicker resolutions.
- Enhance Customer Experience: Implement callback options or virtual assistants to handle common queries, reducing customer frustration.
- Monitor Peak Hours: Adjust schedules based on call volume trends to optimise efficiency.

 
