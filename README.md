# CL-I

BE AI&amp;DS (SPPU) Computer Lab - I  


1 A1 Feature Transformation (Any one)
A. To use PCA Algorithm for dimensionality reduction. You have a dataset that
includes measurements for different variables on wine (alcohol, ash, magnesium,
and so on). Apply PCA algorithm & transform this data so that most variations in
the measurements of the variables are captured by a small number of principal
components so that it is easier to distinguish between red and white wine by
inspecting these principal components. Dataset Link:
https://media.geeksforgeeks.org/wp-content/uploads/Wine.csv
B. Apply LDA Algorithm on Iris Dataset and classify which species a given flower
belongs to. Dataset Link:https://www.kaggle.com/datasets/uciml/iris


2 A2 Regression Analysis:(Any one)
A. Predict the price of the Uber ride from a given pickup point to the agreed drop-off
location. Perform following tasks: 1. Pre-process the dataset.
2. Identify outliers. 3. Check the correlation. 4. Implement linear regression and
ridge, Lasso regression models. 5. Evaluate the models and compare their respective
scores like R2, RMSE, etc. Dataset
link: https://www.kaggle.com/datasets/yasserh/uber-faresdataset
B. Use the diabetes data set from UCI and Pima Indians Diabetes data set for performing
the following: a. Univariate analysis: Frequency, Mean, Median, Mode, Variance,
Standard Deviation, Skewness and Kurtosis b. Bivariate analysis: Linear and logistic
regression modeling c. Multiple Regression analysis d. Also compare the results of
the above analysis for the two data sets Dataset
link: https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

3 A3 Classification Analysis (Any one)
A. Implementation of Support Vector Machines (SVM) for classifying images of
handwritten digits into their respective numerical classes (0 to 9).
B. Implement K-Nearest Neighbours‟ algorithm on Social network ad dataset.
Compute confusion matrix, accuracy, error rate, precision and recall on the given
dataset.
Dataset link:https://www.kaggle.com/datasets/rakeshrau/social-network-ads

4 A4 Clustering Analysis (Any one) 51
A.Implement K-Means clustering on Iris.csv dataset. Determine the number of
clustersusing the elbow method. Dataset Link:
https://www.kaggle.com/datasets/uciml/iris
B. Implement K-Mediod Algorithm on a credit card dataset. Determine the number
of clusters using the Silhouette Method. Dataset
link:https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

5 A5 Ensemble Learning (Any one)
A. Implement Random Forest Classifier model to predict the safety of the car.
Datasetlink: https://www.kaggle.com/datasets/elikplim/car-evaluation-data-set
B. Use different voting mechanism and Apply AdaBoost (Adaptive Boosting),
GradientTree Boosting (GBM), XGBoost classification on Iris dataset and compare the
performance of three models using different evaluation measures. Dataset Link:
https://www.kaggle.com/datasets/uciml/iris

6 A6 Reinforcement Learning (Any one)
A. Implement Reinforcement Learning using an example of a maze environment
that the agent needs to explore.
B. Solve the Taxi problem using reinforcement learning where the agent acts as a
taxi driver to pick up a passenger at one location and then drop the passenger off at
their destination.
C. Build a Tic-Tac-Toe game using reinforcement learning in Python by using
following tasks a. Setting up the environment b. Defining the Tic-Tac-Toe game c.
Building the reinforcement learning model d. Training the model e. Testing the
model


Part II: Data Modeling and Visualization
7 B2 Interacting with Web APIs
Problem Statement: Analyzing Weather Data from OpenWeatherMap API
Dataset: Weather data retrieved from OpenWeatherMap API
Description: The goal is to interact with the OpenWeatherMap API to
retrieve weather data for a specific location and perform data modeling and
visualization toanalyze weather patterns over time.
Tasks to Perform:
1. Register and obtain API key from OpenWeatherMap.
2. Interact with the OpenWeatherMap API using the API key to retrieve weather data
for aspecific location.
3. Extract relevant weather attributes such as temperature, humidity, wind speed, and
precipitation from the API response.

 Computer Laboratory –I BE (AI&DS)
4. Clean and preprocess the retrieved data, handling missing values or inconsistent
formats.
5. Perform data modeling to analyze weather patterns, such as calculating average
temperature, maximum/minimum values, or trends over time.
6. Visualize the weather data using appropriate plots, such as line charts, bar plots, or
scatter plots, to represent temperature changes, precipitation levels, or wind speed
variations.
7. Apply data aggregation techniques to summarize weather statistics by specific time
periods (e.g., daily, monthly, seasonal).
8. Incorporate geographical information, if available, to create maps or geospatial
visualizations representing weather patterns across different locations.
9. Explore and visualize relationships between weather attributes, such as temperature
and humidity, using correlation plots or heatmaps.

8 B3 Data Cleaning and Preparation
Problem Statement: Analyzing Customer Churn in a Telecommunications
Company
Dataset: "Telecom_Customer_Churn.csv"
Description: The dataset contains information about customers of a
telecommunicationscompany and whether they have churned (i.e., discontinued their
services). The dataset includes various attributes of the customers, such as their
demographics, usage patterns, and account information. The goal is to perform data
cleaning and preparation to gain insights into the factors that contribute to customer
churn.
Tasks to Perform:
1. Import the "Telecom_Customer_Churn.csv" dataset.
2. Explore the dataset to understand its structure and content.
3. Handle missing values in the dataset, deciding on an appropriate strategy.
4. Removeany duplicate records from the dataset.
5. Check for inconsistent data, such as inconsistent formatting or spelling variations,
andstandardize it.
6. Convert columns to the correct data types as needed.
7. Identify and handle outliers in the data.
8. Perform feature engineering, creating new features that may be relevant to
predictingcustomer churn.
9. Normalize or scale the data if necessary.
10. Split the dataset into training and testing sets for further analysis.
11. Export thecleaned dataset for future analysis or modeling.

9 B4 Data Wrangling
Problem Statement: Data Wrangling on Real Estate Market
Dataset: "RealEstate_Prices.csv

Description: The dataset contains information about housing prices in a specific real
estate market. It includes various attributes such as property characteristics, location,
saleprices, and other relevant features. The goal is to perform data wrangling to gain
insightsinto the factors influencing housing prices and prepare the dataset for further
analysis or modeling.
Tasks to Perform:
1. Import the "RealEstate_Prices.csv" dataset. Clean column names by removing
spaces,special characters, or renaming them for clarity.
2. Handle missing values in the dataset, deciding on an appropriate strategy (e.g.,
imputation or removal).
3. Perform data merging if additional datasets with relevant information are available
(e.g.,neighborhood demographics or nearby amenities).
4. Filter and subset the data based on specific criteria, such as a particular time
period,property type, or location.
5. Handle categorical variables by encoding them appropriately (e.g., one-hot
encoding orlabel encoding) for further analysis.
6. Aggregate the data to calculate summary statistics or derived metrics such as
averagesale prices by neighborhood or property type.
7. Identify and handle outliers or extreme values in the data that may affect the analysis
or modeling process
10 B5 Data Visualization using matplotlib
Problem Statement: Analyzing Air Quality Index (AQI) Trends in a City
Dataset: "City_Air_Quality.csv"
Description: The dataset contains information about air quality measurements in a
specific city over a period of time. It includes attributes such as date, time,
pollutant levels (e.g., PM2.5, PM10, CO), and the Air Quality Index (AQI) values.
The goal is to use the matplotlib library to create visualizations that effectively
represent the AQI trendsand patterns for different pollutants in the city.
Tasks to Perform:
1. Import the "City_Air_Quality.csv" dataset.
2. Explore the dataset to understand its structure and content.
3. Identify the relevant variables for visualizing AQI trends, such as date, pollutant
levels,and AQI values.
4. Create line plots or time series plots to vi visualize the overall AQI trend over time.
5. Plot individual pollutant levels (e.g., PM2.5, PM10, CO) on separate line plots to
visualize their trends over time.
Use bar plots or stacked bar plots to compare the AQI values across different dates
or time periods.
7. Create box plots or violin plots to analyze the distribution of AQI values for
differentpollutant categories.
8. Use scatter plots or bubble charts to explore the relationship between AQI values
andpollutant levels.
9. Customize the visualizations by adding labels, titles, legends, and appropriate color


Schemes
11 B6 Data Aggregation
Problem Statement: Analyzing Sales Performance by Region in a Retail Company
Dataset: "Retail_Sales_Data.csv"
Description: The dataset contains information about sales transactions in a retail
company. It includes attributes such as transaction date, product category, quantity
sold,and sales amount. The goal is to perform data aggregation to analyze the sales
performance by region and identify the top-performing regions.
Tasks to Perform: . Import the "Retail_Sales_Data.csv" dataset.
2. Explore the dataset to understand its structure and content.
3. Identify the relevant variables for aggregating sales data, such as region, sales
amount,and product category.
4. Group the sales data by region and calculate the total sales amount for each region.
5. Create bar plots or pie charts to visualize the sales distribution by region.
6. Identify the top-performing regions based on the highest sales amount.
7. Group the sales data by region and product category to calculate the total sales
amountfor each combination.
8. Create stacked bar plots or grouped bar plots to compare the sales amounts across
different regions and product categories.

### Part III: Mini Project(Mandatory Assignments)
12 Mini Project (Mandatory- Group Activity) It is recommended that group of 3 to 5 students should undergo a mini project (consideringthe Machine Learning and Data modeling and Visualizing concepts) as content beyond syllabus. Some of the problem statements are mentioned below:
1. Development of a happiness index for schools (including mental health and wellbeingparameters, among others) with self-assessment facilities.
2. Automated Animal Identification and Detection of Species
3. Sentimental analysis on Govt. Released Policies
4. Identification of Flood Prone Roads
5. Identification of Missing Bridges which would increase the connectivity between regions
Note: Instructor can also assign similar problem statementsReferences: For Dataset https://data.gov.in/ For Problem statements: https://sih.gov.in/sih2022PS