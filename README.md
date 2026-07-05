# Project-no.-2-(https://colab.research.google.com/drive/1HAle485lfAZSFyJsy3mjxBzcmKPRfOXK?usp=sharing) colab link
# Bank Transaction Analysis using Python

Analyze six months of bank transaction data to uncover spending patterns, monthly trends, anomalies, and user spending archetypes using Python, Pandas, and NumPy.

## Output Screenshot

> Add a screenshot of your final output here.
>
> Example:
> - Spending overview
> - Monthly trend analysis
> - Time-of-day heatmap
> - Spending archetypes
> - Anomaly detection

## Constraints

- Implemented using only Python, Pandas, and NumPy.
- No SQL or external databases.
- Vendor names extracted from messy transaction descriptions using dictionary mapping.
- Categories assigned using dictionary mapping with `fillna("Uncategorized")`.
- Monthly trends computed using `groupby()` and `pivot_table()`.
- Time-of-day analysis performed using transaction hour extraction.
- Anomaly detection implemented using category-wise Z-score.
- Spending archetypes detected using rule-based logic.

## How to Run

1. Clone this repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy
   ```
3. Place the bank transaction CSV file in the project folder.
4. Open the Jupyter Notebook or Google Colab notebook.
5. Run all cells from top to bottom.
