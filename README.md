# Selenium Automated Login Tests

This repository contains  parallel automated login tests using Python's unittest framework and Selenium WebDriver for the following applications:

- [OrangeHRM Demo Site](https://opensource-demo.orangehrmlive.com/)
- [SauceDemo](https://www.saucedemo.com/)

# 📂 Folder Structure

project-folder/
│
├── test_login.py         # Your Selenium test script
├── README.md             # This file


##  Overview

Two test classes are included:

1. TestLoginOrangeHRM: Tests a valid login and logout workflow on the OrangeHRM demo site using Chrome.
2. TestLoginSauceDemo: Tests a valid login and logout workflow on the SauceDemo site using Firefox.

Each test:
- Opens the browser
- Logs into the website with valid credentials
- Performs a logout
- Verifies that the login page is displayed again

##  Tools

- Python 
- Web drivers:
  - ChromeDriver (for Chrome)
  - GeckoDriver (for Firefox)
- Google Chrome and Mozilla Firefox browsers installed

##  Required Packages

Install dependencies using: pip install pytest pytest-xdist

## Running the Tests
pytest -n 2



