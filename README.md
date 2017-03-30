# all-seeing-eye
Fighting hate by scraping web advertisements and holding the advertisers accountable.

* Short description: create a series of simple tools to scrape the ads on webpages and build a list of the advertisers.

*MVP*

* Create a selenium or siliar tool that can go to a webpage, traverse the pages, pick out the advertisements and screen capture them (preferably cropped) and save to disk or a database with an associated json file of metadata.
* Create cloud infrastructure to run multiple versions of the selenium tool and have them dump to the same bucket or db.
* Scrape the target page for set amount of time or until a certain number of images are collected.
* Create a simple python script to look at the ads and group similar ads (first pass using image stats or md5, later feature descriptor approaches).
* MVP: Once the advertisemnt corpus is reduced such that there is single instance of each advertisement, expose the ads to a crowd platform for labeling (e.g. crowd flower). 
* Long term: use OCR and a neural net to recognize text and logos.
* MVP: Create a jupyter notebook to retrive crowd labeled data, merge it with the raw collection data, clean it up, and show results.
* Publish results in a blog post.

_pull requests gladly accepted_


_see something you can do, hit me up, write a ticket, go to town._
