Performed Data Cleaning and Data Analysis of the California Housing Prices Dataset to find the relation between the housing prices at a block and the amenities and facilities stated in the dataset such as total number of rooms, ocean proximity etc.

The notebook conducts a data analysis of California housing prices, exploring various relationships within the dataset:

1. **Data Cleaning**:
   - Imports necessary libraries (`numpy`, `pandas`, `matplotlib`, `seaborn`).
   - Loads the dataset and examines the `ocean_proximity` column for unique values.
   - Checks for and removes NaN values, ensuring accurate analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzes and visualizes several features:
     - **Population by Ocean Proximity**: Groups data by `ocean_proximity` and plots a bar graph with population on a logarithmic scale, showing higher population near locations labeled "<1H OCEAN."
     - **Income and House Value Relationship**: Uses a 2D histogram to show a positive correlation between median income and house value, with higher income concentrated in houses under $200,000.
     - **House Age and Value Correlation**: Uses a scatter plot to show that median house value and median housing age are not strongly correlated.
     - **Housing Ocean Proximity Distribution**: A pie chart reveals that most houses are within "<1H OCEAN," with "ISLAND" having the least presence.
     - **House Age Frequency**: A histogram shows that the majority of homes have a median age between 30 to 35 years.

The notebook effectively uses grouping, 2D histograms, pie charts, and scatter plots to illustrate patterns and relationships within the California housing market dataset.
