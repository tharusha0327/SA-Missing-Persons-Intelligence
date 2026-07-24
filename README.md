# South African Missing Persons Intelligence Dashboard

## Overview

This project explores publicly available missing persons data from the South African Police Service (SAPS) website.

The objective is to identify patterns and trends relating to:

- Missing persons demographics
- Geographic distribution
- Age categories
- Police station reporting
- Case timelines
- Public safety insights

This project combines:

- Python
- Web Scraping
- PostgreSQL
- Data Analysis
- Power BI
- Investigative Analytics

---

## Project Status

In Development

Current Phase:
- Repository Setup
- Data Collection Planning

---

## Technologies

- Python
- BeautifulSoup
- Requests
- Pandas
- PostgreSQL
- Power BI

---

## Data Validation Pipeline

During development, the public SAPS website occasionally returned incorrect person details for the requested case identifier. To ensure dataset integrity, every scraped record is validated against the original list page. Records that fail validation are automatically retried and quarantined for manual review if they cannot be verified.

---

## Author

Pasha Morgan
