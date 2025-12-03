# Think_Schook_Analysis
I have tried to scrape and analyse the public data of Think School.

# Think School – YouTube Data Analysis Project
A complete end-to-end data scraping, cleaning, analysis, and dashboarding project.

This repository contains an in-depth analysis of the public data from Think School’s YouTube channel, covering:
1)Shorts
2)Podcasts
3)Long-form Case Studies

The purpose of this project is to study content performance, understand audience behaviour, identify hidden patterns, and generate actionable insights that can support content strategy and growth planning.

This analysis was conducted independently as a learning + portfolio project in data analytics, visualisation, NLP, and content strategy.

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
1)Used the YouTube Data API v3
2)Extracted metadata including: view_count, like_count, comment_count, duration, publish date, titles, etc.

#### Data Cleaning & Feature Engineering
1)Converted ISO timestamps
2)Extracted year–month
3)Parsed durations into seconds/minutes
4)Removed Shorts from long-form dataset
5)Created engagement metrics

#### Visual Analysis
Includes:
1)Duration vs Engagement
2)Month/Year-wise performance
3)Rolling averages
4)Distribution plots
5)Heatmaps
6)Upload frequency

#### Dashboards
Four separate Power BI dashboards:
1)Overall Channel Overview
2)Shorts Dashboard
3)Podcast Dashboard
4)Case Study Dashboard

#### Reports
1)Main Summary Report 

#### Insights Summary (Examples)
1)60-second Shorts consistently achieve the highest engagement
2)Geopolitical case studies dominate the Top 10 most viewed videos
3)Podcast viewership peaks during vacation months
4)18–22 minute case studies perform the best among long-form videos
(Full insights are available in the reports/ folder.)

### API Key Security
This project uses a config.py file to store the YouTube API key.
The file is NOT included in version control (protected via .gitignore).

This ensures:
No sensitive information is exposed

The repository remains safe for public sharing

### Tech Stack
1)Python
2)pandas
3)matplotlib
4)seaborn
5)google-api-python-client
6)Power BI 
7)Jupyter Notebook
8)GitHub 

### How to Use This Repository
1)Clone the repository
2)Install dependencies (pip install -r requirements.txt if needed)
3)Add your own config.py with:
4)API_KEY = "YOUR_API_KEY"
5)Run the scraping notebook 
6)Use the cleaned datasets for analysis or dashboards

### Acknowledgements
This project was inspired by the exceptional work of Think School, whose storytelling and educational content make complex business, geopolitical, and strategic subjects accessible to everyone.

## Contact
_Riddhi Rajput_

_Data Analytics & Content Strategy Enthusiast_

_GitHub: https://github.com/riddhi-rajput_

Email: rajputriddhi825@gmail.com
