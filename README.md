# scraper
# Facebook Web Scraping with Selenium

## Introduction

This project provides a Python script for scraping photos from Facebook profiles using the Selenium web automation framework. It can be particularly useful for downloading photos from public profiles or user accounts.

## Prerequisites

Before you begin, make sure you have the following prerequisites installed:

- [Python](https://www.python.org/) (Python 3.6 or higher recommended)
- [Selenium](https://pypi.org/project/selenium/) (Python library for web automation)
- [ChromeDriver](https://chromedriver.chromium.org/) (WebDriver for Google Chrome)
  - You can install it manually or use the [webdriver_manager](https://pypi.org/project/webdriver-manager/) library to manage it automatically.
  
## Setup

1. **Clone the Repository**: Clone this repository to your local machine.
git clone https://github.com/your-username/FacebookScraper.git
cd FacebookScraper

2. **Install Dependencies**: Install the required Python packages using pip.

   pip install -r requirements.txt

3. **Configure Facebook Profile**: Edit the `config.json` file to specify the Facebook profile URL you want to scrape.

4. **Run the Script**: Execute the Python script to start the scraping process.

   python scraper.py


## Configuration

You can customize the behavior of the script by modifying the `config.json` file. You can specify options such as the number of photos to download and the download directory.

## Usage

- The script will launch a Chrome browser controlled by Selenium, navigate to the specified Facebook profile, and download photos.

- Downloaded photos will be saved in the specified directory.

- You can stop the script at any time by pressing `Ctrl+C`.

## Contributing

Contributions to this project are welcome. If you have any improvements or bug fixes to suggest, please submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Note:** This project is intended for educational and personal use only. Respect Facebook's terms of service and privacy settings when using this script. Do not use it to violate anyone's privacy or scrape private information.

If you encounter issues or have questions, please create a GitHub issue, and we'll be happy to assist you.



