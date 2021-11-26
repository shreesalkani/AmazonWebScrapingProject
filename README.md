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

Step 2: Retrieving element Ids.

We identify elements by seeing the rendered web pages, but one can’t say the same for our script.  To pinpoint our target element, we will grab its element id and feed it to the script. 

Getting the id of an element is pretty simple. Suppose I need the element id of the products name, All I have to do 

Get to the URL and inspect the text
In the console, we grab the text next to id=

Step 3: Saving current information to a text file



We use our file object and write the string we just captured, and end the string with a comma “,” to separate its column when it’s interpreted in a CSV format.


