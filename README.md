# Scraping-_HTML
This project focuses on web scraping and data analysis, utilizing HTML parsing, automated browsing with Splinter, and data manipulation with Python libraries. The tasks involve scraping data from Mars-related websites and analyzing it to generate insights.
Deliverables
Scraping Mars News Articles:

Scraped titles and preview texts from the Mars News website using Beautiful Soup.
Stored each article's title and preview in a Python dictionary with title and preview as keys.
Organized all dictionaries in a Python list for structured data storage.
Optionally exported the data to a JSON file for sharing.

Scraping and Analyzing Mars Weather Data:

Scraped Mars temperature data from a web-based HTML table using Beautiful Soup.
Created a Pandas DataFrame with columns reflecting the table's structure: id, terrestrial_date, sol, ls, month, min_temp, and pressure.
Converted data types to appropriate formats (e.g., datetime, int, float) for analysis.
Conducted analysis using Pandas:
Determined the number of Martian months and days in the dataset.
Identified the coldest and warmest months by calculating average minimum temperatures.
Found the months with the lowest and highest atmospheric pressure.
Generated visualizations:
Bar chart for average monthly minimum temperatures.
Bar chart for average monthly atmospheric pressure.
Plot showing daily minimum temperature trends to estimate the length of a Martian year.
Exported the cleaned and analyzed data to a CSV file.








