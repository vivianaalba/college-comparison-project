# Institutional Value in Higher Education: A Data-Driven Analysis of Cost, Quality, and Outcomes

## Abstract
My research aims to study cost, outcomes, and satisfaction ratings of undergraduate institutions throughout the United States. Does “more” really mean better? Through correlational research of over 6,000 American institutions, including both private and public universities and community colleges, I studied what factors make America’s top schools rank so highly. My research involves six data sources, which includes two static web pages, a JSON API endpoint from a dynamic React-based webpage, two APIs, and a downloaded CSV file. Through various steps, including data extraction, cleaning, and aggregation, this project aims to explore which factors play a role in admissions rates, cost, and rankings. <br>

Through statistical and exploratory data analysis, I examined the statistically significant factors that contribute to better student experiences and long-term outcomes. I discovered three overall themes in my research. The first theme was that admissions selectivity is most strongly associated with higher SAT scores, greater faculty pay, and better 4-year graduation outcomes, which suggests that prestige is closely tied to academic rigor and institutional investment. Secondly, crime and location, contrary to initial expectations, did not directly influence institutional rank or tuition, but did correlate with student satisfaction. This is likely due to top-tier institutions being located in urban centers that, despite higher crime rates, offer abundant opportunities and resources. Finally, success outcomes, as measured by post-graduation earnings and completion rates, are significantly associated with higher faculty compensation, lower student-faculty ratios, and greater cost of attendance, suggesting that expensive, well-resourced institutions may offer better long-term returns. I concluded that “more” really does mean better (sometimes), but we must also pay attention to key factors such as school administration, faculty student ratios, and support measures from the university to truly get a worthy return on investment for educational costs. <br>

## Technologies / Skills Used
- **Languages:** Python
- **Data Manipulation & Analysis:** pandas, numpy, scipy, statsmodels, scikit-learn
- **Data Collection / Web Scraping:** requests, BeautifulSoup4, JSON / API handling, python-dotenv
- **Data Cleaning / Matching:** fuzzywuzzy, data aggregation and merging
- **Data Visualization:** matplotlib, seaborn, geopandas
- **Statistical Analysis:** correlation analysis, regression modeling, hypothesis testing
- **Other Skills:** working with multiple data sources, exploratory data analysis, data-driven research and reporting

## Project Structure / How to Run
- `data/` : contains CSV files and extracted data
- `data/merged_data` : contains CSV files and cleaned, merged data
- `notebooks/` : contains Jupyter notebooks for data extraction, cleaning, integration, and analysis
- `report/` : contains written report with project summary, motivations, and results
- `requirements.txt` : contains Python dependencies

**To run the analysis locally:**
```bash
git clone <repo-url>
cd institutional-value-analysis
pip install -r requirements.txt
jupyter notebook notebooks/data_analysis.ipynb


## Requirements
pandas <br>
matplotlib <br>
seaborn <br>
geopandas <br>
scipy <br>
scikit-learn <br>
statsmodels <br>
fuzzywuzzy <br>
python-dotenv <br>
requests <br>
beautifulsoup4 <br>
numpy <br>