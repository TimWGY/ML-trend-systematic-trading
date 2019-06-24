# ML Trend Systematic Trading
A <b>machine learning based systematic trading system</b> that combines the popular <b>trend-following</b> strategy and <b>counter-trend</b> strategy. Aiming at <b>capturing the long uptrends</b> and <b>avoiding unexpected drawdowns</b> in crisis. This is a project done by Tim (Wu Guangyu) and Mandy (Guo Lu) for the <b>Systematic Investing</b> course at NYU Stern School of Business under Professor Vasant Dhar.
<br><br>
The final model of ours proves to be moderately successful with <b>S&P 500 futures</b> after backtesting with the data in <b>past 20 years</b>. It strikes a balance between profit-taking during uptrends and loss-avoidance during crises. For more information, the PDF file in this repo is the <b>final report</b>, which discusses the project ideation, methodology, and results.
<br><br>
The code files include two parts:
<br>
1. 'Signal Generator' takes in raw data (S&P_Futures_data.csv in this case) and create an intermediate data file with various signals.
<br><br>
2. 'Trading Model' takes in the output file of Signal Generator and makes actual trading decisions and generates outputs. Performance analysis is in this file as well.
<br><br>
The intermediate file is created and included in this folder, so the 'Trading Model' notebook can be run directly without running the 'Signal Generator'.


