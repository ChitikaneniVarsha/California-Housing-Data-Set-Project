# California-Housing-Data-Set-Project
**California Housing Data Analysis Project**
**Introduction:**
The California Housing Data Analysis project explores the California Housing dataset, which contains information gathered from the 1990 Census. The dataset consists of 20,640 examples of block groups, each representing a geographically compact area with an average population of 1,425.5 individuals. The dataset includes ten variables, providing details about the geographical location, housing characteristics, population, and income.

**Dataset Features:**

**longitude**: Continuous

**latitude**: Continuous

**housing Median Age**: Discrete

**Total Rooms**: Discrete

**Total Bedrooms**: Discrete

**Population**: Discrete

**Households**: Discrete

**Median Income**: Continuous

**Median House Value**: Discrete

**Ocean Proximity**: Nominal

**Questions Addressed**:

**1.Average Median Income and Distribution:**
Calculated the average median income and visualized its distribution using a histogram.
**Observation**: The distribution is positively skewed, indicating higher median incomes are less common.

**2.Housing Median Age:**
Plotted a histogram for housing median age.
**Observation**: The distribution is fairly symmetrical with a skewness of 0.06.

**3.Median Income vs Median House Values:**
Explored the relationship between median income and median house values using a scatter plot.
**Observation**: Positive correlation between median income and median house values.

**4.Handling Missing Data:**
Deleted examples with missing total bedrooms data.
Filled missing total bedrooms data with the mean value.

**5.Median Value Calculation:**
Implemented a function to calculate the median value for each variable where applicable.

**6.Latitude vs Longitude:**
Plotted a scatter plot for latitude vs longitude.
**Observation**: Latitude and longitude are directly proportional.

**7.Dataset Filtering - Near Ocean:**
Created a dataset filtering examples where ocean proximity is 'Near Ocean.'

**8.Mean and Median of Median Income (Near Ocean):**
Calculated the mean and median of median income for the 'Near Ocean' dataset.

**9.Total Bedroom Size Classification:**
Created a new column, 'total_bedroom_size,' categorizing sizes as small, medium, or large based on specified conditions.

**Conclusion:**
This project provides insights into the California Housing dataset, showcasing data visualization techniques, missing data handling, and feature engineering. The analysis enhances understanding of the relationships between various housing-related variables and serves as a comprehensive exploration of the dataset.
