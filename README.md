
<h1> Stock Price Prediction of Bajaj Finserv </h1>

<h2> About the Company </h2>

>Bajaj Finserv was formed in April 2007 as a result of its demerger from Bajaj Auto Limited to further the Group’s interests in financial services. This demerger enabled Bajaj Finserv to independently run the core businesses of Lending, Protection and savings. Bajaj Finserv Limited is the holding company for the businesses dealing with financial services of the Bajaj Group. It serves millions of customers in the financial services space by providing solutions for asset acquisition through financing, asset protection through general insurance, family protection and income protection in the form of life and health insurance and retirement and savings solutions <br>


__Lending__
Bajaj Finance Limited (BFL), participates in the financial business and is a company listed on The Stock Exchange, Mumbai (the BSE) and the National Stock Exchange (NSE).<br>
BFL also operates through a 100% subsidiary namely, Bajaj Housing Finance Limited (BHFL) which is registered with National Housing Bank (NHB) as a Housing Finance Company (HFC) for its mortgage business. BHFL started its operations in FY2018 and all the incremental mortgage business is now done through BHFL.

__Protection and savings__
These are done through (i) Bajaj Allianz General Insurance Company Limited (BAGIC) for general insurance including health insurance; and (ii) Bajaj Allianz Life Insurance Company Limited (BALIC) for life insurance and retirement plans. BAGIC and BALIC are both unlisted joint ventures with Allianz SE, one of the world’s leading composite insurers.

__Digital and Online Platform__
During the year under review, Bajaj Financial Holdings Ltd., a wholly-owned subsidiary, has firmed up new business plans for undertaking activities on digital and online platform to augment the business of the Company’s subsidiaries and has changed its name to Bajaj Finserv Direct Ltd. with effect from 27 February 2018

In addition, there are wind-farm assets in Maharashtra with an installed capacity of 65.2 MW.


<h2> About the Data </h2>: The data about Bajaj Finserv here is from 26 May 2008 to 30 September 2020.It has been taken from kaggle: https://www.kaggle.com/rohanrao/nifty50-stock-market-data.
The Open and Close columns indicate the opening and closing price of the stocks on a particular day.
<h3>Important Features in the Data</h3>:
1. The Open and Close columns indicate the opening and closing price of the stocks on a particular day.
2. The High and Low columns provide the highest and the lowest price for the stock on a particular day, respectively.
3. The Volume column tells us the total volume of stocks traded on a particular day.
4. The volume weighted average price (VWAP) is a trading benchmark used by traders that gives the average price a security has traded at throughout the day, based on both volume and price. It is important because it provides traders with insight into both the trend and value of a security

<h2> Objective </h2>:
Our objective is to predict the Closing Price of Bajaj Finserv on and after 1 October 2020.

<h2> Methods Used</h2>: 
1. Facebook created an open-sourced package called FBProphet which is used for time series forecasting at a scale with ease.Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.I have used this  method for forecasting the Closing price Bajaj Finserv stock.

2. Secondly I have used ML Models (XGBOOST Regressor)for predicting the Closing Stock prices.For this I took 60 days Closing price as X (independent variable) and Next One day as the y (dependent variable) and repeated this from the entire dataset and then trained the model to predict the y variables from the X variables.So basically it uses the last 60days Closing Price to predict the present Closing Price.
