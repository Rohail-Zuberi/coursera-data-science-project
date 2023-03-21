# Motor Vehicle Collision Data Analysis in New York City

In this data science project, we analyze the Motor Vehicle Collision data provided by the New York City Police Department. We extract insights from the data and plot graphs using deck.gl and plotly. We answer the following questions using data:

- Where are the most people injured in New York City?
- How many collisions occur during a given time of day?
- Top 5 dangerous streets by types of affected categories

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
