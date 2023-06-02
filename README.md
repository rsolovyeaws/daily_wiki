Working in technology means we have to be constantly learning, and learning about more than just the technology we work with can make us even better at our jobs. Wikipedia is a fantastic source of knowledge. To encourage ourselves to keep learning, we've decided to write a web scraper that can extract Wikipedia's featured articles so that we can send ourselves a few articles a day to read and learn from. We've decided to use Scrapy to write our web scraper, since it includes the main features that we want:

Web scraping
Exporting scraped content in various formats
We'll call our project daily_wiki. Using the tools that Scrapy provides, we should be able to create an articles web scraper (called a "spider") that we can run using the following command from within our project:

(daily_wiki) $ scrapy crawl articles
...
To be comfortable completing this lab, you'll need to know how to do the following:

Create a Scrapy project. Watch "Project Overview and Setup: Data Checker" from the Programming Use Cases with Python course if you're unfamiliar with how to do this.
Create a Scrapy spider and determine an HTML/CSS/XPath selector to extract a piece of content from a web page. Watch "Creating a Web Scraper with Scrapy" from the Programming Use Cases with Python course if you're unfamiliar with how to do this.
Export feeds from Scrapy. Watch "Storing Items and Sending Email" from the Programming Use Cases with Python course if you're unfamiliar with how to do this.