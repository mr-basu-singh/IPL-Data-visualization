IPL 2022 Data Analysis & Visualization Project
Overview

This project analyzes IPL 2022 match data using Python to extract meaningful insights about team performance, player statistics, toss impact, and match outcomes.
The goal is to transform raw IPL data into clear and interactive visual insights.

Dataset Information
Total Matches: 74
Features: Match details, teams, scores, toss decisions, player performance
Key Columns:
Teams, Venue, Match Winner
Toss Winner & Decision
Runs, Wickets, Margin
Player of the Match
Top Scorer & Best Bowler
Technologies Used
Python 
NumPy
Pandas
Matplotlib
Seaborn
Plotly (Interactive Visualization)
Key Analysis Performed
Team Performance
Most successful IPL team based on wins
Match-winning trends across teams
Toss Analysis
Toss decision patterns (Bat vs Field)
Impact of toss on match outcome (~48.65% correlation)
Match Outcomes
Wins by Runs vs Wickets comparison
Biggest victory margins
Player Insights
Top Player of the Match award winners
Highest individual run scorer in a match
Best bowling performances
Venue Analysis
Most matches hosted by stadiums
Venue-wise match distribution
Key Insights
Toss does NOT strongly guarantee match victory (~48%)
Certain players dominate both batting and awards (e.g., Jos Buttler)
Wankhede Stadium hosted the highest number of matches
Most matches are won by chasing (wickets)
Visualizations

(You should add screenshots here)

Example:

Bar charts for team wins
Toss decision plots
Player performance graphs
🚀 How to Run This Project
git clone https://github.com/your-username/ipl-analysis.git
cd ipl-analysis

Open in:

Jupyter Notebook OR
VS Code / PyCharm (Jupyter extension)

Run:

pip install -r requirements.txt

Then execute notebook step-by-step.

Project Structure
IPL-Analysis/
│
├── IPL.csv
├── IPL_Analysis.ipynb
├── README.md
└── images/
Author

Kumar Basu Singh
B.Tech (EEE), G.L. Bajaj Institute of Technology and Management

📜 License

This project is open-source and available for educational use.
