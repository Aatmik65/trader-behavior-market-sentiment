## Trader Behavior vs Market Sentiment

### Objective
This project analyzes how Bitcoin market sentiment (Fear & Greed) relates to trader behavior and performance using historical trading data.

The goal is to understand whether changes in market sentiment are associated with differences in risk-taking and trading outcomes.

### Datasets
- Historical trader data from Hyperliquid  
- Bitcoin Fear & Greed Index  

### Approach
- Cleaned and aligned trade-level data with daily sentiment data
- Created basic performance metrics such as PnL and win rate
- Analyzed leverage usage and trading activity during Fear and Greed phases
- Performed simple trader segmentation based on cumulative PnL

The analysis is exploratory and focuses on understanding patterns rather than building predictive models.

### Key Findings
- Traders tend to use higher leverage during Greed periods
- Increased leverage during Greed does not consistently improve win rates
- Losses during Greed phases are often larger, indicating higher risk
- Fear periods show relatively more controlled trading behavior

### Limitations
- Sentiment data is available at a daily level, while trades are intraday
- The analysis is observational and does not imply causation
- External market factors are not included

### Project Structure
trader-behavior-market-sentiment/
│
├── Trader_Behavior_vs_Market_Sentiment_Analysis.ipynb
├── README.md
└── data.zip # Contains historical_data.csv and fear_greed_index.csv


### How to Run
1. Clone or download the repository  
2. Unzip `data.zip` to extract the CSV files  
3. Ensure the extracted CSV files are in the same directory as the notebook  
4. Open the notebook and run all cells from top to bottom


### Notes
- This project was completed as part of an internship assignment and reflects my current learning stage as a data science fresher.
- The datasets are zipped due to GitHub file size limitations.
