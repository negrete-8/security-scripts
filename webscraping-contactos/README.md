# webscraping-contactos

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-BeautifulSoup-orange)

Extracts contact information from a target website: emails, Spanish phone numbers and contact/privacy links.

## Features

- Discovers contact and privacy page links
- Extracts email addresses via regex
- Extracts Spanish phone numbers (`+34` format)
- Saves results to `Reporte.txt`

## Usage

```bash
python webs_scraping.py -u <URL>
```

## Example

```bash
python webs_scraping.py -u https://example.com
```

## Requirements

```bash
pip install requests beautifulsoup4
```

> For authorized use only.
