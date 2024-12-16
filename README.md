# Ecuador Fishing Industry Data Scraper

A Python script to scrape and collect data about fishing vessels and fishmeal plants from Ecuador's government websites.

## Overview

This project scrapes data from Ecuador's official fishing industry websites to gather information about:
- Fishing vessels
- Fishmeal and fish oil processing plants

## Data Sources

The script collects data from the following government websites:
- Vessels: https://srp.produccion.gob.ec/industrial/web/embarcaciones
- Fishmeal Plants: https://bitacora.produccion.gob.ec/industrial/web/empresas

## Features

- Scrapes both main listing pages and detailed information pages
- Handles pagination automatically
- Collects comprehensive vessel information including registration details
- Gathers fishmeal plant data including ministerial agreements
- Exports data to both CSV and Excel formats
- Includes error handling and logging for failed scraping attempts

## Requirements

- Python 3.x
- Required packages:
  - requests
  - beautifulsoup4
  - pandas