# HTML Regulation Parser

A Python project that parses regulatory HTML documents and converts them into structured JSON.

## Features

- Parse HTML legal/regulatory documents
- Extract chapters and articles
- Export structured JSON
- Built with BeautifulSoup

## Project Structure

HTML-Regulation-Parser/

├── parser.py  
├── parser.ipynb  
├── law123.html  
├── law123_output.json  
└── README.md

## Requirements

```bash
pip install beautifulsoup4
```

## Run

```bash
python parser.py
```

## Example Output

```json
{
  "title": "Water Regulation Act 2024",
  "chapters": [
    {
      "chapter": "Chapter 1",
      "articles": [
        {
          "article": "Article 1",
          "text": "This regulation applies..."
        }
      ]
    }
  ]
}
```
