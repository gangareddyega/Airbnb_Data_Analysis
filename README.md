# Airbnb_Data_Analysis
Wrting a Blog Post based on Findings in Airbnb Data
# Udacity Data Science Nanodegree
## Project: Wrting a Blog Post based on Findings in Airbnb Data

### github: https://github.com/gangareddyega/Airbnb_Data_Analysis

### Table of Contents

1. [Motivation](#motivation)
2. [Installation](#install)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

### Motivation <a name="motivation"></a>

Using the Boston and Seattle Airbnb dataset, this project aims to answer four business questions of interest using descriptive analysis, inferential statistics, and machine learning:

1. Can we find any common pattern or attribute that change the listing price? This will help stakeholder to understand earning in certain time frames, areas, etc.

2. What amenities listed on AirBnB can significantly impact on the listing price? This provides tips to host who want to increase their property value.

3. How well can we predict the listing price? This can provide a reference quote to potential hosts who are interested in the business, or any host who want revaluation on their properties.

4. What are key attributes of listings that make AirBnB guest choose one over the other? This will provide tips to newbies ready to start their business, or old hosts struggling to attract more guests to their listings.

### Installation <a name="install"></a>

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

Install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

# File Descriptions <a name="files"></a>

**airbnb.ipynb**

A Jupyter Notebook with all the codes following the steps of CRISP-DM for analyzing Airbnb data in Boston and Seattle.

**helper.py**

A python script containing all the functions used in the airbnb.ipynb.

**seattle/listings.csv**

The listings data of Seattle downloaded from [here](http://insideairbnb.com/get-the-data.html).

**seattle/calendar.csv**

The time-series data of Seattle downloaded from [here](http://insideairbnb.com/get-the-data.html).

**seattle/reviews.csv**

The review data of Seattle downloaded from [here](http://insideairbnb.com/get-the-data.html).

**boston-airbnb-open-data/listings.csv**

The listings data of Boston downloaded from [here](http://insideairbnb.com/get-the-data.html).

**boston-airbnb-open-data/calendar.csv**

The time-series data of Boston downloaded from [here](http://insideairbnb.com/get-the-data.html).

**boston-airbnb-open-data/reviews.csv**

The review data of Boston downloaded from [here](http://insideairbnb.com/get-the-data.html).

### Results <a name="results"></a>

#### Answer to Question 1:

We find that the listing price varies by many attributes, including but not limited to:
- day in a week
- neighbourhood
- room type 
- number of bedrooms
- number of guests

#### Answer to Question 2:

Top 3 common amenities among the listings are Wifi, Heating, and Essentials. Amenities such as pool, standingvalet,TV add significant values to the homestay.

#### Answer to Question 3:

General speaking, host response rate, accommodates, bedrooms, beds and bathrooms are most significant. For dummy variables, room type of "Entire home/apt", "Private room", and amenity of "neighbourhood", "CableTV" add significant values to the listing compared to other categories. 

#### Answer to Question 4: 

AirBnB guest often make decisions based on the following aspects:

1. host_response_rate; 
2. accommodates;
3. bedrooms, beds and bathrooms;
4. room types: Entire home/apt, Private room;
5. Neighbourhood;

In summary, guests tend to choose the listing with good host response rate and accommodates. In addtion, they also prefer number of bedrooms bedrooms/beds/bathrooms. Mostly prefer Entire home.
### Licensing, Authors, and Acknowledgements <a name="licensing"></a>
Please feel free to folk this repository. I will be glad that if you can find some other interesting insights from the data, and plese let me know. You can leave comments on my blog post [here](https://medium.com/@zhitaowang/how-to-increase-the-value-and-book-rate-of-your-airbnb-home-e5d887e40f60).

Credit to Airbnb for the open data. All data are downloaded from [here](http://insideairbnb.com/get-the-data.html). 
You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/seattle) and [here](https://www.kaggle.com/airbnb/boston).
