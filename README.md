# Gender Differences in Executives’ Corporate Decision-Making in the Covid-19 Pandemic

## INTRODUCTION
This repository presents our analysis of gender differences in executives’ corporate decision-making during the Covid-19 pandemic.

In this study, we examine gender differences in executives’ corporate decision-making during the Covid-19 pandemic. According to previous research, women generally take fewer risks when making financial decisions, but they also tend to be more resilient to stress than men. The recent Covid-19 global pandemic adversely affects many industries, which provides us with the opportunity to investigate gender differences in corporate decision-making under risky, uncertain, and stressful conditions. We gathered corporate and executive data of U.S. publicly listed companies between 2016 and 2021 and applied the panel data analysis method to explore gender differences in corporate decision-making during the pandemic. The results indicate that, surprisingly, companies with more female executives tend to make more risky corporate decisions and are less affected by Covid-19. We further discuss the policy, management, and social implications of our research, as well as limitations and future directions.


## CONTENT
- [LitReview.xlsx](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/LitReview.xlsx): a spreedsheet listing our literature review results.
    - Sheet *Literature*: key information of important literature to this research.
    - Sheet *Useful*: main literature under each aspect of corporate decision-making (risk-taking, cash holdings, innovation) discussed in this research.
    - Sheet *Variable*: key variables that should be obtained from WRDS database for analysis.
- [Data](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Data): the data folder contains both raw data constructed from WRDS database and the dataset used for regression analysis after pre-processing.
    - [Executive.csv](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Data/executive.csv): raw executive data obtained from [Execucomp](https://wrds-www.wharton.upenn.edu/pages/get-data/compustat-capital-iq-standard-poors/compustat/execucomp/annual-compensation/) (a database including information about public companies’ executives in the United States).
    - [Corporate.csv](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Data/corporate.csv): raw corporations’ financial data obtained from [Compustat](https://wrds-www.wharton.upenn.edu/pages/get-data/compustat-capital-iq-standard-poors/compustat/north-america-daily/fundamentals-annual/) (a market and corporate finance database on global companies).
    - [Stock.csv](https://drive.google.com/file/d/1slPZGJxyjTwm8nJsIvJaeyKdDaf0Yazw/view?usp=sharing): raw data of different corporations' daily stock obtained from [CRSP US Stock Database](https://wrds-www.wharton.upenn.edu/pages/get-data/center-research-security-prices-crsp/annual-update/crspcompustat-merged/security-monthly/) (a comprehensive database containing market and corporate action data for over 32,000 securities).
    - [Volatility.csv](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Data/volatility.csv): volatility data of each corporation calculated from the above raw data.
    - [Merged.csv](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Data/merged.csv): the output dataset after pre-processing and merging the above raw data. Will be utilized in regression analysis.
- [DataProcessing.ipynb](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/DataProcessing.ipynb): the Python code of pre-processing the raw data with annotation.
- [Regression.R](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/Regression.R): the R code of conducting regression analysis with annotation.


## SENIOR CAPSTONE REPORT
The research presented on the repo pertains to our senior capstone project in Data Science at NYU Shanghai during Fall 2023. Read the full [report](https://github.com/koapushjin/Spring2023-DS-capstone/blob/main/CapstoneReport.pdf) here.


## AUTHOR
- Tian JIN (tj1059@nyu.edu)
- Yumeng CHEN (yc4144@nyu.edu)


## ACKNOWLEDGEMENT
We thank Professor Li Guo, Guodong Chen and Yu Zhou for their guidance throughout the project. We thank Professor Olivier Marin for his help in reviewing this repo.
