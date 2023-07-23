# Swiggy Restaurant Data Analysis Project

![Swiggy Restaurant Data Analysis](images/swiggy_analysis.png)

This repository contains the code and documentation for the **Swiggy Restaurant Data Analysis Project**. The project involves collecting restaurant data from the Swiggy website using web scraping techniques, cleaning the data, performing data analysis, and deriving valuable insights.

## Introduction

Swiggy is a popular online food delivery platform that connects customers with a wide range of restaurants. This project aims to analyze the restaurant data available on Swiggy to gain insights into various aspects such as popular cuisines, average ratings, delivery times, and more. The ultimate goal is to provide valuable information to restaurant owners and customers, helping them make informed decisions.

## Data Collection

To collect restaurant data from Swiggy, we used **Selenium** and **BeautifulSoup** in Python. Selenium is a powerful web automation tool that allows us to interact with the Swiggy website, while BeautifulSoup helps in parsing the HTML content to extract relevant information.

## Data Cleaning

Once the data was collected, it underwent a data cleaning process to handle missing values, remove duplicates, and ensure consistency in the data. Python was used for data cleaning tasks, and the cleaned data was exported to a CSV file for further analysis.

## Data Analysis

The data analysis phase involved exploring the cleaned data using **pandas**, **NumPy**, and other Python libraries. Various statistical and visualization techniques were applied to understand the trends and patterns in the restaurant data.

## Insights

- Top cuisines preferred by customers.
- Restaurants with the highest and lowest average ratings.
- Average delivery times for different types of cuisines.
- Popular locations with the most number of restaurants.
- Correlations between ratings, cuisines, and delivery times.

## Dependencies

The following Python libraries are used in this project:

- Selenium
- BeautifulSoup
- pandas
- NumPy
- matplotlib
- seaborn

## How to Use

To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/swiggy-restaurant-analysis.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the data collection script: `python src/data_collection.py`
4. Run the data cleaning script: `python src/data_cleaning.py`
5. Explore the notebooks in the `notebooks/` directory for data analysis.
6. Check the `presentation/` directory for the final PPT.

## Contributing

We welcome contributions to this project! If you find any issues or have suggestions for improvement, please create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank Swiggy for providing the restaurant data, which made this analysis possible. Additionally, we acknowledge the open-source community for the valuable tools and libraries used in this project.
