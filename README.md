# Projects

Repository containing Tech projects in various fields

## Web Development
*WordPress, HTML, CSS*

Development of 2 websites using **WordPress** technology, while being a **web consultant** for ISEP Junior Entreprise [Junior ISEP](https://juniorisep.com/)

- [Syneria](https://syneria.eu) for an European consulting firm in environmental technology

- [Parsy Fine Properties](https://parsyfineproperties.fr) for a French real estate agency


## Real Estate Data projects exploratory analysis and mapping
*SQL, Data Cleaning with Python & Google Sheets*

Following my internship at [Proprioo](https://www.proprioo.fr/), a French startup reinventing real estate with digital tools where I set-up the Data department, I developed a great interest in real estate Data. 

In mid-2019 the French Ministry of Economy made public the notarial bases of the last 6 years (2014 to 2019). **Notarial bases are files listing all the real estate transactions throughout France**, whether they concern land, commercial premises, apartments, houses or other types of properties. These databases thus include a large amount of information related to these transactions, the most important being the sale price, the date of sale, the different surfaces of the property (habitable surface, surface of a possible garden, surface of the cellars, etc.) and the address (in addition to the longitude and latitude) of the property.
Notarial bases can be downloaded [here](https://www.data.gouv.fr/fr/datasets/5c4ae55a634f4117716d5656/)

Following this release I started several real estate projects using these data.

### Mapping
*Google Sheets & Google Maps*

After a long data cleaning work of all Paris transactions (+100 000) contained in the notarial bases, I aggregated these transactions by [pluscode system](https://plus.codes/) developed by Google in order to create "neighborhoods" of around 75000m² with aggregated data in order to have an **evolution of Paris real estate price and dynamism**. After cleaning and aggregating data, I used Google Maps to plot these neighborhoods and create **interactive maps** containing all the Data.

- [Paris Map 1](https://drive.google.com/open?id=1bYKrzYddpg0RCIuHa554BcsgRQOnFXPc&usp=sharing) showing **the average m² price** for all Paris neighborhoods on a small and precise scale and giving you other information (number of transactions per year, average area, average price growth year after year, ...) for each neighborhood

- [Paris Map 2](https://drive.google.com/open?id=1b_0M5x9MTc8AH3XkYjj8f7i3TtrWi5X1&usp=sharing) showing **the average m² price growth** for all Paris neighborhoods on a small and precise scale and giving you other information (number of transactions per year, average price per m², average area, average price growth year after year, ...) for each neighborhood

### Real Estate Estimation Interface
*Google Sheets formulas*

Using Google Sheets and the previously cleaned Data, I have created an **estimation interface** allowing people to get an **estimated value** for their real estate properties in Paris. This estimated value comes with a pretty visual document giving **valuable insights** (price growth over the years, average price, average surface) on the neighborhood the property belongs to, as well as information on the neighborhood (beautiful pictures, best places, quick description).
Instructions on how to use the Estimator are inside (only available in French at the moment).

- [Estimator](https://docs.google.com/spreadsheets/d/1-yrTY5q0C5gitchko1oKf6UgsnxUQwgEUAmis2YKYtg/edit?usp=sharing)

Here are some examples of the documents the Estimator can generate: 

- [Example1](https://drive.google.com/file/d/154GBYd5a3Awr08dwo1R8_bKwAVM9fEcc)

- [Example2](https://drive.google.com/file/d/1USm8pGZTP1PS8LFlZe39TT54oUiYpmns)

- [Example3](https://drive.google.com/open?id=1nP-y3IQyQOYkRv-oZBPUz-RqNnMlCGu9)

### Article redaction
*SQL*

- Redaction of an [article](https://www.proprioo.fr/blog/dynamiques-quartiers-parisiens/) for Proprioo's blog [Parages](https://www.proprioo.fr/blog/) in French about Paris real estate price and dynamism trends after long analyses of the Paris notarial bases (containing all real estate transactions from 2015 to 2018)

## Football Data Analysis Project
*Python - Pandas, Numpy, Matplotlib, seaborn*

Data Analysis project done with **Python** and using several Data Science libraries (**Pandas, Numpy, Matplotlib, seaborn**) in order to get valuable insights from several football datasets and produce nice plots (including interesting **heatmaps**). Datasets have be collected by [Wyscout](https://wyscout.com/) and can be downloaded [here](https://figshare.com/collections/Soccer_match_event_dataset/4415000).

- [View in GitHub](https://github.com/nathanbry2/Projects/blob/master/Football_Analyses.ipynb)

- [View with nbviewer (recommended for much better visualization)](https://nbviewer.jupyter.org/github/nathanbry2/Projects/blob/master/Football_Analyses.ipynb)

## Wisconsin Breast Cancer Prediction Project
*Python - Pandas, Matplotlib, seaborn, scikit-learn*

Data Science project done with **Python** and using several Data Science libraries (**Pandas, Matplotlib, seaborn, scikit-learn**) in order to get valuable insights on what are the main features when it comes to sort out benign and malignant tumours. We will then build a Random Forest Classifier to predict these outcomes. Data can be found [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

- [View in GitHub](https://github.com/nathanbry2/Projects/blob/master/Wisconsin_Breast_Cancer.ipynb)
- [View with nbviewer (recommended for much better visualization)](https://nbviewer.jupyter.org/github/nathanbry2/Projects/blob/master/Wisconsin_Breast_Cancer.ipynb)

## Pokemon Data Project

### Scraping Part
*Web Scraping with Python BeautifulSoup, Pandas*

The first part of the project was about **gathering Data**. Even though several Pokemon datasets already exist, I wanted to create mine, using **web scraping**. I parsed the website [Pokemon Database](https://pokemondb.net/pokedex/all) which lists all necessary information on any existing Pokemon, using Python and the Beautiful Soup parsing library.

Right below are the Notebook containing my code and the dataset I have created.

- [Notebook - View in GitHub](https://github.com/nathanbry2/Projects/blob/master/Pokemon%20Project%20-%20Scraping%20Part.ipynb)

- [Notebook - View with nbviewer (recommended for much better visualization)](https://nbviewer.jupyter.org/github/nathanbry2/Projects/blob/master/Pokemon%20Project%20-%20Scraping%20Part.ipynb)

- [Dataset](https://github.com/nathanbry2/Projects/blob/master/pokemon_dataset.csv)

## COVID-19 confirmed cases visualization 

Using Flourish Studio software and scraped COVID-19 Data I made this [Bar Chart Race video](https://public.flourish.studio/visualisation/1560411/) to show the crazy evolution of the number of confirmed COVID-19 cases per country over time.
