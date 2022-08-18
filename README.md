# Exploratory and explanatory visualization of FordGoBike System data.
## Introduction
Ford GoBike is the Bay Area's bikeshare system, which aims to be fast, convenient way to get around whether you're commuting, running errands, or just sightseeing. In this analysis, I aim to perform Univariate, Bivariate and Multivariate exploration with this data that includes trip duration information about individual rides made by users of the Ford GoBike bike-sharing system covering the greater San Francisco Bay area in February 2019.

## Dataset
In this project, I worked on the following dataset:
- __FordGoBike System Data__: This data set includes information about 183000 individual rides made in a bike-sharing system covering the greater San Francisco Bay area. 

## Summary of Findings
In conclusion, I will say most users are males and they tend to ride for short durations because the most trips tend to last for approximately 10 minutes. Also of the two user types, subscribers did the most trips but on a daily basis customers tend to have a higher average trip duration. The majority of users are under the age of 40 years and they use the service in addition with other modes of transport to complete their trips. Although Saturday and Sunday have the least of amounts of trips, most of the long duration trips happened on these same days. Thursday has the highest amount of trips. Based on the period of the day, trips tend to be lesser in the Afternoon and Night time but the average trip duration tend to be higher during these same periods.

Outside of the main variable of interest, I observed the relationship between member age, trip distance and day of the week. As I expected, the older the member the lesser the distance they covered and this was evident in the exploration as I found that members aged 18 - 50 years old convered more distance than members aged above 50 years old. I also found that the age distribution of members who booked trips on Saturday and Sunday are similar and younger compared to other days.

## Key Insights for Presentation
For the presentation, the focus will be on the trip duration and its relationship with other variables - days of the week, member age and, user type - that leads to insights that allows us to understand the data. I will start with introducing the univariate distribution of the main variable of interest: duration. Then I'll go on to show bivariate visualizations depicting how the other variables of interest relate with the main variable of interest. Finally I'll depict multivariate visualizations to show how the combination of user type and days of the week can effect trip duration. At the end of the presentation, we should be able to determine factors that can have the most effect on trip duration with just knowing certain details about any typical user.

You can see content on nbviewer:  
- Explanatory analysis: [Slide presentation](https://nbviewer.org/github/10xDatabro/FordGoBike-data-visualization/blob/main/HTML/FordGoBike_deck.slides.html#/2) , [Jupyter Notebook](https://nbviewer.org/github/10xDatabro/FordGoBike-data-visualization/blob/main/FordGoBike_deck.ipynb)
- Exploratory analysis: [Jupyter Notebook](https://nbviewer.org/github/10xDatabro/FordGoBike-data-visualization/blob/main/FordGobike_EDA.ipynb)

OR download the HTML files in the subdirectory and view the content offline at anytime in the browser of your local machine.

## Getting Started
> These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- You need to be able to work in a Jupyter Notebook on your computer
- You need an installation of Python and the following python libraries need to be installed. (You can install these packages via conda or pip)
  * NumPy
  * pandas
  * matplotlib
  * seaborn
 
### Installing
These examples tell you how to get a development environment running

I recommend installing Anaconda, which comes with all of the necessary packages, as well as Jupyter Notebook. Here are the installation steps:
- Download the [installer](https://www.anaconda.com/download/). Choose the Python 3.6 or higher version, and the appropriate 64/32-bit installer
- Refer to the installation instructions [here](https://docs.anaconda.com/anaconda/install/)
- Verify the installation, as mentioned [here](https://docs.anaconda.com/anaconda/install/verify-install/)

If you already have Anaconda installed, use the `environment.yaml` to create the exact environment I used during the project by typing the line below into the Anaconda terminal in the same folder where the environment file is saved on your computer
``` 
conda env create -f environment.yaml
```
OR If you're not using Conda, you can use pip to install dependencies with the `requirements.txt` file by typing this line into your terminal

```
pip install -r requirements.txt
```

## Built With
- [Anaconda](https://www.anaconda.com/) - Dependency management
- [Jupyter Notebook](https://jupyter.org/) - Data analysis documentation

## Authors
- Gilbert Adikankwu

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/10xDatabro/FordGoBike-data-visualization/blob/main/LICENSE) for more details.

## Acknowledgments
- Udacity ALX-T Data Analyst Nanodegree
