# Monroe Community College Admissions Database

This repository is a starter kit for organizing Monroe Community College (MCC) admissions information. It includes a sample admissions dataset plus a quick FAQ for prospective students.

## What's Included
- **Dataset**: `data/mcc_admissions.csv`
- **Admissions FAQ**: [FAQ.md](FAQ.md)

## Dataset Overview
`data/mcc_admissions.csv` contains sample admissions statistics. You can import it into a database or spreadsheet and expand it with additional years or fields.

**Fields**
- `Year`: Academic year of the admissions cycle.
- `Applications`: Total number of applications received.
- `Admitted`: Number of students admitted.
- `AcceptanceRate`: Percentage of applicants admitted.

```text
Year,Applications,Admitted,AcceptanceRate
2020,12000,7500,62.5%
2021,12500,7800,62.4%
2022,13000,8000,61.5%
2023,13500,8200,60.7%
```

## Usage
1. Download `data/mcc_admissions.csv`.
2. Import it into your preferred tool (Excel, Google Sheets, or a SQL database).
3. Add new columns (program, residency, enrollment, etc.) or new rows for future years.

## Viewable Site
This repo includes a simple static site in `docs/` so the content is easy to preview in a browser.

To view it locally:
1. Run `python -m http.server` from the repository root.
2. Open <http://localhost:8000/docs/> in your browser.

## Brand Guidelines
If you add MCC-branded visuals or messaging, reference the official brand toolkit for approved colors, logos, and usage guidance: <https://www.monroecc.edu/depts/brand-toolkit/>.
