# Amazon.eg Samsung Scraper

Simple Jupyter notebook that uses Selenium to scrape Samsung product titles, prices and image URLs from Amazon Egypt.

## Files
- [scrapper.ipynb](scrapper.ipynb) — main notebook (see symbols: [`webdriver`](scrapper.ipynb), [`Service`](scrapper.ipynb), [`driver`](scrapper.ipynb))
- [samsung_products.csv](samsung_products.csv) — output CSV with Description, Price, Image URL
- [chromedriver](chromedriver) — ChromeDriver binary used by the notebook

## Prerequisites
- Python 3.x
- Selenium: `pip install selenium`
- Chrome browser compatible with the included [chromedriver](chromedriver)

## Usage
1. Open and run the notebook: [scrapper.ipynb](scrapper.ipynb).
2. Ensure the `Service(...)` path in the notebook points to the included [chromedriver](chromedriver).
3. Run all cells — output will be written to [samsung_products.csv](samsung_products.csv).

## Notes
- Respect Amazon's terms of service and robots.txt when scraping.
- This is a minimal example for learning and personal use.

## License
MIT