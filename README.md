# Feed Reader Testing project

This project is a web-based application that reads RSS feeds and it has a small test suite. 


## What does it do?

1. RSS Feeds test loops through each feed in the allFeeds object and ensures it has a URL and a name defined and that the URL and the name are not empty.
2. The menu test suite ensures the menu element is hidden by default and the menu changes visibility when the menu icon is clicked;
3. Initial Entries test ensures there is at least a single .entry element within the .feed container after the loadFeed function is called and completes its work. 
4. New Feed Selection test ensures that the content actually changes after a new feed is loaded by the loadFeed function.

### How to see its power?

Please, run index.html via your favourite browser and enjoy its loveliness.