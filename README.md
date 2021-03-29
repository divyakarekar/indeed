# Web Scrapping using BeautifulSoup

A webscrapper to extract jobs posted on indeed.com and store it into csv file.

![image](https://user-images.githubusercontent.com/80902649/112814366-d8b57280-909c-11eb-8a43-65f60e91c43f.png)

BeautifulSoup, one of the most favoured Python's module, is been used for Web Scraping this code.
The code scrapes the information of jobs posted on indeed.com with the given input as position and location.

# Programming Language:

Python Version 3.8.1

# Libraries/Modules:

requests (To make HTTP Requests to fetch data)
BeautifulSoup (To extract/scrape data from websites)
datetime (To extract date)
csv (To store the extracted result in csv file)

# Setup:

1. Clone the repository to your local environment using git.
2. Install the below libraries/modules required to run the program.
   pip install requests
   pip install BeautifulSoup
3. Enter the position and location of the job to be searched while running the main method.
4. Once the packages are installed, the application indeed.py can be run from the command prompt / terminal.
   python scrapper.py
5. A result.csv file gets generated as an output wherein the required job information is stored.
