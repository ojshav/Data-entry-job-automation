# Data Entry Job Automation using Beautiful Soup and Selenium on Zillow.com
If you are tired of manually entering data into spreadsheets, then this project may be just what you need. In this project, we used Beautiful Soup and Selenium to automate the data entry process for Zillow.com, a popular website for finding houses for rent and sale in the United States. We then stored the collected information into a Google Form and converted it into an Excel sheet for easier management.

### Overview
The goal of this project was to automate the process of collecting data from Zillow.com and store it in an organized manner that can be easily accessed and analyzed. The automation process was achieved by using two powerful Python libraries: Beautiful Soup and Selenium.

We used Beautiful Soup to parse the HTML content of the Zillow.com website and extract the relevant information such as the address, price, number of bedrooms and bathrooms, square footage, and other details for each house listing. We then used Selenium to interact with the Google Form and automate the process of entering the data about the required houses.

### Requirements
* Python 3.x
* Beautiful Soup
* Selenium
* Google Forms
* Google Sheets

### Usage
* Install the required libraries:
pip install beautifulsoup4
pip install selenium
* Create a new Google Form and add the desired fields for data entry such as Address, Price, Number of Bedrooms, Number of Bathrooms, Square Footage, and other details.
* Use Beautiful Soup to extract the relevant information from Zillow.com and store it in a Python dictionary.
* Use Selenium to automate the process of filling out the Google Form with the information about the required houses.
