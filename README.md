# Vibe-Code
# vibe-code

**Personal coding projects & data analysis experiments**  
*Building a portfolio of football analytics, data visualization, and Python projects*

***

## 📊 Direct Freekick Goal Analysis

**Latest project**: Visual analysis of direct freekick goals from football match data.

### What it does
- Loads shot event data from CSV files.
- Filters to **direct freekick goals only**.
- Maps all goals on a **football pitch** using `mplsoccer`.
- **Blue dots** = right-foot goals | **Red dots** = left-foot goals.
- **Arrows** highlight highest/lowest xG (expected goals) freekicks.

### Sample Output
  
<img width="978" height="693" alt="image" src="https://github.com/user-attachments/assets/e7716a64-af42-4320-b89b-c7201ed1e82c" />

***

## 🛠️ Tech Stack

```
Python 3.10+
├── pandas (data processing)
├── matplotlib (visualization)  
├── mplsoccer (football pitch)
├── numpy (numerics)
└── seaborn (styling)
```

Install: `pip install -r requirements.txt`

***

## 📁 File Structure

```
vibe-code/
├── shots.csv          # Shot event data (core dataset)
├── players.csv        # Player stats  
├── teamstats.csv      # Team stats
├── direct_freekicks.py # Main analysis script
├── README.md
└── requirements.txt
```

***

## 🚀 Quick Start

1. Clone repo: `git clone https://github.com/YOURUSERNAME/vibe-code`
2. Update CSV paths in `direct_freekicks.py` to your files.
3. Run: `python direct_freekicks.py`
4. View the pitch visualization!

***

## 🎯 Other Projects Coming Soon

- Football player performance dashboards
- Sports betting xG models
- Custom data scrapers & APIs

***

**Built by Azhi Rasyl | Madrid-based data analyst & football enthusiast**  


***
