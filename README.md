# Packers Game Data Scraper (Pro-Football-Reference)

This Python script scrapes Green Bay Packers game data from [Pro-Football-Reference.com](https://www.pro-football-reference.com/) for any range of seasons, processes the data using `pandas`, and stores it in a local PostgreSQL database.

> **Disclaimer:** All data belongs to [Pro-Football-Reference](https://www.pro-football-reference.com/). This script is for educational and non-commercial purposes only.

## Features

- Scrapes full season game data for any range of years.
- Handles HTML tables embedded within comments (used by Pro Football Reference).
- Cleans and standardizes column names for usability.
- Stores season-by-season tables and a combined table (`packers_years`) in PostgreSQL.

## Tech Stack

- Python
- Requests
- BeautifulSoup
- Pandas
- SQLAlchemy (PostgreSQL)

## Requirements

Install dependencies using:

```bash
pip install requests beautifulsoup4 pandas sqlalchemy psycopg2-binary
