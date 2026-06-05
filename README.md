**# Hockey-Teams-WebScraper

## 📌 Project Overview
This repository contains a Python-based web scraping application designed to extract semi-structured HTML sports data and convert it into a structured, production-ready dataset. Using a combination of programmatic HTTP requests and programmatic document parsing, the script automates data harvesting from targeted web forms, isolating specific structural table components and rendering them suitable for downstream analytics.

* **Target Applications:** Competitive Intelligence, Sports Data Analytics, Algorithmic Reporting.
* **Core Technology Stack:** Python 3, Requests, BeautifulSoup4 (bs4), Pandas.

---

## 🛠️ Project File Architecture

The repository is structured following industry-standard data engineering practices:
* `Hockey_TeamNames_Scrapper.ipynb` - Documented Python scraping pipeline with inline code commentary.
* `Hockey_TeamNames_Scrapper.csv` - Final extracted dataset output containing scraped hockey team information.
* `requirements.txt` - Complete environment configuration file containing package dependencies.

---


## Execution Steps

1.Ensure your local development environment is configured by installing the core library dependencies directly from the project's layout configuration file:

```bash
pip install -r requirements.txt

2. Clone this repository to your machine:
   ```bash
   git clone https://github.com/usmanali9999/Hockey-Teams-WebScraper.git
   cd Hockey-Teams-WebScraper
   ```

3. Start the Jupyter workspace environment:
   ```bash
   jupyter notebook
   ```

3. Open and run all cell groups inside `Hockey_TeamNames_Scrapper.ipynb` to regenerate the live data.
