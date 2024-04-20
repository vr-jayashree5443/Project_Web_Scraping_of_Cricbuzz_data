# Project_Web_Scraping_of_Cricbuzz_data

This project involves scraping cricket rankings data from the ICC website. The data is categorized into batting, bowling, and all-rounder rankings for different formats such as Test, ODI, and T20.

## Pages Scraped
- **Page 1: Batting Rankings**
- **Page 2: Bowling Rankings**
- **Page 3: All-Rounder Rankings**

## Scraping Methodology
For each page, the following steps are executed:
1. **Web Scraping:** The BeautifulSoup library is utilized to scrape data from the respective URLs.
2. **Data Extraction:** Specific HTML elements containing player rankings, names, countries, and ratings are identified.
3. **Data Cleaning:** The extracted data is cleaned using regular expressions to remove HTML tags and unnecessary characters.
4. **DataFrame Creation:** The cleaned data is structured into a DataFrame containing columns for player type (batting, bowling, all-rounder), player position, name, country, and rating.
5. **Data Consolidation:** Data from all three pages are consolidated into a single DataFrame.

## Output
The final DataFrame is exported to a CSV file named `file1.csv` for further analysis and usage.

## File Structure
- **batting:** Contains rankings data for batting players.
- **bowling:** Contains rankings data for bowling players.
- **all-rounder:** Contains rankings data for all-rounder players.

## Usage
- **Data Analysis:** The exported CSV file can be used for further analysis, such as identifying top-ranked players, comparing rankings across formats, etc.
- **Visualization:** The data can be visualized using various plotting libraries to gain insights into player performances and rankings trends.

## Libraries Used
- **BeautifulSoup:** For web scraping HTML content.
- **Pandas:** For data manipulation and DataFrame creation.
- **Requests:** For making HTTP requests to fetch web page content.
- **Regular Expressions (re):** For data cleaning and pattern matching.

## Note
Ensure that the BeautifulSoup and Requests libraries are installed in your Python environment before running the script.

```bash
pip install beautifulsoup4
pip install requests
```
