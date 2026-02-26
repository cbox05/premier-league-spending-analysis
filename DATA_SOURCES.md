# Data Sources

## 1. Match-Level Performance Data

**Source:** football-data.co.uk  
**Competition:** English Premier League  
**Seasons Covered:** 2018–19 through 2022–23  
**Format:** CSV files downloaded manually  

### Variables Used

- `HomeTeam`
- `AwayTeam`
- `FTHG` (Full-Time Home Goals)
- `FTAG` (Full-Time Away Goals)
- `FTR` (Full-Time Result)

### Processing

Match-level records were aggregated into season-level performance metrics, including:

- Total Points  
- Goal Difference  
- Goals For  
- Goals Against  
- Final League Position  

---

## 2. Transfer Spending Data

**Source:** Transfermarkt  
**Section Used:** Premier League “Income & Expenditures” tables  
**Seasons Covered:** 2018–19 through 2022–23  
**Format:** Tables manually exported to CSV  

### Variables Used

- `Club`
- `Expenditure`
- `Income`
- `Balance`

### Processing

- Currency values were cleaned and converted to numeric millions.
- Non-numeric characters were removed.
- Club names were standardized to match performance datasets.
- Multi-season spending data was merged into a unified dataset.