# Web Scraping Scripts

This repository contains two Python scripts for web scraping using Selenium and BeautifulSoup. The scripts are designed to collect data from different sources and perform specific tasks.

## Script 1: Main Web Scraper (`main.py`)

**Description**: The `main.py` script is a web scraper that extracts data from the Kaspi.kz website, specifically focusing on notebooks with specific RAM configurations. It scrapes details such as the maximum memory, name, price, and link to each product. The collected data is then saved to a CSV file.

**Usage**:
1. Ensure you have Python 3.x, Selenium, Chrome WebDriver, BeautifulSoup, and Pandas installed.
2. Configure the script with the desired URL, WebDriver path, and other settings.
3. Run the script using the command: `python main.py`.

## Script 2: Link Comparison (`parse.py`)

**Description**: The `parse.py` script reads links from two different sources - a text file and a CSV file. It then compares these links to find the differences between them, specifically identifying links that exist in one source but not in the other.

**Usage**:
1. Ensure you have Python 3.x and the pandas library installed.
2. Provide the paths to the text file and CSV file containing links within the script.
3. Run the script using the command: `python parse.py`.

## Prerequisites

Before using these scripts, make sure you have the following installed:

- Python 3.x
- Selenium (install with `pip install selenium`)
- Chrome WebDriver (download and configure for Selenium)
- BeautifulSoup (install with `pip install beautifulsoup4`)
- Pandas (install with `pip install pandas`)

## Project Structure

The repository is organized as follows:

- `main.py`: Script for scraping notebook data.
- `parse.py`: Script for comparing links.
- `requirements.txt`: A list of Python dependencies.
- `chromedriver.exe`: Chrome WebDriver executable (download and place it here).

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

