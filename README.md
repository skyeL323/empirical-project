Strava Data Science Project:

This project explores and analyses running data extracted from the Strava API for two individuals, myself and my friend Issy. It includes data cleaning, visualisation, and extends into some webscraping of parkrun 5ks in the Devon area. The resulting outcome is a blog on HackMD, which can be found at (https://hackmd.io/@klqCM-EaQ761qj1z07U3NQ/BJkTiNEAyx) - see blog.txt. I have also included a PDF of the blog, however this is better viewed on HackMD. The blog is a summary of the project and includes analysis of graphs created from (i) test_strava.ipynb, and (ii) web_scrape_parkrun.ipynb, which covers only the webscraping component of my project. 
The API download was a zip file I named skye_strava_data, and includes information on activities, friends, giving kudos, any uploaded images, and much more. The same was done for issy_strava_data.
The activities file included a gpx file for each of my activities, which necessitated any geo-spatial data analysis I made. 

Project Structure: 
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
    
