# Project-Week4


Trello project opened

Data were already cleaned as it was mentionned in the description file.


1st step:
Data exploration => checking all the possible variables to analysis, and variables of split. Checking all value counts, type of datas, etc.


2nd step: Define the analysis
The datas are meant to show rides for 12 months, so the aim of the analysis will be to show usages of those bikes

3rd step:
Chart plan

MATPLOTLIB : 
1. Bar chart of rides per month (+ associated with temperature or precipation ??) (sum ride_length possible aussi)
2. Pie chart of bike type
3. Radar Plot of average ride duration by month  and bike type
4. Multiple Box Plot of duration by membership type and bike type
5. Line plot of hourly rides per bike type by month
6. 3D scatter plot ride length per bike type and per member_casual
7. Scatter plot of ride length per time of hour
8. Multi-series Bar Plot of monthly rides by membership type

SEABORN: 
1. Hour of usage bar chart
2. Violin chart of ride duration
3. Bubble plot of ride length per bike type and ???
4. Point Plot of average duration by membership type and bike type
5. Scatterplot matrix of ride start and end locations, duration, and membership type
6. boxplot of rides length per month
7. Area plot of bike type usage per month
8. Jointplot ride duration and member ship type
9. Pie chart of number of person who used it less than 1 minute (potential broken bikes) (0-2 min, 2-5 min, >5 min)

OTHER LIBRARIES:
1. Heatmap of starting zones by count (seaborn + folium)
2. Heatmap of ending zones by count (seaborn + folium)


CAUTION : dataset was too heavy to be uploaded on the repo (800 Mo)
If needed, the dataset was store here (link available until 19/02/2023) : https://we.tl/t-VLCdJpfNX6
