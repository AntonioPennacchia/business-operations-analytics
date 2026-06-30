# 📊 Insurance Claims Volume Monitoring

Business Intelligence dashboard designed to monitor operational volumes across the insurance claims lifecycle.

![Dashboard](overview.png)

---

## Business Context

Insurance companies receive claim assignments throughout the year.

Operational workload naturally fluctuates over time. During peak periods (typically summer months), incoming assignments increase significantly, making it difficult for operational teams to keep pace with assessments and claim closures. During quieter periods, teams progressively recover the accumulated backlog.

This dashboard was designed to monitor these operational dynamics and support workload planning.

---

## Business Process

Each assignment follows three operational milestones.

| Metric | Description |
|--------|-------------|
| **Opened Claims** | New claim assignments received from insurance companies. |
| **Completed Assessments** | Technical inspections completed by adjusters. |
| **Closed Claims** | Claims formally closed after administrative processing. |

These three operational events allow managers to distinguish between incoming workload, completed technical activities and fully processed claims.

---

## Key Features

- Dynamic Reporting Year parameter
- Team filtering
- Quarter and Month filtering
- Total Volume / Daily Average toggle
- Interactive dashboard documentation
- Monthly operational trend analysis

---

## Daily Average View

The **Display Volumes By** selector allows users to switch between **Total Volume** and **Daily Average**, providing both absolute workload and normalized operational trends.

![Daily Average](daily-average.png)

---

## Interactive Filtering

Quarter and Month filters allow users to focus on a specific reporting period, making seasonal trends easier to identify and compare operational performance over time.

![Quarter Filter](quarter-filter.png)

---

## Built-in Documentation

The dashboard includes an integrated information panel explaining the business process, KPI definitions and report usage, allowing new users to quickly understand the solution without requiring external documentation.

![Information Panel](info-panel.png)

---

## Technical Highlights

### Data Model

- Star schema
- Disconnected Calendar table
- Dynamic Reporting Year parameter
- Dynamic DAX measures
- Power Query transformations

### Technology Stack

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## Dataset

The dataset is entirely fictional and was created exclusively for portfolio purposes.

Although simulated, it reproduces a realistic insurance claims operational workflow, including seasonal workload peaks, temporary assessment delays and backlog recovery.

---

## Repository Contents

- `Insurance Claims Volume Monitoring.pbix`
- `insurance_claims_volume_monitoring.xlsx`
- `overview.png`
- `daily-average.png`
- `quarter-filter.png`
- `info-panel.png`
- `README.md`

---

## Disclaimer

This project was created exclusively for educational and portfolio purposes.

All companies, agencies, teams, assignments and operational data are entirely fictional and do not represent any real organization.
