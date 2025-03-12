# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Security Breach Analysis

Security Breach Analysis is a comprehensive data analysis project designed to explore, analyse, and visualise cybersecurity attack data. The project aims to provide valuable insights into security threats, attack patterns, and their impact using various data analysis techniques and visualisations.

Dataset Content

The dataset used in this project consists of cybersecurity attack logs, including information such as timestamps, attack types, severity levels, geolocation data, traffic types, and anomaly scores. The dataset helps identify attack trends, analyze threat severity, and generate actionable insights for cybersecurity professionals.

Business Requirements

Identify and categorize different types of cybersecurity attacks.

Assess the severity and frequency of security breaches over time.

Analyze geographical distribution of attacks to pinpoint high-risk areas.

Build predictive models to anticipate potential security threats.

Provide interactive data visualisations for cybersecurity decision-makers.

Hypothesis and Validation

Hypothesis 1: Cybersecurity attacks occur more frequently during peak business hours.

Validation: Analyse attack timestamps and compare attack frequency across different hours.

Hypothesis 2: Specific attack types, such as DDoS, are more severe than others.

Validation: Compare severity levels associated with different attack types.

Hypothesis 3: High-traffic network segments are more prone to cyberattacks.

Validation: Examine correlations between traffic type and attack occurrences.

Project Plan

Data Collection: Load the dataset and handle missing values.

Data Cleaning & Transformation: Standardize columns, extract geolocation information, and categorize severity levels.

Exploratory Data Analysis (EDA): Generate descriptive statistics and detect patterns in the dataset.

Data Visualisation: Create interactive plots, time series graphs, and geo-visualisations.

Predictive Modeling: Build machine learning models for anomaly detection and severity prediction.

Dashboard Development: Design an intuitive dashboard for cybersecurity insights.

Evaluation & Reporting: Summarize findings and assess the effectiveness of the models and visualisations.

Mapping Business Requirements to Data Visualisations

Business Requirement

Data Visualisation

Identify attack types

Bar charts, pie charts

Assess severity levels

Donut charts, stacked bar plots

Geographical distribution of attacks

Scatter maps, choropleth maps

Attack frequency over time

Time series line charts

Predictive modeling of security threats

Regression plots, classification reports

Analysis Techniques Used

Exploratory Data Analysis (EDA): Summary statistics, distribution plots, and correlation analysis.

Regression Analysis: Evaluating relationships between network traffic and anomaly scores.

Classification Models: Using Random Forest for severity level prediction.

Geospatial Analysis: Mapping attack locations with interactive geo-plots.

Time Series Analysis: Identifying attack trends over time.

Limitations & Challenges:

Missing or incomplete geolocation data.

Class imbalance in attack severity levels.

Potential bias in dataset sampling.

Ethical Considerations

Data Privacy: No personally identifiable information (PII) is used.

Bias & Fairness: Ensured data-driven insights without manipulation.

Security Compliance: Adhered to cybersecurity best practices while handling sensitive attack data.

Dashboard Design

Home Page: Overview of security breaches and attack summaries.

Attack Analysis: Visualizations for attack types, severities, and trends.

Geospatial Insights: Interactive maps showing attack locations.

Predictive Insights: Anomaly detection and security threat predictions.

User Interaction Features: Filters, drill-down capabilities, and customizable views.

Unfixed Bugs

Geolocation Mapping Issues: Some attacks lack valid city/state information, leading to missing data points in maps.

Class Imbalance in Predictive Models: Some attack types have limited data, affecting prediction accuracy.

Dashboard Performance on Large Datasets: Rendering interactive visualizations may slow down with high data volumes.

Future Improvements:

Enhance dataset quality by incorporating real-time threat intelligence feeds.

Implement additional machine learning models for improved anomaly detection.

Optimize dashboard performance for large-scale security datasets.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.