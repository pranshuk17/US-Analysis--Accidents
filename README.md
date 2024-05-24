# US Accidents Analysis

This project conducts an exploratory data analysis on the US Accidents dataset from Kaggle. The dataset contains accident records in the US from February 2016 to March 2023.

![Screenshot (73)](https://github.com/nitinriaan/US-Accidents-Analysis/assets/83333586/8ebb73dd-21e0-47e9-ace6-083ebd7e19fc)

## Data

The dataset is originally from the US Department of Transportation. It was compiled and uploaded to Kaggle.

The data dictionary provides details on each feature in the dataset. Key variables include:

- Location (city, county, state, latitude, longitude)
- Environment (weather, visibility, road conditions) 
- Time (timestamp, day of week, holiday)
- Accident severity and types
- and much more...

The dataset can be found here: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

## Methods

The analysis covers:

- Exploratory data analysis on the distributions of key variables
- Visualizations of major accident factors and trends over time/location
- Determining correlations between variables and accident severity

The project focuses on extracting insights from the data rather than developing a predictive model.

## Requirements

The project requires Python and common data analysis libraries like Pandas, Matplotlib, Seaborn, Folium and Scikit-Learn.

## Usage

The Jupyter Notebook `us_accidents_analysis.ipynb` contains the full analysis. To use:

1. Clone this repository
2. Download the dataset and add to the repository folder
3. Ensure the required libraries are installed
4. Run the notebook

## Key Findings

Some example insights from the analysis:

1. Are there more accidents in warmer or colder areas? - Mild and Hot temperature region have higher numbers. (Hot weather cause of Vehicles overheating, Drivers feeling fatigued or Tires blowing out. etc;)
2. Which 3 states have the highest number of accidents? - California, Florida and Texas. (Dense population might be the reason).
3. Does New York show up in the data? - No, it does not contains accident data of New York. 
4. What is the trend of accidents year over year in terms of degree of severity? - The severity in accidents have decreased. 
5. What time of the day are accidents most frequent in? - 7am-8am in the morning and 4pm-5pm at the afternoon. (people leave to and come back from work at these times respectively)
6. Which days of the week have the most accidents? - Weekdays have more accidents with Friday being the highest. (Commute is higher during weekdays due to work than rest days.
7. Which months have the most accidents? - December and January stack the highest number. (Winter season, snowfall might be the reason here)
8. What is the trend of accidents year over year (decreasing/increasing?) - Numbers have been increasing exponentially.
9. When does the accidents occur more often day or night? - Day (more than twice the number of night time)

   
## References

The original dataset can be found here: https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, and Rajiv Ramnath. “A Countrywide Traffic Accident Dataset.”, 2019.

- Moosavi, Sobhan, Mohammad Hossein Samavatian, Srinivasan Parthasarathy, Radu Teodorescu, and Rajiv Ramnath. "Accident Risk Prediction based on Heterogeneous Sparse Data: New Dataset and Insights." In proceedings of the 27th ACM SIGSPATIAL International Conference on Advances in Geographic Information Systems, ACM, 2019.

