# Scraping with Selenium


### Getting Set up

Selenium Docs: https://selenium-python.readthedocs.io/

Download chrome webdriver that corresponds to version of google chrome.

https://sites.google.com/a/chromium.org/chromedriver/downloads

to identify which version of google chrome you are using, navigate to the three dots in the corner of browser, select Help > About Google Chrome

Version 86.0.4240.80 (Official Build) (x86_64) unzip download in a directory where you want it to live.

Make sure you've identified the file path, as you'll need to use this directory to access the webdriver.


### Coffee Scraper

The initial goal of this scraper is to navigate to individual coffee products on mistobox.com and extract and store all coffee information (roaster, origin, tasting notes, roast profile, type, process, reviews, etc.