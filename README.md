# Motor Vehicle Collision Data Analysis in New York City

In this data science project, we analyze the Motor Vehicle Collision data provided by the New York City Police Department. We extract insights from the data and plot graphs using deck.gl and plotly. We answer the following questions using data:

- Where are the most people injured in New York City?
- How many collisions occur during a given time of day?
- Top 5 dangerous streets by types of affected categories

## How to Run the App

To run the app, follow these steps:

1. Clone the repository:
`git clone git@github.com:Rohail-Zuberi/coursera-data-science-project.git`

2. Navigate to the project directory:
`cd coursera-data-science-project`

3. Install the required dependencies:
`pip install -r requirements.txt`

4. Run the app:
`streamlit run app.py`

5. Open your web browser and navigate to http://localhost:8501 to view the app.

## App Features

The app has the following features:

### Where are the most people injured in New York City?

The app uses `streamlit.map()` method to make a scatterplot of "Where are the most people injured in New York City?". There is a slider that you can move to select the number of people injured.

### How many collisions occur during a given time of day?

The app uses a 3D plot from `deck.gl` to plot "How many collisions occur during a given time of day?". There is a slider to select the hour of the day for this. Below this, we use a plotly histogram to plot the number of crashes by the minute within that hour.

### Top 5 dangerous streets by types of affected categories

The app has a selectbox to select the affected category from pedestrians, cyclists, and motorists. The table below shows the top 5 dangerous streets for the selected category and how many injured on that street.

## Conclusion

By analyzing the Motor Vehicle Collision data provided by the New York City Police Department, we can gain insights into the most dangerous areas and times for collisions. This information can be used to improve road safety and reduce the number of accidents in the city.

Note: The Motor Vehicle Collision dataset used in this project is not included in the repository because it is too large to push. However, you can download the dataset from the following link: 

https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95

Once downloaded, save the dataset in the project directory with the name `Motor_Vehicle_Collisions_-_Crashes.csv` and change the DATA_URL variable to the path of the dataset.
