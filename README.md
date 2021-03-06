# Web Scraping English News

![1_6M0FxnC6CD9L6xGwROl5jQ](https://user-images.githubusercontent.com/85668824/152629704-0c73f23e-e6b7-44ce-86db-00257a83e538.png)


Web scraping is the process of collecting and parsing raw data from the Web, and the Python community has come up with some pretty powerful web scraping tools.

Steps involved in web scraping:

1. Send an HTTP request to the URL of the webpage you want to access. 
The server responds to the request by returning the HTML content of the webpage. It uses a third-party HTTP library for python-requests.

2. Once HTML content is accessed, we are left with the task of parsing the data. 
Since most of the HTML data is nested, we cannot extract data simply through string processing. 
One needs a parser which can create a nested/tree structure of the HTML data. There are many HTML parser libraries available but the most advanced one is html5lib.

3. Now, all we need to do is navigating and searching the parse tree that we created, i.e. tree traversal. 
For this task, we will be using another third-party python library, Beautiful Soup.
It is a Python library for pulling data out of HTML and XML files.

#### Libraries used :

requests

beautifulsoup4



#### Websites Scraped :

https://timesofindia.indiatimes.com/

https://www.ndtv.com/

https://www.indiatoday.in/
