# pycrawl web crawler for generating structured data

Usage:

Create virtual python environment:
```
python3 -m venv myenv
source myenv/bin/activate
```

Run the crawler to fetch JSON-LD data. Edit `config.py` to place the URL.

```
pip3 install -m requirements.txt
python3 crawl.py
```

# Credits / references
- JSON-LD scraper based on ScraperHub: https://github.com/hackersandslackers/jsonld-scraper-tutorial
- Google tool for crawling and exposing structured data: https://search.google.com/test/rich-results
- Scraping using Selenium: https://www.toptal.com/python/web-scraping-with-python
