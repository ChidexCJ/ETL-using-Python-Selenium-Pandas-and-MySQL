# ETL-using-Python-Selenium-Pandas-and-MySQL
## This project is aimed at using an automation Library "Selenium" to scrape performance data of footballers in English Premier League for the 2022/2023 season from "fbref.com". Three steps were involved in the entire operation.
- ### Extraction
- ### Transformation
- ### Loading
## Extraction - involved using an instance of a web driver (chromedriver) to pull data from the target URL. This cranks up the web page which on element ispection displays its static features. Paths associated to target data are iteratively copied and parsed through a Selenium method. Resulting data is stored in a list.
## Transformation - scraped data are usually dirty and not properly formatted, transformation techniques are applied to handle this problem. Here, datatypes were reformatted, redundant column dropped, columns renamed, and list splitted for easy creation of tabular data.
## Loading - data were loaded to a pandas dataframe and uploaded to a MySQL database.

## NB: .gitignore contains a .ini  file extension holding MySQL credentials used in accessing and loading the database.
