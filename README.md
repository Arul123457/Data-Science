# Data-Science


1. Data Exploration and Preprocessing

Data Inspection:
Understanding and using methods like df.head(), df.info(), and df.describe() to get a quick overview of the dataset.
Identifying the number of rows and columns using df.shape.

Handling Missing Values:
Detecting missing values using df.isnull().sum().
Filling missing values in categorical columns with the mode using df['column'].fillna(df['column'].mode()[0], inplace=True).

Data Type Conversion:
Converting data types of columns as needed, for example, using df['column'] = df['column'].astype('int').


2. Feature Engineering

Creating New Features:
Extracting new features like the length of the restaurant name using df['Name Length'] = df['Name'].apply(len).
Creating binary encoded features from categorical variables using lambda functions.

Encoding Categorical Variables:
Using LabelEncoder to encode categorical variables, for instance, df['Price Range Encoded'] = LabelEncoder().fit_transform(df['Price Range']).
Descriptive Analysis

Basic Statistical Measures:
Calculating mean, median, standard deviation, etc., for numerical columns using methods like df['column'].mean() and df['column'].std().

Analyzing Distributions:
Using histograms to understand the distribution of numerical variables.


3. Predictive Modeling

Model Building:
Building regression models using algorithms like Linear Regression, Decision Trees, and Random Forests.

Model Evaluation:
Splitting the dataset into training and testing sets using train_test_split.
Evaluating models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).


4. Data Visualization

Plotting with Matplotlib:
Creating various types of plots such as histograms, bar plots, scatter plots, and box plots to visualize data and relationships between variables.
Customizing plots with titles, labels, grids, and annotations.

Geospatial Analysis:
Mapping:
Visualizing geographical data using latitude and longitude information on maps (e.g., using folium or other mapping libraries).


5. Domain-Specific Analysis

Customer Preference Analysis:
Analyzing the relationship between cuisine types and ratings.
Identifying popular cuisines based on votes.
Determining cuisines that tend to receive higher ratings.


6. Programming and Libraries

Python Programming:
Enhancing my Python programming skills by writing and understanding scripts and functions.

Pandas:
Extensive use of Pandas for data manipulation and analysis.

Scikit-Learn:
Using Scikit-Learn for machine learning tasks, including model building, evaluation, and preprocessing.

Matplotlib:
Creating and customizing plots for data visualization.
