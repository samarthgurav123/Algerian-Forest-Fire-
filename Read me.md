Project Overview: Algerian Forest Fires Dataset Analysis and Prediction

Situation
The Forest Department of Algeria faced a recurring challenge of forest fires, which caused significant environmental and economic damage. These fires were particularly prevalent during the dry season from June to September. The department sought an effective plan to manage and mitigate the impact of these fires through predictive modeling and data-driven decision-making.

Dataset Information
The dataset used for this analysis consisted of 244 instances, divided equally between two regions in Algeria: the Bejaia region in the northeast and the Sidi Bel-abbes region in the northwest. The data spanned from June 2012 to September 2012 and included 11 attributes along with an output attribute (class) indicating whether a fire occurred or not.

Attributes:
Date: (DD/MM/YYYY) - The date of the observation.

Temp: Temperature at noon (maximum temperature) in Celsius degrees (22 to 42).

RH: Relative Humidity in percentage (21 to 90).

Ws: Wind speed in km/h (6 to 29).

Rain: Total rainfall in mm (0 to 16.8).

Fine Fuel Moisture Code (FFMC): Index from the FWI system (28.6 to 92.5).

Drought Code (DC): Index from the FWI system (7 to 220.4).

Initial Spread Index (ISI): Index from the FWI system (0 to 18.5).

Buildup Index (BUI): Index from the FWI system (1.1 to 68).

Fire Weather Index (FWI): Index (0 to 31.1).

Classes: Two classes, namely Fire (138 instances) and Not Fire (106 instances).

Actions Taken

1. Data Cleaning
To ensure the dataset was suitable for analysis, the following data cleaning steps were performed:

Removing Null Values: Ensured no missing values were present in the dataset.
Removing Spaces from Column Names: Standardized column names by removing spaces.
Changing Data Types: Converted data types as necessary for analysis.
Dropping Unnecessary Columns: Removed columns that were not relevant to the analysis.
Encoding Categorical Columns: Encoded the 'Classes' column for model compatibility.

2. Exploratory Data Analysis (EDA)
Conducted a thorough exploratory data analysis to understand the dataset better and identify key patterns:

Classes Column Pie Chart: Visualized the distribution of fire and non-fire instances.
Correlation and Heatmap: Analyzed correlations between variables using a heatmap.
Box Plot: Examined the distribution and outliers of numerical attributes.
Monthly Fire Column Graph: Plotted the occurrence of fires across different months to identify seasonal patterns.

3. Regression Analysis
Developed and evaluated multiple regression models to predict the likelihood of forest fires based on the given attributes:

Defining Dependent and Independent Features: Identified target and predictor variables.
Train and Test Split: Split the dataset into training and testing sets.
Multicollinearity Check: Assessed multicollinearity among predictors.

Standardization: Standardized the features to improve model performance. Visualized box plots before and after standardization to understand the impact.
Model Building and Evaluation: Built and evaluated the following regression models using metrics such as Mean Absolute Error (MAE) and R-squared (R²), along with scatter plots to visualize predictions:
Linear Regression
Lasso Regression
Ridge Regression
Elastic Net Regression
Responsibilities

My role involved the following responsibilities:

Data Preprocessing: Managed data cleaning and preparation for analysis.
Exploratory Data Analysis: Conducted EDA to uncover insights and inform model building.
Feature Engineering: Developed and selected relevant features for the models.
Model Building: Built and evaluated linear regression, Lasso, Ridge, and Elastic Net regression models using Python and libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

Communication: Communicated findings and model results to the Algerian Forest Department, providing actionable insights for resource allocation and fire prevention strategies.
Results
The predictive models achieved high accuracy in identifying conditions conducive to forest fires. The key results included:

Improved Resource Allocation: The models enabled the department to allocate resources more efficiently, focusing on high-risk periods and regions.
Proactive Fire Hazard Response: By predicting potential fire occurrences, the department could implement proactive measures, significantly reducing the incidence of forest fires.

Enhanced Decision-Making: The analysis and models provided the department with data-driven insights, aiding in better decision-making for forest management and fire prevention.

The successful implementation of this project demonstrated the power of data analysis and predictive modeling in addressing real-world challenges, ultimately contributing to the conservation of Algeria's forests and reducing the impact of forest fires.
