in this notebook I have Performed data analysis and visualization on the Titanic dataset to understand the factors that influenced the survival of passengers.

Steps :-
1. **Data Loading:**
   - Load the dataset using Pandas.

2. **Data Exploration:**
   - Display the first few rows of the dataset.
   - Check for missing values and handle them appropriately.
   - Summarize the dataset using descriptive statistics.

3. **Feature Engineering:**
   - Create a new feature `FamilySize` by combining the `SibSp` (siblings/spouses aboard) and `Parch` (parents/children aboard) columns.
   - Create a new feature `IsAlone` to indicate whether a passenger was traveling alone or with family.
   - Convert categorical variables (like `Sex` and `Embarked`) into numerical format using one-hot encoding.

4. **Data Analysis:**
   - Analyze the survival rate based on different features:
     - **Gender:** Compare survival rates between males and females.
     - **Pclass:** Compare survival rates across different passenger classes.
     - **Embarked:** Analyze the survival rate based on the port of embarkation.
     - **Family Size:** Investigate the impact of family size on survival.
     - **Fare:** Explore the relationship between the fare paid and survival rate.

5. **Data Visualization:**
   - Create visualizations to represent your findings using **Matplotlib**, **Seaborn**, and **Plotly** for interactive plots:
     - **Bar Charts:** Use Plotly to compare survival rates across different categories (e.g., gender, Pclass, Embarked). Make the charts interactive to allow for zooming and hovering over data points.
     - **Histograms:** Visualize the distribution of fares and ages, segmented by survival, using Plotly's interactive features.
     - **Box Plots:** Show the distribution of age and fare for survivors vs. non-survivors using Plotly, allowing for a more dynamic exploration of the data.
     - **Heatmaps:** Use Plotly to create an interactive heatmap showing the correlation between different features.
     - **Scatter and Pair Plots:** Use Seaborn and Plotly to create scatter plots or pair plots showing the relationships between multiple features, colored by survival. Include interactive elements to explore the data in more detail.
       interactive elements to explore the data in more detail.

6. **Summary:**
   - Summarize your findings and insights in a concluding section.
   - Highlight the most significant factors that influenced the survival of passengers.

#### **Tools and Libraries:**
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For static visualizations.
- **Plotly**: For interactive visualizations.
