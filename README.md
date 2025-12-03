# Think_Schook_Analysis
I have tried to scrape and analyse the public data of Think School.

# Think School – YouTube Data Analysis Project
A complete end-to-end data scraping, cleaning, analysis, and dashboarding project.

This repository contains an in-depth analysis of the public data from Think School’s YouTube channel, covering:
Shorts
Podcasts
Long-form Case Studies

The purpose of this project is to study content performance, understand audience behaviour, identify hidden patterns, and generate actionable insights that can support content strategy and growth planning.

This analysis was conducted independently as a learning + portfolio project in data analytics, visualisation, NLP, and content strategy.

### Repository Structure
Think_School_Analysis/
│
├── dashboards/            → Power BI dashboards for Shorts, Podcasts, Case Studies, and overall channel.
│
├── data/                  → Cleaned CSV datasets used for analysis.
│
├── notebooks/             → Jupyter notebooks with:
│      - Data cleaning
│      - Feature engineering
│      - Visualisations
│      - Insights generation
│
├── scraping/              → YouTube API scraping notebook (API key hidden via .gitignore).
│
├── report/                → Main report + 3 deep-dive reports (Shorts, Podcasts, Case Studies).
│
├── .gitignore             → Ensures API keys and sensitive files remain private.
│
├── README.md              → Project documentation (this file).
│
└── Think_School.ipynb     → Combined analysis notebook (final compiled version).

### Project Goals
1)Scrape Think School's public YouTube data via YouTube Data API
2)Clean and transform raw data for analysis
3)Perform exploratory data analysis (EDA) across all 3 content types
4)Build month-wise, duration-wise, and engagement-wise insights
5)Identify top-performing formats and themes
6)Create interactive dashboards to visualise trends and patterns
7)Present findings in structured, professional reports

### Key Features
#### Data Scraping
Used the YouTube Data API v3
Extracted metadata including:
view_count, like_count, comment_count, duration, publish date, titles, etc.

#### Data Cleaning & Feature Engineering
Converted ISO timestamps
Extracted year–month
Parsed durations into seconds/minutes
Removed Shorts from long-form dataset
Created engagement metrics

#### Visual Analysis
Includes:
Duration vs Engagement
Month/Year-wise performance
Rolling averages
Distribution plots
Heatmaps
Upload frequency

#### Dashboards
Four separate Power BI dashboards:
Overall Channel Overview
Shorts Dashboard
Podcast Dashboard
Case Study Dashboard

#### Reports
Main Summary Report (5 pages)
Detailed Shorts Analysis
Detailed Podcasts Analysis
Detailed Case Study Analysis

#### Insights Summary (Examples)
60-second Shorts consistently achieve the highest engagement
Geopolitical case studies dominate the Top 10 most viewed videos
Podcast viewership peaks during vacation months
18–22 minute case studies perform the best among long-form videos
(Full insights are available in the reports/ folder.)

### API Key Security
This project uses a config.py file to store the YouTube API key.
The file is NOT included in version control (protected via .gitignore).

This ensures:
No sensitive information is exposed

The repository remains safe for public sharing

### Tech Stack
Python
pandas
matplotlib
seaborn
google-api-python-client
Power BI 
Jupyter Notebook
GitHub 

### How to Use This Repository
Clone the repository
Install dependencies (pip install -r requirements.txt if needed)
Add your own config.py with:
API_KEY = "YOUR_API_KEY"
Run the scraping notebook 
Use the cleaned datasets for analysis or dashboards

### Acknowledgements
This project was inspired by the exceptional work of Think School, whose storytelling and educational content make complex business, geopolitical, and strategic subjects accessible to everyone.

## Contact
_Riddhi Rajput_
Data Analytics & Content Strategy Enthusiast
GitHub: https://github.com/riddhi-rajput

Email: rajputriddhi825@gmail.com
