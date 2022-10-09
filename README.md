# Netflix_dataset_EDA

Steps did for Exploratory analysis:
Statistical summary and observations on data: 
1. Shape of data
2. Data type information
3. The statistical description of data
4. Check duplicate values
5. Missing value detection

Data cleaning and pre-processing:
1. Imputed null values of rating column using mode because only 3 NaN values were found.
2. The columns such as director, cast, and country have a majority of null values so replacing the null values with 'Unavailable'.
3. Missing values in the date column can be dropped using dropna().
4. Converting the date column to DateTime format and extracting the year and month columns from it for further analysis.

Exploratory Data Analysis:
1. Non-Graphical Analysis: Value counts and unique attributes.
2. Visual Analysis - Univariate, Bivariate after pre-processing the data and plotting the graphs.

Insights from the EDA:
1. The majority of types of content on Netflix is movies with 69.7% while T.V. shows with 30.3%.
2. Movies and T.V shows content based on ratings.
3. The Year in which NetFlix released maximum content.
4. Number of content released on NetFlix on monthly basis.
5. Top 10 countries that produce maximum content on NetFlix.
6. Top 15 cast that has starred on NetFlix.
7. Top 15 directors that are popular on NetFlix.
8. Top 15 genres that are present on NetFlix
9. The Average duration for T.V. shows that are present on NetFlix is around 2 Seasons.
10. The Average duration for Movies that are present on NetFlix is around  80-100 mins.

Recommendations:
1. Majority of the Movies and T.V. shows present on NetFlix come from the United States and India. So Netflix can focus more on other countries as well to get relevant content.
2. Also NetFlix may prefer the movies and T.V. shows of top directors and cast to increase the number of users.
3. The average watch time of a user can be increased by increasing the durations of Movies and T.V. shows.
