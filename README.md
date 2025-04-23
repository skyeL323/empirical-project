An Overkill Analysis of Personal Strava Data. 

Strava Premium shockingly sits at a price of £55 a year, and so commences my endeavour to process the data myself. 
This project explores and analyses running data extracted from the Strava API for two individuals, myself and my friend Issy. It includes data cleaning, visualisation, and extends into some webscraping of parkrun 5ks in the Devon area. The resulting outcome is a blog on HackMD, which can be found at (https://hackmd.io/@klqCM-EaQ761qj1z07U3NQ/BJkTiNEAyx) - see blog.txt. I have also included a PDF of the blog, however this is better viewed on HackMD. The blog is a summary of the project and includes analysis of graphs created from (i) test_strava.ipynb, and (ii) web_scrape_parkrun.ipynb, which covers only the webscraping component of my project. 
The API download was a zip file I named skye_strava_data, and includes information on activities, friends, giving kudos, any uploaded images, and much more. The same was done for issy_strava_data.
The activities file included a gpx file for each of my activities, which necessitated any geo-spatial data or pace-related analysis.
I generated a few .csv files, which was generated and used as base data in my code. Particulaly, the parkrun results website refreshes with new results every Saturday, so for replicability I used the results scraped from 2025-04-12 dated parkruns. 
GitHub repository (with commit history): https://github.com/skyeL323/empirical-project

Project Directory: (empirical_proj.zip)

C:.
|   all_run_summary.csv
|   blog.txt.txt
|   issy_activity_summary.csv
|   processed_run_dataTEST.csv
|   README.md
|   strava_run_summary.csv
|   sw20-24_devon_parkruns.csv
|   SW20-24_exeter_results.csv
|   test_strava(code_pt1).pdf
|   test_strava.ipynb
|   web_scrape_parkrun(code_pt2).pdf
|   web_scrape_parkrun.ipynb
|  'Run Forrest Run!'_ An Overkill Analysis of Personal Strava Data.pdf
|   
+---.venv
|
+---graph_pngs
|
+---issy_strava_data
|   |   activities.csv
|   |
|   +---activities
|   |
|   +---media
|
\---skye_strava_data
    |   activities.csv
    |
    +---activities
    |      
    +---media
    
    
Requirements:
pip install pandas numpy matplotlib seaborn selenium webdriver-manager geopy requests beautifulsoup4

Instructions: 
1. See requirements for packages needed. 
2. Run test_strava.ipynb first, which includes data cleaning and visualisations of personal Strava data. Don't uncomment the save csvs as it will overwrite the csvs in the directory. 
3. Run web_scrape_parkrun.ipynb second, which includes web scraping of parkrun results from their website for women aged 20-24 in the South West. Don't uncomment the save csvs here either. 
4. See blog.txt for the url to the HackMD blog, which includes analysis of the graphs made in the two notebooks. If this is not suitable, there is also a PDF version of the blog in the project directory, called 'Run Forrest Run!'_ An Overkill Analysis of Personal Strava Data.pdf. 
5. If you would like to see the base code for much of the first notebook, see activities.csv in skye_strava_data or issy_strava_data, which lists all individual recorded activities. 
    
