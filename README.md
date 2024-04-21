## Sentiment-enhanced Algorithmic Stock Trading Agent

**Problem Description:** This project aims to develop an intelligent trading agent capable
of making real-time trading decisions informed by both historical market data and
the sentiment derived from financial news and related articles. By utilizing a combination
of sentiment analysis and Optimal Policy Trees (OPTs), we aim to to capture the
sentiment-driven fluctuations in the stock market alongside historical stock behaviour to
optimize investment returns.

**Sentiment Analysis:** The proposed trading agent utilizes market sentiment to improve
decision-making. In order to quantify this sentiment in an effective manner, we developed
a sentiment analysis model. This model utilizes the TextBlob Python library, chosen for
its efficiency in assigning sentiment scores. The model was trained and validated on a
dataset of labelled financial news articles and then run on an extensive dataset of news
related to a chosen set of stocks from Yahoo Finance.

**Prescriptive Analysis using OPTs:** The main aim of the study is to generate intelligent
trading decisions. This is achieved through the use of an optimal policy tree (OPT).
The tree was trained on both historical stock price data and corresponding sentiment
scores. Once trained and validated, the developed model was benchmarked against rulebased
trading decisions. The model was seen to greatly outperform common rule-based
investing methods, and thus cements the importance of using both elements of data for
a holistic representation of market conditions.

**Conclusion:** This is an especially useful application of such machine learning models,
as when combined with sentiment analysis, the obtained strategies can change based on
sentiment-driven market dynamics. The project stands as a testament to the innovative
applications of machine learning in finance, showing potential for the future of algorithmic
trading where data-driven insights and advanced analytics can enable individuals to make
more informed and strategic trading decisions.
