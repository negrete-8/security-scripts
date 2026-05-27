# nmap-automation

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?logo=python&logoColor=white)
![Tool](https://img.shields.io/badge/Tool-Nmap-informational)

Automates Nmap port scans using a target IP, a port list file and a configurable scan type.

## Features

- TCP Connect scan (`-sT`)
- SYN Stealth scan (`-sS`)
- Version detection scan (`-sV`)
- Port list loaded from external file

## Usage

```bash
python nmapauto.py -t <IP> -l puertos.txt -s <T|S|V>
```

| Flag | Description |
|------|-------------|
| `-t` | Target IP address |
| `-l` | Path to port list file |
| `-s` | Scan type: `T` (TCP), `S` (SYN), `V` (Version) |

## Example

```bash
python nmapauto.py -t 192.168.1.1 -l puertos.txt -s S
```

## Requirements

```
nmap installed and in PATH
```

> For authorized use only.
