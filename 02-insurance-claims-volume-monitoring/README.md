
# 📊 Insurance Claims Volume Monitoring

Business Intelligence dashboard designed to monitor operational volumes across the insurance claims lifecycle.

---

## Dashboard Overview

> 📷 **Insert screenshot here**
>
> `Images/overview.png`

This dashboard provides a centralized view of operational workload by monitoring three key stages of the insurance claims lifecycle.

Managers can quickly understand:

- incoming workload;
- completed technical activities;
- formally closed claims;
- seasonal workload patterns;
- operational performance by Team and reporting period.

---

## Business Scenario

Insurance companies assign claims throughout the year.

Incoming workload is not constant: during peak periods, claim assignments increase significantly, causing temporary delays in assessments and administrative closures. During quieter periods, operational teams recover accumulated backlog.

This report helps operational managers monitor these dynamics and better understand workload distribution over time.

---

## Business Process

Each assignment follows three operational milestones.

| Metric | Description |
|---------|-------------|
| **Opened Claims** | New claim assignments received. |
| **Completed Assessments** | Technical inspections completed by adjusters. |
| **Closed Claims** | Claims formally closed after administrative activities. |

---

## Dashboard Features

- Dynamic Reporting Year selection
- Team filtering
- Quarter and Month filtering
- Total Volume / Daily Average toggle
- Interactive dashboard documentation
- Monthly operational trend analysis

---

## Filtering Example

> 📷 **Insert screenshot here**
>
> `Images/quarter-filter.png`

Quarter and Month filters allow users to focus the analysis on a specific reporting period, making seasonal trends easier to identify.

---

## Dashboard Information

> 📷 **Insert screenshot here**
>
> `Images/info-panel.png`

The dashboard includes an integrated information panel describing the business process, KPI definitions and report usage, allowing new users to quickly understand the solution without external documentation.

---

## Technical Highlights

### Data Model

- Star schema
- Disconnected Calendar table
- Reporting Year parameter
- Dynamic DAX measures
- Power Query transformations

### Tools

- Power BI
- Power Query
- DAX
- Excel

---

## Dataset

The dataset is entirely fictional and was created exclusively for portfolio purposes.

Although simulated, it reproduces a realistic insurance claims operational workflow, including seasonal workload peaks, assessment delays and backlog recovery.

---

## Repository Structure

```text
Insurance Claims Volume Monitoring
│
├── Dataset
│   └── insurance_claims_volume_monitoring.xlsx
│
├── Images
│   ├── overview.png
│   ├── quarter-filter.png
│   └── info-panel.png
│
├── Power BI
│   └── Insurance Claims Volume Monitoring.pbix
│
└── README.md
```

---

## Disclaimer

This project was created for educational and portfolio purposes only.

All data is fictional and does not represent real companies, customers or insurance claims.
