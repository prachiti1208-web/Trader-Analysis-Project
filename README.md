# Trader-Analysis-Project

##  Project Overview
This project analyzes trader behavior using sentiment (Fear vs Greed) and trading features (win rate, long/short bias, leverage proxy).  
The goal is to understand how market sentiment and leverage affect trader performance, and to propose practical strategy ideas.

##  Contents
-script.pdf → Python script with all code and charts  
-analysis.pdf → Polished report with insights and strategies  
-output/ → Saved plots 

##  Key Insights
1. **Win Rate by Sentiment** → Traders perform better on Fear days than Greed days.  
2. **Directional Bias** → Greed days show more long trades, Fear days show more shorts.  
3. **Leverage Impact** → High leverage traders have more extreme PnL outcomes.  

##  Strategy Ideas
- Reduce leverage on Greed days to avoid volatility.  
- Align trade direction with sentiment bias but limit trade frequency on Greed days.
- 
##  How to Run

1. Make sure you have **Python 3.x** installed on your system.  
   - You can check by running:
     ```bash
     python --version
     ```

2. Install the required libraries (if not already installed):
   ```bash
   pip install pandas matplotlib seaborn
3. Clone this repository:
bash
git clone https://github.com/your-username/trader-analysis.git
cd trader-analysis

4.Run the analysis script:
bash
python analysis.py

5.The script will generate charts and analysis results.

Charts will either display in a window or be saved as image files (depending on the code).
For a polished summary, open analysis.pdf included in this repo.
