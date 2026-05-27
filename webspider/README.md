# webspider

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-Requests-blue)

Recursive web crawler that maps a domain up to a configurable depth, collecting URLs, emails and phone numbers. Outputs a structured JSON report.

## Features

- Crawls all internal links up to depth N
- Extracts email addresses and Spanish phone numbers
- Stays within the target domain (no external links)
- JSON output report

## Usage

```bash
python webspider.py -u <URL> -d <depth> -o <output.json>
```

| Flag | Description | Default |
|------|-------------|---------|
| `-u` | Starting URL | required |
| `-d` | Max crawl depth | `2` |
| `-o` | Output JSON file | required |

## Example

```bash
python webspider.py -u https://example.com -d 3 -o report.json
```

## Requirements

```bash
pip install requests beautifulsoup4
```

> For authorized use only.
