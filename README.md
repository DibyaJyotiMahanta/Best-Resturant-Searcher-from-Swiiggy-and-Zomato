# Restaurant-Searcher: A Python Script for Finding Top-Rated Restaurants on Zomato and Swiggy

## Description

This Python script leverages Selenium to scrape restaurant data from Zomato and Swiggy, enabling you to discover highly-rated establishments based on user reviews and food quality.

## Features

- Data Scraping: Extracts restaurant information from Zomato and Swiggy using Selenium.
- Restaurant Segregation: Organizes restaurants based on user ratings and food quality for informed decision-making.


## Installation

Python: Ensure you have Python 3.9 or later installed on your system. You can download it from the official website: https://www.python.org/downloads/

Create a Virtual Environment (Recommended): Using a virtual environment helps isolate project dependencies and avoids conflicts with other Python installations on your system. Here's how to create one using conda:

### Cmd Pompt
- ``` conda create -n restaurant-searcher python=3.9 ```

### Install Dependencies: Within the virtual environment, use pip to install the required libraries:
- ```pip install selenium pandas numpy```

### Usage
Clone the Repository: Use Git to clone this repository onto your local machine:

- ```git clone https://github.com/DibyaJyotiMahanta/Resturant-Searcher.git```
- ```cd Resturant-Searcher```

### Conda Environment (Optional): If you prefer using conda environments, you can create one using the environment.yml file provided

- ```conda env create -f environment.yml```
  
Activate the environment using source activate restaurant-searcher (Linux/macOS) or activate restaurant-searcher (Windows) before running the script.

Selenium WebDriver: You might need to download a specific WebDriver for your browser to use Selenium effectively. Refer to the Selenium documentation for instructions: https://www.selenium.dev/documentation/

## Contributing

We welcome contributions to this project! Feel free to fork the repository, make changes, and submit pull requests.

## Disclaimer

The restaurant data scraped from Zomato and Swiggy in this project remains the property of the respective owners (Zomato and Swiggy). This project extracts data solely for educational and research purposes, adhering to ethical scraping practices. We respect the intellectual property rights of both Zomato and Swiggy.

## Future Plans :
1. Make a django framework.
2. tie it up to a react frontend for frequent use
3. make it more personalized it like checking the restaurant history resturants according to which food is being searched.
