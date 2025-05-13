# Swift Logistics Delay Analysis Report (2022-2024)

## Overview

This repository contains the **Swift Logistics Delay Analysis Report (2022-2024)**, a comprehensive analysis of shipment delays affecting Swift Logistics, a Third-Party Logistics (3PL) provider. The report examines data from 2022 to 2024 to identify delay patterns, root causes, and actionable strategies to improve operational efficiency and customer satisfaction. It includes detailed findings supported by visual data and a roadmap for implementation.

* **Key Findings**: 42% of all shipments and 50.1% of Express shipments are delayed, driven by systemic planning flaws, route inefficiencies, supplier-side delays, and limited real-time visibility.
* **Recommendations**: Quick wins (e.g., route optimization, supplier timestamp tracking), mid-term initiatives (e.g., predictive maintenance), and long-term strategies (e.g., AI-driven dispatch).
* **Target Audience**: COO, leadership team, and operational stakeholders at Swift Logistics.

## Report Structure

The report is organized into the following sections:

* Executive Summary: Highlights key delay statistics and root causes.
* Company Overview: Background on Swift Logistics and the business problem.
* Data Sources & Methodology: Details on data collection and analysis processes.
* Key Findings: Insights into delay drivers, supported by graphs.
* Recommendations: Actionable steps categorized by timeline.
* Implementation Roadmap: Phased plan with KPIs.
* Risks & Mitigation: Potential challenges and solutions.
* Clarifying Questions for Stakeholders: Open questions for decision-making.
* Assumptions: Underlying assumptions in the analysis.
* Initial Hypothesis: Preliminary hypotheses tested during analysis.
* Definitions: Key terms and delay thresholds.
* Next Steps: Timeline for stakeholder review and action.

## Usage

* **View the Report**: The full report is available as `Report.pdf` in this repository. Open it with any PDF reader to review the detailed analysis and visuals.
* **Access Visuals**: Graphs are embedded in the PDF and linked below for reference. Use these to explore data trends and insights.
* **Collaboration**: Contact the Analytics Team at [analytics@swiftlogistics.com](mailto:itnhamo@gmail.com) for further discussion or to provide feedback.

## Visual Data

The report includes the following graphs to support the analysis:
### Arrival Status by Fatigue Risk (2022-2024)

**Description**: Histogram showing shipment counts by fatigue risk level (High, Medium, Low) and arrival status (Delayed, On Time). High fatigue risk has \~3000 delayed and \~3500 on-time shipments; low risk has \~500 delayed and \~700 on-time.
**Link**: [Arrival Status by Fatigue Risk](images/fatigue chart.png)
**Insight**: Fatigue does not strongly correlate with delays.

![Arrival Status by Fatigue Risk](images/fatigue chart.png)

---

### Average Delay Hours by Incident Type for Express (2022-2024)

**Description**: Bar chart showing average delay hours by incident type (Incidents: 10 hours, Border Issues: 6 hours, Driver Issues: 5 hours, etc.).
**Link**: [Average Delay Hours by Incident Type](images/delay hours.png)
**Insight**: Systemic factors like incidents and border issues drive significant delays.

![Average Delay Hours by Incident Type](images/delay hours.png)

---

### Driver Performance for Express Shipments (2022-2024)

**Description**: Table of driver metrics (e.g., Jennifer Pena: 75% delay rate, 8 trips; Todd Rosales: 62.29% delay rate, 61 trips).
**Link**: [Driver Performance Express](images/drivers table.png)
**Insight**: Express delays are not solely driver-related.

![Driver Performance Express](images/drivers table.png)

---

### Overall Driver Performance (2022-2024)

**Description**: Table of overall driver metrics (e.g., Alexis Baker: 58.06% delay rate, 62 trips; Donald Schultz: 57.01% delay rate, 97 trips).
**Link**: [Overall Driver Performance](images/overall delay.png)
**Insight**: Disconnect between Express and overall delay patterns.

![Overall Driver Performance](images/overall delay.png)

---
## Installation

No installation is required. Simply download the `Report.pdf` file and open it. The images can be viewed directly via the provided links or within the PDF.

## Contributing

* **Suggestions**: Submit issues or pull requests with proposed updates to the analysis or recommendations.
* **Data Updates**: Share additional TMS logs or tracking data with the Analytics Team for future revisions.
* **Contact**: Reach out at [analytics@swiftlogistics.com](mailto:itnhamo@gmail.com) for collaboration.

## License

This report is proprietary to Swift Logistics. Distribution or reproduction requires written permission from the Analytics Team.

## Acknowledgments

* **Analytics Team**: For conducting the in-depth analysis and visualization.
* **Swift Logistics Leadership**: For supporting the project and providing data access.

---

*Last Updated: May 13, 2025, 12:37 PM SAST*
