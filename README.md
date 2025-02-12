# AI Web Scraper

This project is an AI-powered web scraper built with Streamlit. It allows users to scrape a website, clean the content, and parse the DOM content based on user input.

## Features

- Scrape website content by entering a URL.
- Clean and extract the body content from the scraped website.
- Store and display the cleaned DOM content.
- Parse the DOM content based on user-provided descriptions.

## Installation

1. Clone the repository:
    ```sh
    https://github.com/kusayvarde/AI-web-scraping.git
    cd AI-web-scraper
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run main.py
    ```

2. Enter the website URL you want to scrape in the input box and click "Scrape Website".

3. View the cleaned DOM content in the expandable text box.

4. Describe what you want to parse in the text area and click "Parse Content" to see the parsed results.

## Project Structure

- [main.py](http://_vscodecontentref_/1): The main Streamlit application file.
- [scrape.py](http://_vscodecontentref_/2): Contains functions for scraping and cleaning website content.
- [parse.py](http://_vscodecontentref_/3): Contains functions for parsing the DOM content.

## Dependencies

- Streamlit
- selenium
- BeautifulSoup4
