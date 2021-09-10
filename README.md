# Generic scrapy crawler to scrape reddit.

How to use:
1. Clone this repo
2. Install scrapy
3. Run
```
scrapy crawl redditPosts -s CLOSESPIDER_ITEMCOUNT=1000 -o posts.json
scrapy crawl bursaBets -s CLOSESPIDER_ITEMCOUNT=1000 -o bursaPosts.json
```