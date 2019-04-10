# Twitter-moods-as-stock-price-predictors-on-Nasdaq
Although news most certainly influence stock market prices, public mood states or sentiment may play an equally important role. We know from psychological research that emotions, in addition to information, play a significant role in human decision-making. Behavioral finance has provided further proof that financial decisions are significantly driven by emotion and mood. It is therefore reasonable to assume that the public mood and sentiment can drive stock market values as much as news. As far as tweets go, some interesting discoveries have already been made. I also wanted to investigate this, and made some interesting discoveries!

Hypothesis:
Tweets today with a positive or negative sentiment and containing one or several cashtags can affect the way a stock moves tomorrow. If negative sentiments dominate today, the stock price is expected to fall tomorrow, and rise after positive sentiments. The number of followers a Twitter account has is also a dominating factor. The more followers, the more influential the tweets, and the more impacts on the stock price.

PLEASE NOTE ONE THING ABOUT THE NOTEBOOKS: The dataframes contain also a lot of columns not used in the actual binary classification analysis, where only two features were relevant; 'Pct_daily_change' and 'Compound_multiplied' (=the x:s) and 'Buy/Sell' (=the y).
