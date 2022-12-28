# Homestay Price At Seatle Investigation
## By VietNT3

- Project link: https://github.com/Vietnt1987/ds_project1
- Blog post link: https://github.com/Vietnt1987/ds_project1/wiki/How-you-choose-home-stay-with-correct-price-when-traveling-in-Seattle-with-Airbnb-data%3F

## Libraries used:
    libraries required for project are in requirements.txt file.
    
## Project motivation
This project, i will be creating a blog post and Github repository to begin building a data science portfolio of my own. 

## Installation:
    - install libraries by command line: pip install -r requirements.txt
    - open notebook by command line: jupyter notebook

## Project summary
    - Project name: Homestay Price At Seatle Investigation
    - Description: Project is to investigating how characteristics of homestay affected to the price.

## explanation of files in the repository
    - seattle_airbnb.ipynb is jupyter notebook file which contains all the investigation
    - listings.csv is the dataset file containing information  about homstay in Seattle
    - seattle_airbnb.slides.html is slide file for communication. This file is generated each time run deploy command at the end of seattle_airbnb.ipynb
    - requirements.txt contains all libraries required to work with this project.

## Dataset
    Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA. The following Airbnb activity is included in this Seattle dataset:
        - Listings, including full descriptions and average review score
        - Reviews, including unique id for each reviewer and detailed comments
        - Calendar, including listing id and the price and availability for that day
    In this project i would like to use only listings.csv file for my investigation. This dataset has 3818 rows and 92 columns.


## Summary of Findings
    In this investigation, i'm most interested in checking price of homestay to know about all characteristics affected to the price. So, i will investigate and answers about my interested questions are:
        - which quatities affect to price and what is the most affected to price ?
        - how kind of neighbourhood_group_cleansed affected to price. which has the most price.
        - how kind of homestay affected to price. which has the most price.
        - how kind of room type affected to price. which has the most price.

## Licensing, Author, and Acknowledgements
    - Data source: [Seattle Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/seattle)
    - Acknowledgements:
    Data credit
        Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.
    - Author: VietNT3
    - License: Distributed under the MIT License.
