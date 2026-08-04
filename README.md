# Finance/Data Science Portfolio

#### Technical Skills: Python, SQL, AWS, Docker, Tableau, Airflow, Google BigQuery, Google Earth Engine, Geospatial Analysis (GIS/TIGER), Statistical Modeling (Logistic Regression), Quantitative Factor Modeling (Compustat/CRSP)

## Education
- M.S., Finance	| UCSD (_December 2026_)	 		
- M.S., Data Science	| Johns Hopkins University (_August 2024_)	 			        		
- B.S., Industrial Engineering Operations Research | University of California Berkeley (_May 2022_)

## Work Experience
**Finance and Accounting Extern @ Equity Methods LLC (_March 2026_)**
- Accepted into the competitive Spring 2026 Externship at Equity Methods, a nationally recognized consulting firm specializing in stock-based compensation (SBC) valuation and financial reporting.
- Modeled forecasting and budgeting scenarios for stock-based compensation expenses on behalf of a Fortune 100 client company, applying ASC 718 equity
compensation accounting frameworks.
- Gained exposure to equity-based compensation accounting. Experience with technology-driven analytics and consulting workflows in a two-day intensive.
- Networked with senior consultants and partners across Equity Methods’ nationally recognized practice.
  
**Data Scientist @ HelloSky AI (_June 2025 - August 2025_)**
- Improved business insights, increasing customer engagement through enhanced usage metrics in reporting dashboards.
- Improved decision support quality and organized three-tier information workflow by optimizing data management processes.
- Enhanced entire company Streamlit application to seamlessly navigate API endpoints usage.
- Helped create closing pitches for converting trial to yearly subscription customers.

**Associate Product Manager @ Visa (_August 2022 - June 2023_)**
- Created new Visa Direct Highspot learning repository for internal employees and increased employee satisfaction for accessing Highspot resources by 80%
- Performed market landscape research for Visa Consulting Analytics sustainability clients and improved client sentiment with Visa Product Design team by 80%

**Retail Data Analytics Intern @ Samsung Electronics America (_June 2021 - August 2021_)**
- Analyzed user traffic datasets using advanced statistical modeling in Python resulting in actionable insights for leadership team helping retail and carrier stores sell 75% more product to customers post-pandemic
- Developed customer demographics dashboard using data visualization techniques on Tableau to indicate ethnic groups and regions purchasing Samsung Mobile products and received 95% approval from Samsung retail analytics senior executives

**Data Science Intern @ Takeda (_May 2020 - August 2020_)**
- Developed Artificial Intelligence application by utilizing Pandas Profiling, Flask, Python, and JavaScript to easily handle any complex pharmaceutical datasets allowing users to perform deep dive analyses
- Contributed to optimizing speed and efficiency of exploratory data analysis through web application by 65% to facilitate Data Scientists across Takeda Global

**Data Science Researcher @ UC Berkeley IEOR Department (_January 2020 - May 2020_)**
- Resolved programming problems by using Python toolkit under supervision of Professor Anil Aswani in evaluation of ML bias. Maximized fairness and limited bias through multiple optimization techniques by implementing loss function by 75%
- Developed and implemented efficient SVM, Random Forest, Clustering, linear regression, and decision tree Algorithms for resolution of unique optimization problems

## Projects
### Quality Minus Junk: A Systematic Multi-Dimensional Quality Factor for U.S. Large-Cap Equities (_May 2026_)
[Project Writeup](https://drive.google.com/file/d/1f4rdDDNB_ntwwZ0x0KKiEw5bAiXf0viP/view?usp=drive_link)

This project tests the Quality Minus Junk (QMJ) factor, built on the three-pillar framework of profitability, growth, and safety from Asness, Frazzini, and Pedersen, against a point-in-time S&P 500 universe of 491 constituents from June 2016 through December 2025. Using Compustat, CRSP, and Yahoo Finance data run through a six-step signal pipeline (winsorize, rank z-score, sub-composite formation, re-standardization, composite scoring, and monthly decile sorting), the analysis finds that the classic D10-minus-D1 long-short spread earned only a weak 1.71% annualized return with an Information Ratio of 0.14, while an alternative "Upper Quality" long-only strategy targeting Deciles 7 through 9 substantially outperformed at 16.35% annualized with an IR of 1.02, suggesting the market already prices in the very highest-quality names. Results varied notably by sector, with Consumer Defensive the only sector approaching statistical significance and Technology and Utilities showing a negative quality signal. The team's self-critique flags two limitations: a one-year (rather than five-year) growth-pillar specification that adds noise, and a 2016–2025 sample period spanning unusual macro regimes, including COVID-era intervention, that aren't ideal for testing defensive quality factors, both of which the team notes as areas for future refinement.

### Mortgage Repayment Risk in California (_May 2026_)
[Project Writeup](https://drive.google.com/file/d/1PCeFzkbxlxv-F2ojPtMejfEAFyc_WO1i/view?usp=drive_link)

This project integrates 2016 California mortgage origination data from Freddie Mac and Fannie Mae (roughly 683,000 loans) with satellite-derived wildfire observations from the MODIS Active Fire Product, linking the two through census tract and ZIP-code boundaries via a tract-to-ZIP crosswalk. Using Google BigQuery for data processing and Google Earth Engine for wildfire detection, the analysis constructs a mortgage-stress indicator, stressed_at_origination, based on risk markers such as high-cost lending, cash-out refinancing, non-owner occupancy, and manufactured housing, then tests whether ZIP-level wildfire exposure (fires_2016) is associated with this stress measure using logistic regression. The model, which achieved an ROC-AUC of approximately 0.61, found only a modest relationship between wildfire activity and mortgage stress at origination, but it demonstrates that environmental exposure can be systematically incorporated into mortgage-risk analysis alongside traditional borrower and loan characteristics. Rather than a predictive tool, the project serves as a proof of concept for climate finance research, showing that publicly available satellite and geographic data can be integrated with financial records to explore, though not establish causally, the connection between wildfire risk and housing finance stress in California.

### Guest Moderator, Analytics Careers Panel (StepStone) (_May 2026_)

Moderated a panel titled "Insights from Analytics Careers," featuring two StepStone alumni from the 2025 MQF cohort who shared their experiences in financial and investment analytics. Guided the discussion through career paths, day-to-day responsibilities, and key skills for success in the field, and facilitated Q&A to keep the conversation engaging for MQF and MSBA students in attendance. The session concluded with an open networking segment connecting students directly with the panelists.

### Predicting NYC UHI Index (_March 2025_)
[Project Code](https://drive.google.com/file/d/1DgrDZFYBL6a9KiexoESCSOiYg3g7396o/view?usp=sharing)

Predicting UHI Index using Sentinel 2 and Landsat 8 satellite data bands using Planetary Computer API. All work was done using Python and Pandas using Random Forest Regression for prediction. Experimenting with different training test splits to improve test and validation accuracy from 70/30 split to 90/10 split. 

### NYPD Arrests Deep Dive (_August 2024_)
[Presentation](https://drive.google.com/file/d/1NDojpCKFzszMLg_TfjAVSuB4iKruAN0T/view?usp=sharing)

Finding key drivers on NYC arrests by discovering noticable increase of arrests by borough, offense type, ethnicity, and age groups. We synthesized all of our findings into a **Tableau** dashboard, so we can better inform the NYPD how to better equip themselves to reduce crime. Our recommendations involve a collective effort in improving officer training and gain better understanding of NYC regulations. 

![Dashboard](/assets:img/screenshot.png)

### End-to-End Data Pipeline for State Economic Metrics (_August 2024_)
[Project Zip](https://drive.google.com/file/d/1LhRFiPbAZLURcl7AU4CpKCHou0HSRxYF/view?usp=sharing) | [Documentation](https://drive.google.com/file/d/1Uj8wresM191eU_76C5pcWprG90o5tnTr/view?usp=sharing)

The purpose of this data pipeline project is to streamline the integration, processing, and analysis of economic datasets from various sources like the USDA Economic Research Service and Kaggle. The project aims to deliver a self -contained data pipeline that can be deployed effortlessly using **Docker**. It automates data ingestion, transforms datasets with Airflow, and stores results in **SQL**. The documentation covers dataset descriptions, normalization into 11 tables, and the generation of pandas profiling reports for comprehensive data exploration. The architecture includes stages for data loading, transformation, and storage, with **Airflow** managing ETL tasks and PostgreSQL serving as the database backend.

### Crypto Coin Prediction using Neural Networks (_May 2024_)
[Dataset](https://www.kaggle.com/datasets/olegshpagin/crypto-coins-prices-ohlcv) | [Project Zip](https://drive.google.com/file/d/1sNN--vGXtgjKwL6jPsQBAvSiKlCBXa6d/view?usp=sharing) | [Presentation](https://docs.google.com/presentation/d/1P0VGm3m4luplThVDgFFC4JXrKGQ8wsWX/edit?usp=sharing&ouid=107641025095273989713&rtpof=true&sd=true)

The goal of the project is to predict daily Bitcoin prices leveraging deep learning models learned in the Johns Hopkins Neural Network course. Research was performed into 7 different types of datasets: weekly, hourly, and daily changes. The dataset overall contains 234 Crypto Coins/Altcoins with historical Open, High, Low, Close, and Volume (OHLCV) prices traded in the Binance Exchange. 
Our project group chose D1 as a group since there includes more data for the daily scale and can provide high capabilities for prediction. The networks used were RNN, LSTM and GRU to compare model performance and accuracy. 


### Modeling Stock Market Behavior (_May 2024_)
[Project Code](https://github.com/arag1/Stock-Price-Markov-Model)

The goal of the project is to build a model of how stock prices vary year over year. In order to do this, our team built a Markov chain using a stationary distribution with historical price information. Then, we compare the distribution of the Markov chain with the distribution of the test set of stock prices. This method was developed in a previous study in 2011.  The data used was the closing prices of each Dow Jones Industrial average member from 2014-2019. This generates 1007 points per symbol. Overall, there are 30 symbols within Dow Jones. This was used as a reference to produce the stationary distribution of the Markov chain. We used this stationary distribution to project the stocks for 2023-2024.

### Credit Card and Fico Score Exploration (_April 2023_)
[Deliverable](https://drive.google.com/file/d/1sADmVuHuSJw_7KzKdRz-C0D_lLVpEXWP/view?usp=drive_link)

Used **Python** to explore patterns between FICO scores and credit cards. From the analysis portion, Visa and MasterCard are the top two companies that authorize the highest amount of credit limit for their clients. Most middle class workers owning less than 3 credit cards have an average FICO score of 800+. Addditional steps that would be taken to further improve this project are looking at other variables, such as ethnicity, location, and education to further gain clarrification on if there is a correlation between the number of credit cards and FICO score.




