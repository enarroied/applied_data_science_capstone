# applied_data_science_capstone

## What is this?

This notebooks are part of the Coursera course ["Data Science Professional Certificate"](https://www.coursera.org/professional-certificates/ibm-data-science) by IBM.

[Here is my credential for completing the course](https://www.credly.com/badges/d869e7e7-d1c6-42d1-960e-47bb17019390?source=linked_in_profile).

## Case of study

The notebooks show the different steps required to perform a basic Machin Learning project. In this case, they aim to predict if the Falcon 9 first stage will land successfully: SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.


## Content

The project has 7 notebooks and a dashboard application created with Dash.

Each note book (or app) represents a step in the process of data analysis and prediction. 

* ```1_API_spaceX_projetc.ipynb```: collecting data about SpaceX launhings via the API.
* ```2_Data_wrangling.ipynb```: wrangling the data and performing some Exploratory Data Analysis (EDA) on it.
* ```3_webscrapping-capstone.ipynb```: collecting data from Wikipedia with web scrapping.
* ```4_EDA_with_Visualization.ipynb```: create visualizations with Matplotlib and Seaborn.
* ```5_EDA_with_SQL.ipynb```: learn some basic SQL commands to wrangle data. Used a DB2 DataBase and an IBM environment to retrive the data, the notebooks execute the SQL commands with cell magic.
* ```6_Data_visualization_folium.ipynb```: visualize data about the launchings using Folium (geographic data visualization).
* ```7_Machine_Learning_Prediction_Lab.ipynb```: predict the outcome of the launchings of SpaceX's Falcon 9 rockets based on several parameters (location, time...).
* ```8_spacex_dash_app.py```: a dashboard app created with Dash and data from the Falcon 9 launchings.