# Interactive-Scraper

🌐 Interactive Web Scraper (Flask App)

This is a simple web application that scrapes data from a website and displays it in a user-friendly format. Built using Python, Flask, and BeautifulSoup as part of an internship project focused on practical web scraping.

 💡 Features

- Scrapes quotes and authors from [quotes.toscrape.com](http://quotes.toscrape.com)
- Clean HTML output in the browser
- Uses BeautifulSoup for parsing and Flask for UI
- Responsive and styled with basic CSS

🗂️ Project Structure

Task-WebScraper/
├── app.py                # Flask backend + scraping logic
├── scraper.py            # Web scraping functions
├── templates/
│   └── index.html        # Display results
└── static/
└── style.css         # Styling

 How to Run

1. Install required packages:
```

pip install flask beautifulsoup4 requests

```

2. Run the app:
```

python app.py

```

3. Open your browser:
```

[http://localhost:5000](http://localhost:5000)

 ⚙️ How It Works

- The app sends a request to `quotes.toscrape.com`
- Parses the HTML to extract quote text and author
- Displays the results in a styled HTML page

