# PaisImap-

A comprehensive collection of IMAP/SMTP server configurations organized by country.

## What's Included

- **219 country/territory JSON files** with IMAP and SMTP settings
- Each file contains **global providers** (Gmail, Yahoo, Outlook, Hotmail, Live, iCloud, ProtonMail, Zoho, Tutanota, Fastmail) plus **country-specific ISPs, telcos, and email providers**
- Major countries include 20-36 providers; smaller countries include the 10 global providers

## JSON Format

```json
{
  "country": "United States",
  "code": "US",
  "providers": [
    {
      "domain": "gmail.com",
      "name": "Google Gmail",
      "imap": {
        "host": "imap.gmail.com",
        "port": 993,
        "ssl": true
      },
      "smtp": {
        "host": "smtp.gmail.com",
        "port": 465,
        "ssl": true
      }
    }
  ]
}
```

## File Naming

Files are named in lowercase with underscores: `usa.json`, `germany.json`, `united_kingdom.json`, `costa_rica.json`, etc.

## Coverage

All regions covered: North America, South America, Western/Eastern/Northern/Southern Europe, Middle East, Central Asia, East Asia, South Asia, Southeast Asia, Oceania, West/East/Central/North/Southern Africa.
