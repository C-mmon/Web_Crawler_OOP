# Web_Crawler_OOP
Project to build a web crawler from scratch.
Main focus of the project is to crawl all the link from the given url without getting stuck in an infinite loop.

What is a web crawler?
A bot indexing and visiting every URL it encounters in its path.

For simplicity, we will only take a single URL as an input. 
The following project will rely on breadth-first search.

Duplication is one of the main issue in the web-crawler.
Chances are high bot can be stuck in a infinity loop visting a site A which Links to site B which in turns links to Site A.

There are two proposed method to solve this issue.
By checking the canonical tag, but suppose the website is made by someone unprofessional chances are high, there will be no canonical tag.

- Marking every visited site as true using BFS.

