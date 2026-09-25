
## Updated README.md

```markdown
# S&P 500 Stock Price Analysis (2014–2017)

Analysis of daily stock prices for S&P 500 companies from 2014 to 2017, aimed at identifying which stocks perform best on price and which perform best on trading volume, including a year-wise breakdown.

## Dataset

- **Source file:** `data/S&P+500+Stock+Prices+2014-2017.csv`
- **Records:** 497,472 rows
- **Stocks:** 505 S&P 500 companies
- **Period:** 2 January 2014 – 29 December 2017
- **Columns:** symbol, date, open, high, low, close, volume

## Tools Used

- **Power Query** – data cleaning and transformation
- **Tableau** – data visualization and analysis

## Objective

- Identify the best-performing stock overall.
- Compare stocks on price (Open, High, Low, Close) and on trading Volume.
- Find the leading stock in each year from 2014 to 2017.

## Methodology

1. Backed up the raw CSV and stored working copies separately.
2. Cleaned and transformed the data in Power Query (checked for missing values, duplicates, and logical errors such as High < Low).
3. Built visualizations in Tableau for Open, High, Low, Close and Volume totals by stock.
4. Compared results year by year to find yearly leaders.
5. Drew conclusions and recommendations based on the findings.

## Dashboard

[Tableau Dashboard](image/Dashboard.png)

## Key Findings

- **PCLN** ranks first on Open, High, Low and Close totals in every year — but this is because of its high share price, not necessarily the strongest growth.
- **BAC** ranks first on trading Volume in every year, by a wide margin.
- PCLN does not appear among the top stocks by Volume at all.

## Recommendation

- If price level matters most: **PCLN**
- If trading volume / liquidity matters most: **BAC**
- The dataset ends in 2017, so more recent data should be checked before making any real investment decision.

## Limitations

- Data covers only 2014–2017 and does not reflect current market conditions.
- Analysis is based on price and volume only; company fundamentals and news events are not considered.
- This project is for practice/portfolio purposes and is not financial advice.

## Files in This Repository

| Folder | Contents |
|---|---|
| `data/` | Source CSV file |
| `docs/` | Change Log and Documentation (Word files) |
| `image/` | Tableau dashboard screenshot |
| `presentation/` | Summary slide deck (PowerPoint) |
| `visualization/` | Tableau workbook (.twb) |

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details. The underlying stock price data is publicly available market data.

## Author

Sidhant Negi
```
