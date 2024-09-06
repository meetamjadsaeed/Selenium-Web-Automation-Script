# Selenium Web Automation Script

This Python script uses Selenium to automate interactions with two websites: Daraz and Facebook. It demonstrates basic functionalities such as performing a search on Daraz and logging into Facebook.

## Features

- **Daraz Search Automation:** Searches for "redmi note 11" on the Daraz website.
- **Facebook Login & Crawling:** Logs into Facebook and performs actions such as clicking "Add Friend" and crawling for friends.

## Prerequisites

- Python 3.x
- Selenium
- WebDriver Manager
- Chrome WebDriver

## Installation

1. **Install Python 3.x**: Ensure Python is installed on your system.

2. **Install Required Libraries**: Install the necessary Python libraries using pip:

    ```bash
    pip install selenium webdriver-manager
    ```

3. **Download ChromeDriver**: The `webdriver-manager` library will automatically handle the downloading and setup of ChromeDriver.

## Usage

1. **Set Up the Script**: Update the script with your own Facebook credentials (email and password) in the `facebook_login_and_crawl` function.

2. **Run the Script**: Execute the script using Python:

    ```bash
    python script_name.py
    ```

    Replace `script_name.py` with the name of your Python script file.

## Script Overview

The script performs the following actions:

1. **Daraz Search Automation**:
    - Opens the Daraz website.
    - Searches for "redmi note 11".
    - Clicks the search button.

2. **Facebook Login & Crawling**:
    - Opens Facebook and logs in with provided credentials.
    - Clicks on "Add Friend".
    - Crawls for friends by scrolling through the page and collects friend names.

## Notes

- **Security:** Make sure not to share your credentials publicly. Consider using environment variables or a secure method to handle sensitive information.
- **Website Changes:** This script may need updates if the websites change their layout or element IDs.
