Quantitative Finance Portfolio:

This repository contains independent quantitative research projects completed as part of graduate-level finance coursework. Each project combines Python-based data analysis with investment insight, covering macroeconomic forecasting, equity regression modeling, NLP-driven sentiment analysis, and portfolio performance evaluation.

Projects
1. Economic Forecast & Investment Recommendation
Files: Economic_Forecast_based_Investment_Recs.ipynb · Economic_Forecast_based_Investment_Recs.pdf
Macroeconomic analysis of the US economy used to derive a forward-looking investment recommendation. Covers GDP growth by sector, unemployment and inflation trends, CPI dynamics, and FOMC sentiment analysis using the OpenAI API. Forecasts were generated using ARIMA time-series modeling and Reddit sentiment scraping via the PRAW library.
Key techniques: ARIMA forecasting · FOMC statement sentiment analysis (GPT) · Reddit NLP (PRAW) · GDP sector decomposition · CPI & inflation trend analysis

2. Regression Analysis — SPY vs. AMZN
Files: Regression_Analysis.ipynb · Regression_Analysis_Presentation.pdf
Comparative regression study of Amazon (AMZN) returns against the S&P 500 ETF (SPY). Four regression models — Linear Regression, Huber Regressor, RANSAC, and Theil-Sen — are evaluated on predictive accuracy and robustness. The Huber model is identified as the best-performing estimator (R² = 0.2095, MAE = 0.0727), and its forecasts are used to simulate a trading strategy with Sharpe ratio analysis.
Key techniques: Linear · Huber · RANSAC · Theil-Sen regression · Beta estimation · Sharpe ratio · Strategy backtesting · MAE cross-validation

3. ML-Based Sentiment Analysis — Predicting S&P 500 Direction
Files: Sentiment_Analysis.ipynb · MLbased_Sentiment_Analysis.pdf
Machine learning classification models trained on WallStreetBets Reddit comments to predict next-day S&P 500 market direction (Up/Down). Three methodologies are compared: Naïve Bayes at comment level, Naïve Bayes on daily average sentiment, and a Support Vector Machine (SVM) using bag-of-words features. Naïve Bayes achieves the highest accuracy (~60.8%) with stronger precision than the SVM.
Key techniques: VADER sentiment scoring · Naïve Bayes classification · Support Vector Machine · Confusion matrix analysis · Precision / Recall evaluation · NLP feature extraction4. 

4. Fund Performance & Volatility Analysis — Mutual Funds vs. S&P 500
Files: Fund_Performance___Volatility_Analysis.ipynb
Quantitative performance comparison of eight actively managed mutual funds (SGENX, FAGAX, STAEX, BIAGX, ESEAX, TGVFX, MIGFX, BIAGX) against the S&P 500 Total Return benchmark (^SP500TR) over a 10-year period (2014–2024). Analysis covers historical returns, annualized volatility, Sharpe ratios, rolling correlations, and drawdown analysis to assess whether active management generates alpha over the benchmark.
Key techniques: yfinance data retrieval · Annualized return & volatility · Sharpe ratio · Rolling correlation · Maximum drawdown · Benchmark comparison

About
These projects were completed as part of the MBA Finance curriculum at Baruch College's Zicklin School of Business. They reflect self-directed application of quantitative methods to real financial data, developed alongside formal coursework in Econometrics, Quantitative Modeling, and Corporate Finance.


