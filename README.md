# Predicting Cryptocurrency Price Movement and Market Trends: A Machine Learning Approach using Historical Price Data and News Sentiment Analysis 
This project investigates the prediction of cryptocurrency price movements and market trends by 
leveraging historical price data and sentiment data by sentimental analysis. Focusing on ten 
cryptocurrencies, including Bitcoin, Ethereum, and others, the project employs Random Forest, 
XGBoost, Gradient Boosting, and Support Vector Machine (SVM) algorithms to forecast price 
fluctuations. Drawing inspiration from previous work, the study addresses the volatile and complex 
nature of the cryptocurrency market. By combining sentiment analysis with machine learning, the 
project provides valuable insights for investors and trading firms. SVM exhibited the highest accuracy 
for all cryptocurrencies, which is above 85%. LTC and MATIC provided highest accuracy of 95% for 
SVM model and there is 100% accuracy in SHIB, SVM model bias due to the unbalanced nature of 
the data and the specific behavior of SHIB during the initial period. The findings demonstrate the 
feasibility of accurate price movement predictions, highlighting the potential of these techniques in 
deciphering and forecasting cryptocurrency market dynamics. The project establishes a robust 
foundation for future research in this evolving field. 

<img width="487" alt="Architecture of the Project" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/c5e4c3e7-6f9d-413d-a62e-0fa12da78c34">

## Introduction 
The integration of advanced machine learning techniques has emerged as a powerful methodology for 
predicting cryptocurrency price movement and market trends. This project leverages historical price 
data and sentiment data to provide valuable insights into the cryptocurrency market dynamics. 
Through the application of well-established machine learning algorithms including Random Forest, 
XGBoost, Gradient Boosting, and Support Vector Machine (SVM), the goal is to offer accurate 
forecasts of cryptocurrency price fluctuations. This project addresses a classification problem, 
predicting whether a cryptocurrency's price will increase or decrease based on historical price and 
news sentiment data. Classification involves categorising data into "price increase" or "price 
decrease" classes for each cryptocurrency. These classification algorithms acquire insights from the 
dataset to predict the classification of new and unfamiliar data instances. 
The foundation of this approach draws from the work by (Valencia, Gómez-Espinosa, and Valdés
Aguirre, 2019), demonstrating the viability of machine learning and sentiment analysis in forecasting 
well-established cryptocurrency price movements, such as Bitcoin, Ethereum, Ripple, and Litecoin. 
This breakthrough highlights their potential in addressing challenges within financial time series 
analysis, especially in emerging markets like cryptocurrencies. Combining historical price data from 
Yahoo Finance and cryptocurrency news headlines web scrapped from Google News forms a multi
dimensional dataset for this project. There are 10 datasets of 10 cryptocurrencies which are ADA: 
Cardano, AVAX: Avalanche, BTC: Bitcoin, DOGE: Dogecoin, ETH: Ethereum, LTC: Litecoin, 
MATIC: Polygon (previously known as Matic Network), SHIB: Shiba Inu, SOL: Solana and UNI: 
Uniswap, spanning from January 2021 to February 2023. The significance of sentiment analysis in the 
cryptocurrency market, as highlighted by Oikonomopoulos et al. (2022), emphasises its role in 
influencing price trends. Employing machine learning algorithms, including Random Forest, 
XGBoost, Gradient Boosting, and SVM, represents a sophisticated approach to this predictive task. 
Random Forest's ensemble learning aggregates multiple decision trees to enhance accuracy and 
reduce overfitting. XGBoost and Gradient Boosting utilise gradient descent to iteratively refine 
predictions by minimising errors. SVM, a powerful tool for classification and regression, transforms 
non-linear data into higher-dimensional space to identify decision boundaries, making it an apt choice 
for market prediction tasks. These diverse algorithms collectively address various aspects of the 
intricate cryptocurrency market behavior. As underscored by Kumar et al. (2023), the cryptocurrency 
market's volatility necessitates refined predictive models that offer clear objectives and strategies to 
trading firms. 
The project exemplifies the constructive interaction between different analysis and machine learning 
for predicting cryptocurrency price movement and market trends. By deploying Random Forest, 
XGBoost, Gradient Boosting, and SVM algorithms, the research aims to provide accurate insights 
into the dynamic cryptocurrency domain. The fusion of historical price data and sentiment data 
contributes to our understanding of cryptocurrency price fluctuations, enabling well-informed trading 
decisions and strategic investments.
<img width="483" alt="Techniques" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/e5d40b04-1422-4a86-aca8-82268e280d71">
##  Aims & Objective 
Aim: The aim of this project is to develop a machine learning-based predictive model that accurately 
forecasts short-term cryptocurrency prices movements and identifies market trends through analysis. 
By combining historical price data and news sentiment data, the project aims to provide valuable 
insights for investors and traders in the cryptocurrency market. 
Objective: The objective is to forecast future price movements, identify trading opportunities, and 
gain insights into the dynamics of the cryptocurrency market. By analysing historical trends, 
employing advanced machine learning algorithms, and considering relevant market indicators, the 
project aims to assist investors, traders, and stakeholders in making informed decisions in the 
cryptocurrency domain. 
<img width="505" alt="Problem Statement" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/12e70927-ecd2-4260-ab0a-ab0e7268299f">
## Research Questions 
1. Can the combination of historical price data and news sentiment data accurately predict 
short-term cryptocurrency price movements and identify market trends for a diverse set of 
10 cryptocurrencies from 2021 to 2023? 
2. Can we use news sentiment analysis to get sentiment score is an additional feature to 
improve the accuracy of price predictions? 
3. How accurately can machine learning models forecast cryptocurrency price movements 
using the given dataset? 
4. Are there significant correlations between cryptocurrency prices and news sentiment? 
How does news sentiment affect price trends? 
5. Can machine learning models effectively capture and predict market trends in the 
cryptocurrency market using historical price data? 
6. Which machine learning algorithms perform best in predicting cryptocurrency prices and 
market trends? 
7. How do different cryptocurrencies behave in terms of price movements and market 
trends? Are there any distinct patterns or differences among them? 
8. Can we identify specific news topics or sentiment patterns that have a notable impact on 
cryptocurrency prices? 
9. How does price volatility in the cryptocurrency market vary across different 
cryptocurrencies? Can we predict and model volatility using the available data? 
10. How do different classification techniques, such as of Random Forest, XGBoost, Gradient 
Boosting, and SVM algorithms perform in predicting cryptocurrency prices?

# EDA
<img width="472" alt="Histograms" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/0269a61c-c945-4dc1-9b87-a584c3a3d28f">
<img width="406" alt="heatmap" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/de14272d-ba33-48b4-bb5b-0c72326dc094">
<img width="472" alt="linecharts" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/81c4eb2c-89ed-4628-860e-8ddf409a6180">


# Result
<img width="484" alt="Results" src="https://github.com/Shabeehak/Python-Cryptocurrency/assets/139266524/ac603636-d126-4849-a357-222512e0f201">

## Conclusion 
The project combines historical price data and sentiment analysis to unveil cryptocurrency market 
dynamics. By utilising various exploration techniques and established machine learning methods such 
as Random Forest, XGBoost, Gradient Boosting, and Support Vector Machine (SVM), the project's 
goal is to provide precise forecasts for cryptocurrency price fluctuations. The research spans a wide 
range of questions, encompassing prediction accuracy, news sentiment impact, cryptocurrency 
behavior, and market trends. 
Regression analysis highlights the significance of sentiment scores and trading volume in explaining 
cryptocurrency prices. Volume analysis is used to comprehend market behavior and trends, revealing 
trading volume's stronger influence on price changes. This finding aligns with the project's objectives, 
providing context for the relationship between price movements and trading activity. These outcomes 
underscore the need for tailored strategies for different cryptocurrencies and the potential of ensemble 
techniques for enhancing accuracy. 
The project primarily focuses on classification, predicting price increases or decreases based on 
historical trends and news sentiment data. This involves categorising data into relevant classes for 
each cryptocurrency, enabling algorithms to recognise patterns and forecast future trends. The 
overarching aim is to create a machine learning-based model that delivers accurate short-term 
cryptocurrency price forecasts, with SVM displaying superior performance across all cryptocurrencies 
(more than 85%). By amalgamating historical data and news sentiment, the project strives to provide 
crucial insights for cryptocurrency market participants. Its core objective centers on predicting price 
movements, identifying trading opportunities, and offering a comprehensive understanding of the 
complex dynamics within the cryptocurrency landscape. 
