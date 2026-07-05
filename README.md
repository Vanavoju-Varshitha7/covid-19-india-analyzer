# COVID-19 India State-wise Analyzer

## About
End-to-end analysis of India's COVID-19 state-wise data
using NumPy and Pandas — no visualization libraries used.

## Dataset
Source: Kaggle — COVID-19 India dataset by Dhamodharan R
Rows: 36 states/UTs | Columns: 9

## Key Findings
1. Maharashtra had highest total cases — contributing ~17% of India's total
2. India's national recovery rate is 98.81%
3. Punjab had highest Case Fatality Rate at 2.69% — double the national average
4. Mizoram and Arunachal Pradesh managed best with lowest CFR values
5. Strong correlation (r > 0.9) between cases and deaths across states

## Analysis Performed
- National totals using NumPy (sum, mean, std)
- Case Fatality Rate (CFR) per state
- Recovery Rate ranking of all 36 states
- Outlier detection using IQR method
- Cases per million population analysis
- Correlation between cases and deaths

## Tools Used
- Python 3
- NumPy
- Pandas
- Google Colab

## How to Run
1. Open Google Colab (colab.research.google.com)
2. Upload the .ipynb file
3. Upload the dataset CSV
4. Run all cells top to bottom

## Author
Varshitha — B.Tech Data Science, Vignan Institute of Technology and Science
