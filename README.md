# Excel-IPL-Dashboard (2008-2023)

An Excel dashboard analysing every IPL season from 2008 to 2023, covering match results, toss decisions, title winners and Player of the Match awards. Built with Pivot Tables, Pivot Charts and Slicers.

File: IPL-Dashboard.xlsx

---

1. Overview

The dashboard answers questions such as:

- Which teams have won the most IPL titles?
- Do teams bat first or bowl first after winning the toss?
- Which teams have won the most tosses?
- Who has won the most Player of the Match awards?
- Who won each season, and who was Player of the Tournament?

A season slicer filters the dashboard to any IPL edition.

---

2. Dashboard Components

| Visual | Chart type |
|---|---|
| Toss decision split | Doughnut |
| Toss wins by team | Stacked bar |
| Title winners | Bar / Doughnut |
| Player of the Match | Bar / Treemap |
| Season KPI table | Pivot table |
| Season filter | Slicer |

---

3. Key Insights

- 64% of toss winners chose to bowl first, 36% chose to bat first.
- Mumbai Indians won the most tosses (139), then Chennai Super Kings (131) and Kolkata Knight Riders (121).
- Mumbai Indians and Chennai Super Kings have 5 titles each.
- AB de Villiers has the most Player of the Match awards (25), then Chris Gayle (22) and Rohit Sharma (19).

---

4. Workbook Structure

| Sheet | Purpose |
|---|---|
| Dashboard | Final dashboard with charts and slicers |
| Matches_win | Toss wins by team |
| Toss_decision | Bat first vs bowl first share |
| POM_Winner | Player of the Match counts |
| Winner Team | Titles by team |
| KPI | Winner, runner-up and awards by season |
| DATA | Raw match data (1,028 matches, 38 columns) |
| DATA-2 | Season summary lookup |

---

5. Tools

- Microsoft Excel: used to build the whole dashboard
- Pivot Tables: summarise toss, title and award data
- Pivot Charts: doughnut, bar and treemap visuals linked to the pivots
- Slicers: filter every visual by season
- Data Cleaning: prepared 1,028 matches into a main data sheet and a lookup sheet

---

6. How to Use

1. Clone or download this repository:
```bash
   git clone https://github.com/prashantprajapati7476-lang/Excel-IPL-Dashboard.git
```
2. Open IPL-Dashboard.xlsx in Microsoft Excel 2016 or later.
3. Go to the Dashboard sheet.
4. Use the season slicer to filter by season.

---

7. Preview

![IPL Dashboard Preview](https://github.com/prashantprajapati7476-lang/Excel-IPL-Dashboard/blob/main/Snapshort%20of%20the%20IPL-dashboard.png)

---

8. Author

Prashant Kumar
[GitHub](https://github.com/prashantprajapati7476-lang)
