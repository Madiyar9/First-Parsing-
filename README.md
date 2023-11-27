# Web Scraping Project

This project contains two Python scripts for web scraping data from different sources using Selenium and BeautifulSoup.

## Scripts

### Script 1: Notebook Scraping

This script scrapes data from the Kaspi.kz website to collect information about notebooks with specific RAM configurations. It extracts details like the maximum memory, name, price, and link to each product. The collected data is then saved to a CSV file.

#### Usage

1. Make sure you have Python 3.x, Selenium, Chrome WebDriver, and BeautifulSoup installed.
2. Configure the URL, WebDriver path, and other settings in the script.
3. Run the script: `python notebook_scraping.py`.

### Script 2: Link Comparison

This script reads links from two different sources, a text file, and a CSV file, and compares them to find the differences. It identifies links that exist in one source but not in the other.

#### Usage

1. Make sure you have Python 3.x and pandas installed.
2. Provide the paths to the text file and CSV file containing links in the script.
3. Run the script: `python link_comparison.py`.

## Prerequisites

- Python 3.x
- Selenium (install with `pip install selenium`)
- Chrome WebDriver (download and configure it for Selenium)
- BeautifulSoup (install with `pip install beautifulsoup4`)
- Pandas (install with `pip install pandas`)

## Project Structure

- `notebook_scraping.py`: Script for scraping notebook data.
- `link_comparison.py`: Script for comparing links.
- `requirements.txt`: List of Python dependencies.
- `chromedriver.exe`: Chrome WebDriver executable (download and place it here).

## Contributing

If you'd like to contribute to this project or report issues, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


