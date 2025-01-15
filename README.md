# Web Scraping Practice Project 🌐

A project undetaken by myself as a first exploration into web scraping and collecting data myself for use in analysis.

## About the Project 🌟


I undertook this as part of my training to become a Data Analyst. It is important to do projects like this as it helps to understand where data is sourced from and how this process happens. This can be used going forwards in many contexts to conduct
analysis on data found online. The website used here is designed to practice this technique: https://books.toscrape.com/

## Goals 🎯

- Learn HTML basics and understand:
  - Tag functionality
  - How to access parts of tags
  - Tag hierarchy
- Learn `BeautifulSoup` as a means to fulfil a web scraping project 
- Create three functions aimed at fulfilling tasks that run sequentially:
  - Scrape a list of categories on the site
  - Scrape a list of books from each category
  - Scrape features and descriptions of each book

## Technologies Used 🖥️

- `python`
  - `pandas`
  - `numpy`
  - `requests`
  - `BeautifulSoup`
  - `RegEx`
- Microsoft Excel CSV Files (for data exportation)

## Project Structure 🔀

- **HTML Exploration**: Began with a look into HTML tags, webpage structure and key information to gather
- **Homepage Scraping**: First step in scraping was to work on the homepage. Learnt how to extract text from tags and used this to gather link suffixes which were reverse engineered into workable links.
- **Python Understanding**: Looked into manipulating what is returned by BeautifulSoup web scraping and used this to create a preliminary dataframe holding all books on the site
- **Output Generation**: Scraped each book listing page individually to get an extensive dataframe holding all information related to each book. Exported this dataframe to a csv for further use.
- **Project Explanation**: Went over the code, explaining techniques through commetns and cleaning up code via function division.

## Outcomes 🎉

*Technical*:

- `Scraped Books.csv` is the final output from my code. It gives each books title, hyperlink and a range of information relating to it in a csv format
- Develop the basis of a web scraping tool. It fulfills the task as intended however has room for improvement should I find the time. These improvements are described at the beginning of `BooksToScrape_Book_Scraper`.

*Personal*:

- Learn more about webpages and how they are coded and structured
- Practice web scraping through python
- Strengthen basic python techniques including list/dictionary manipulation, looping and function relationships
