# Web Scraping with Python

Check out jupyter notebook here: https://jovian.ai/8smbhavikatti/scraping-giva-jewelleries
## Introduction:
### Introduction on Web scraping:
Web scraping is the process of extracting specific data from the internet automatically
We are scraping https://www.giva.co/
Note: This is preferred only for learning purpose


## About GIVA
GIVA Website is basically a E-Commerce site which sells jewellery store featuring high-quality, affordable designs
Here we are scraping the details like the Categories it has,Actual Price of the product,Sale Price of the product,URL of the category,Rating and Reviews it has recieved.

## Outline of the project:
1. Understanding the structure of GIVA Website
2. Installing and Importing required libraries
3. Simulating the page and Extracting the different Category Name and URLs of from website using BeautilfulSoup
4. Accessing each Category with the URL
5. Parsing the Top 10 Products details into 6 fields: Name of Item,Actual Price,Sale Price,Rating,Number of Reviews,Repo URL using Helper Functions.
6. Storing the extracted data into a dictionary.
7. Compiling all the data into a DataFrame using Pandas and saving the data into CSV file
