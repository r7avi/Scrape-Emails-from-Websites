# Email Scraper

This Python-based email scraper extracts email addresses from websites listed in a CSV file. It uses the Playwright library to interact with web pages and locate email addresses on both the main page and designated contact pages.

## Features

- Scrapes email addresses from the main page of a website.
- Follows and scrapes contact pages linked from the main page.
- Converts relative URLs to absolute URLs.
- Logs errors to `error_log.txt` for troubleshooting.
- Saves results to a new CSV file with an additional 'Email' column.

## Prerequisites

- Python 3.7 or higher
- Google Chrome or Chromium browser

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/email-scraper.git
   cd email-scraper
