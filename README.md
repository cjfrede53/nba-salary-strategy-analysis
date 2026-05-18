# The Price of Winning: NBA Salary Strategy Analysis

A sports analytics research project exploring how NBA teams convert payroll into competitive success across the modern NBA era.

Using salary, performance, and playoff data from the 2015–16 through 2025–26 seasons, this project investigates whether higher spending actually leads to winning — and how roster construction strategy impacts efficiency, playoff performance, and long-term success.

The project combines multi-source web data collection, large-scale data cleaning and transformation, exploratory data analysis, custom salary concentration metrics, and statistical visualization using Python.

---

## Full Report

The complete written report, findings, and visual analysis are included in:

[Research-Report.pdf](./Research-Report.pdf)

---

## Research Questions

This project explores several core questions surrounding NBA payroll strategy:

- Do higher payroll teams win more games?
- Are expensive teams more successful in the playoffs?
- How do teams allocate salary across positions and players?
- Is superstar-heavy spending more effective than balanced roster construction?
- Which teams generate the best value relative to spending?
- What salary and roster-building trends have emerged over the last decade?

---

## Key Findings

### Higher payroll teams generally perform better in the regular season

Across seasons, higher-spending teams tended to post stronger regular season win percentages.

### Spending alone does not guarantee championships

Only a small number of recent NBA champions entered the playoffs with the league’s highest payroll.

### Superstar-heavy teams often outperform balanced rosters

Teams concentrating payroll among top players frequently achieved:

- Higher regular season win percentages
- Lower cost-per-win values
- Greater overall efficiency

### Modern NBA salary allocation has shifted toward guards and versatile forwards

The data reflects increasing league-wide emphasis on:

- Playmaking
- Perimeter scoring
- Multi-dimensional positional versatility

### Successful teams balance elite talent with roster depth

Most championship teams ultimately fell into a middle salary concentration category, suggesting sustainable contention requires both star power and roster balance.

---

## Repository Structure

```text
.
├── README.md
├── Research-Report.pdf
├── data-collection.ipynb
└── data-cleaning-and-visualizations.ipynb
```

### `data-collection.ipynb`

Contains the full data acquisition and preparation pipeline, including:

- Pulling NBA salary and performance data from:
  - HoopsHype
  - ESPN
  - Basketball Reference
- Cleaning and standardizing salary formats
- Resolving inconsistent team and player naming conventions
- Transforming multi-season datasets into analysis-ready tables
- Constructing merged datasets across salary and performance metrics

### `data-cleaning-and-visualizations.ipynb`

Contains the primary exploratory analysis workflow, including:

- Team salary vs. win percentage analysis
- Playoff salary efficiency analysis
- Positional salary trend analysis
- Salary distribution analysis
- Superstar-heavy vs. balanced roster comparisons
- Cost-per-win calculations
- Statistical visualizations and comparative plots

---

## Data Sources

This project integrates public NBA salary and performance data spanning the 2015–16 through 2025–26 seasons using programmatic data collection and transformation workflows.

Primary sources include:

- HoopsHype
- ESPN
- Basketball Reference

---

## Technologies Used

- Python
- pandas
- NumPy
- seaborn
- matplotlib
- Jupyter Notebook

---

## Analytical Techniques

- Exploratory Data Analysis (EDA)
- Data cleaning and transformation
- Multi-source dataset integration
- Statistical visualization
- Salary concentration analysis
- Efficiency metric construction
- Comparative sports analytics research

---

## Example Metrics

### TopHeavyIndex

A custom metric measuring how concentrated a team’s payroll is among its top three highest-paid players.

### Cost Per Win

```python
Team Payroll / Regular Season Wins
```

Used to evaluate organizational efficiency rather than raw success alone.

---

## Authors

- CJ Frederickson
- Athena Wemmert
- Daryn Pham
- Ian Couture
- Nathan Levine
