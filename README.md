# 🧠 Correlation Analysis Between Closing and Opening Prices

This project explores the **correlation between the opening and closing prices** of a financial asset using historical data. The aim is to analyze the statistical relationship between these two variables through **normalization**, **visualization**, and **correlation analysis**.

## 📁 Repository Contents

- `analyse-de-la-corr-lation-entre-le-prix-de-fermeture.ipynb`  
  Jupyter notebook containing the full analysis and visualizations (written in R).
- `README.md` This documentation file.
-  Dataset  The dataset used is stored in `NASDAQ.csv` and contains 250 rows of historical NASDAQ market data, with the following columns:

| Column      | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `Date`      | The trading date (format: YYYY-MM-DD)                                       |
| `Open`      | The opening price of the NASDAQ index on that day                           |
| `High`      | The highest price reached during the trading day                            |
| `Low`       | The lowest price during the trading day                                     |
| `Close`     | The final closing price at the end of the trading day                       |
| `Adj Close` | Adjusted closing price (corrected for dividends and stock splits)           |
| `Volume`    | Number of shares traded (daily trading volume)                              |

## 🛠️ Technologies Used

- **R** via Jupyter Notebook (`IRkernel`)
- R packages:
  - `ggplot2` for data visualization
  - `dplyr` for data manipulation
  - `corrplot` for displaying correlation matrices
  - `caret` (if applicable) for data preprocessing

## 📊 Methodology

1. **Data import and cleaning**
2. **Normalization** of `open` and `close` columns
3. **Visualization** (scatter plots, histograms, etc.)
4. **Pearson correlation** computation
5. **Interpretation** of statistical findings

## 📝 Key Findings

- A strong positive correlation was observed between opening and closing prices.
- Normalizing the data helped better visualize and compare the variables.
- Multiple plots were used to illustrate patterns and relationships.

