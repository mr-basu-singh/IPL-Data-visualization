# IPL 2022 Data Analysis & Visualization Project

## Overview
This project analyzes IPL 2022 match data using Python to extract meaningful insights about team performance, player statistics, toss impact, and match outcomes.  
The goal is to transform raw IPL data into clear and interactive visual insights.

---

## Dataset Information
- Total Matches: 74
- Features include:
  - Match details (teams, venue, date)
  - Scores and wickets
  - Toss decision and impact
  - Player performance data
  - Match winner and margin

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly (for interactive visualization)

---

## Project Structure

IPL-Analysis/
│
├── IPL.csv
├── IPL_Analysis.ipynb
├── README.md
└── images/


---

## Key Analysis Performed

### Team Performance Analysis
- Most successful IPL teams based on wins
- Match-winning trends across teams

### Toss Analysis
- Toss decision trends (Bat vs Field)
- Toss impact on match results (~48.65%)

### Match Outcome Analysis
- Wins by Runs vs Wickets
- Largest victory margins

### Player Performance Analysis
- Most Player of the Match awards
- Highest individual score in a match
- Top scorers in IPL 2022

### Bowling Performance Analysis
- Best bowling figures analysis
- Top wicket takers across season

### Venue Analysis
- Stadium-wise match distribution
- Most matches hosted by venue

---

## Key Insights
- Toss does not strongly guarantee winning (~48% correlation)
- Chasing (winning by wickets) is slightly more common
- Jos Buttler and Quinton de Kock were top-performing batsmen
- Wankhede Stadium hosted the highest number of matches
- Multiple bowlers delivered 5-wicket performances

---

## How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/ipl-analysis.git
cd ipl-analysis
2. Install dependencies
pip install numpy pandas matplotlib seaborn plotly
3. Run notebook

Open the notebook using:

Jupyter Notebook
VS Code (Jupyter extension)
PyCharm (Jupyter plugin)

Run all cells step by step.

Sample Code Libraries Used
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
from plotly.offline import iplot
import warnings
warnings.filterwarnings("ignore")
Author

Kumar Basu Singh
B.Tech (EEE)
G.L. Bajaj Institute of Technology and Management

License

This project is open-source and free to use for learning purposes.


---

If you want next improvement, I can help you:
- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}
- :contentReference[oaicite:2]{index=2}
