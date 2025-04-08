Applied Data Science Capstone

🚀 SpaceX First Stage Landing Prediction

📄 Project Background

SpaceX has revolutionized space travel by making it more affordable, primarily through the reuse of Falcon 9 rocket first stages. With a launch cost of $62 million compared to over $165 million by other providers, much of the cost savings come from the ability to land and reuse the rocket's first stage. The objective of this project is to predict whether SpaceX will be able to successfully reuse the first stage of the Falcon 9, based on various factors such as payload mass, launch site, number of flights, and orbits.

The goal is to use machine learning models to predict the likelihood of a successful first stage landing, which directly impacts the cost-effectiveness of the mission.

📄 Questions to be answered

How do variables like payload mass, launch site, number of flights, and orbits affect the success of the first stage landing?

Does the rate of successful landings improve over time?

What is the best algorithm for predicting the binary classification (success or failure) of the first stage landing?

📄 Methodology

1. Data Collection Methodology
   SpaceX REST API: Data was collected directly from SpaceX's public API for mission details, rocket launches, and other related information.

Web Scraping from Wikipedia: Additional data on launches and outcomes was gathered using web scraping techniques from relevant Wikipedia pages.

2. Data Wrangling
   Filtering the Data: Only relevant data points were filtered for analysis, focusing on the key attributes that affect landing success.

Handling Missing Values: Missing values were identified and managed using imputation techniques to avoid skewing the analysis.

One Hot Encoding: Categorical features were transformed into binary format using One Hot Encoding to prepare the dataset for machine learning models.

3. Exploratory Data Analysis (EDA)
   Visualization: Data was analyzed and visualized to discover patterns and relationships between features, using libraries like matplotlib and seaborn.

SQL: SQL queries were used to query and summarize the data for deeper insights.

4. Interactive Visual Analytics
   Folium: Geographic data was visualized using Folium maps to explore the proximity of launch sites to various regions.

Plotly Dash: A dashboard was created to enable interactive analytics, allowing users to explore launch site data, success rates, and payload ranges dynamically.

5. Predictive Analysis
   Classification Models: Various machine learning algorithms were used to predict the success of the first stage landing. These included:

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

Model Evaluation: Models were tuned and evaluated to select the best-performing one, with a focus on accuracy, precision, recall, and F1-score.

🛠 Tools and Technologies Used

Python: Core programming language used for data wrangling, analysis, and machine learning.

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, folium

APIs: SpaceX REST API

SQL: Used for data extraction and aggregation

Web Scraping: BeautifulSoup and requests for scraping data from Wikipedia.

🎯 Objectives

Predict the likelihood of a successful first-stage landing based on various mission parameters.

Evaluate the success of SpaceX's Falcon 9 launches and landings.

Explore how historical data and predictive models can optimize space missions and reduce costs.

📈 Results

The final model achieved high accuracy in predicting successful first-stage landings, and insights were gained into the key factors influencing landing success. This analysis can be used to further optimize SpaceX’s operations and reduce launch costs by predicting when first-stage reuse is likely.
