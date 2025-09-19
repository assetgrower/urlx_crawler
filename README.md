
Spec for the URLx Crawler.


Background: URLX finds URLs and we want to crawl them and save meta data to Google Storage

Things we want this todo:
 - Be able to process 100M total per day (x per second, across x VMs).
 - Make sure not to get abuse complaints (probably run through proxies in the same region)
