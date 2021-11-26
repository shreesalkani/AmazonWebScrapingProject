# AmazonWebScrapingProject

Web scraping is a data extraction method used to exclusively gather data from websites. It is widely used for Data mining or collecting valuable insights from large websites. Web scraping comes in handy for personal use as well. Python contains an amazing library called BeautifulSoup to allow web scraping. We will be using it to scrape product information and save the details in a CSV file.
Module needed and installation:

BeautifulSoup: Our primary module contains a method to access a webpage over HTTP.

lxml: Helper library to process webpages in python language.

requests: Makes the process of sending HTTP requests flawless.the output of the function


Approach:



First, we are going to import our required libraries.
Then we will take the URL stored in our text file.
We will feed the URL to our soup object which will then extract relevant information from the given URL
based on the element id we provide it and save it to our CSV file.
Let’s have a look at the code, We will see what’s happening at each significant step.

Step 1: Initializing our program.

We import our beautifulsoup and requests, Create/Open a CSV file to save our gathered data. We declared Header and added a user agent. This ensures that the target website we are going to web scrape doesn’t consider traffic from our program as spam and finally get blocked by them
