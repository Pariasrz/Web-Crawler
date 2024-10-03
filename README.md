# Web-Crawler

The notebook implements a web crawler using Python, employing libraries such as requests for fetching web pages, urllib for handling URL-related tasks, BeautifulSoup for parsing HTML and extracting links, and networkx for building a directed graph that represents the structure of a website. 

Starting from a predefined URL (https://example.com), the crawler performs a breadth-first search (BFS) algorithm to explore all internal links within the same domain, storing visited URLs in a set to avoid revisiting them. As the crawler navigates through the website, it adds discovered links as nodes and edges in a graph. The crawler ultimately constructs a graph of the website's link structure, which can later be visualized using matplotlib or saved as a .gexf file which can be used with Gephi. 
