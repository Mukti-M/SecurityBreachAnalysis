# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Security Breach Analysis

Security Breach Analysis is a comprehensive data analysis project designed to explore, analyse, and visualise cybersecurity attack data. The project aims to provide valuable insights into security threats, attack patterns, and their impact using various data analysis techniques and visualisations.

<img src="security-alert.jpg" alt="Security Alert" height="300" width= "800" style="box-shadow: 5px 5px 10px gray;">

# Dataset Content

The dataset contains 40,000 records with 25 columns related to cybersecurity attacks, including IP addresses, ports, protocols, attack types, severity levels, timestamps, and network segments. The dataset is cleaned and preprocessed to facilitate in-depth analysis and visualisation of security breaches.
### The objective of this project -
1. Identify patterns and trends in cybersecurity breaches.
2. Detect anomalies and categorize different attack types.
3. isualise attack distribution geographically.
4. Predict the severity of attacks based on traffic and anomaly scores.


# Hypothesis and Validation

#### Hypothesis 1 -

Null Hypothesis (H0): There is no significant relationship between the type of traffic and the anomaly scores.
#### Validation: Perform regression analysis and evaluate the mean squared error (MSE).

#### Hypothesis 2 -

Null Hypothesis (H0): The severity level of cyber attacks is independent of the traffic type and anomaly scores.
#### Validation: Build a predictive model (e.g., Random Forest) and evaluate its accuracy.

#### Hypothesis 3 -

Null Hypothesis (H0): The distribution of cyber attacks is uniform across different cities and states.
#### Validation: Analyse the geographical distribution of attacks using visualisations and statistical tests.

#### Hypothesis 4 -

Null Hypothesis (H0): DDoS attacks do not show any specific trend over time.
#### Validation: Analyse DDoS attack trends over time using line charts and heatmaps.

# Project Plan

#### 1. Data Collection: Load the dataset and handle missing values.

#### 2. Data Cleaning & Transformation: Standardize columns, extract geolocation information, and categorize severity levels.

#### 3. Exploratory Data Analysis (EDA): Generate descriptive statistics and detect patterns in the dataset.

#### 4. Data Visualisation: Create interactive plots, time series graphs, and geo-visualisations.

#### 5. Predictive Modeling: Build machine learning models for anomaly detection and severity prediction.

#### 6. Dashboard Development: Design an interactive dashboard for cybersecurity insights.

#### 7. Evaluation & Reporting: Summarize findings and assess the effectiveness of the models and visualisations.

#### 8. Mapping Business Requirements to Data Visualisations

# Business Requirement :-

|   Data Analysis   | Visualisation Model       | 
| ------------- |:-------------:| 
|Identify attack types     |  Bar charts, pie chart| 
| Assess severity levels      |  Donut charts, stacked bar plots  |   
| Geographical distribution of attacks |  Scatter Map    |    
| Attack frequency over time |  Time series line charts |
| Predictive modeling of security threats |  Regression plots, Classification Reports |

# Analysis Techniques Used :-

* Exploratory Data Analysis (EDA) - Summary statistics, distribution plots, and correlation analysis.

* Regression Analysis - Evaluating relationships between network traffic and anomaly scores.

* Classification Models - Random Forest classifier used to predict attack severity levels.

* Time Series Analysis - Identifying attack trends over time.

* Geospatial Analysis - Mapping attack locations with interactive geo-plots.

# Limitations & Challenges :-

1. Missing or incomplete geolocation data.

2. Class imbalance in attack severity levels.

3. Potential bias in dataset sampling.

# Ethical Considerations
1. Data Privacy: No personally identifiable information (PII) is used.

2. Bias & Fairness: Ensured data-driven insights without manipulation.

3. Security Compliance: Adhered to cybersecurity best practices while handling sensitive attack data.

# Power BI Dashboard Design

The purpose of this Power BI report is to

Analyse cybersecurity attack patterns based on geo-location and network traffic data.
Identify the most attacked cities and states.
Categorize attacks based on severity level and traffic type.
Provide insights into intrusion attempts, malware incidents, and DDoS attacks.
Visualise attack trends over time to aid in proactive threat detection.

### Hypothesis Statements

1. Higher attack rates in urban areas - Cybersecurity attacks are more frequent in densely populated cities due to higher digital infrastructure.
2. DDoS attacks dominate high-traffic regions - Locations with high internet usage are more prone to Distributed Denial of Service (DDoS) attacks.
3. Severity levels are correlated with attack type - More sophisticated attacks like malware and intrusion attempts have a higher severity rating.
4. Certain traffic types are more vulnerable - HTTP and DNS traffic are more likely to be exploited in cyber-attacks than other protocols.
5. Attack frequency follows seasonal patterns - Cybersecurity incidents increase during specific timeframes, such as year-end or holiday seasons.

### Key Features & Findings -
KPI Metrics:
Total attack count: 406 (Example Value)
Most attacked city: Agra (Example Value)
Most common traffic type targeted: DNS
Most frequent attack type: DDoS

Time Series Analysis:-
Attack frequency fluctuates, with notable spikes in March, July, and November.
Trendlines suggest periodic surges, possibly linked to global cyber incidents.

Geo-Location Insights:-
Cyberattacks are concentrated in Agra, Ahmedabad, and Allahabad.
The highest attack densities are in urban areas.

Attack Type Breakdown:-
DDoS attacks account for the largest share of incidents.
Malware and intrusion attacks are significant, indicating the need for stronger endpoint security.
Network Segment Analysis:-
Segments A and C experience higher attack volumes, suggesting vulnerabilities in specific network sections.

![alt text](<SecurityBreachAnalyser Dashboard.png>)

##### Next Steps
1. Implement predictive analytics to forecast attack trends.
2. Enhance real-time monitoring using Power BI alerts.
3. Integrate AI-driven anomaly detection for proactive threat mitigation.

### Unfixed Bugs

1. Geolocation Mapping Issues: Due to PowerBI trial period limitations, Map did not used for geolocation analysis in Power BI report.
2. Class Imbalance in Predictive Models - Some attack types have limited data, affecting prediction accuracy.
3. Dashboard Performance on Large Datasets- Rendering interactive visualisations may slow down with high data volumes.

### Future Improvements:

1. Enhance dataset quality by incorporating real-time threat intelligence feeds.
2. Implement additional machine learning models for improved anomaly detection.
3. Optimise dashboard performance for large-scale security datasets.

## Main Data Analysis Libraries

* pandas: Used for data manipulation and analysis.
* numpy: Used for numerical operations.
* plotly: Used for interactive visualisations.
* seaborn: Used for statistical visualisations.
* scikit-learn: Used for predictive modeling and regression analysis.

## Credits

#### Content
* The text for this project was sourced from various references, including ChatGPT for formatting summaries and Kaggle for dataset information.

* Instructions on how to implement the dashboard were followed from this YouTube tutorial, which helped me understand how to create interactive Power BI reports.
1. https://www.youtube.com/watch?v=H84UJn1CiWo&list=PL6Omre3duO-OGTAMuFuDOS8wMuuxmyaiX
2. https://www.youtube.com/watch?v=wZATWjV4scg&list=PL6Omre3duO-OGTAMuFuDOS8wMuuxmyaiX&index=3

* The code for the data analysis was implemented with the assistance of various AI tools, such as ChatGPT and Perplexity etc.

#### Media
* The photos and logos used in this project were taken from open-source sites like Google etc.
  https://pixabay.com/photos/security-alarm-monitor-cyber-5043368/

## Acknowledgements

I want to thank my instructors and peers for their helpful feedback and support throughout this project.
A special thanks to Vasi and Paul for their guidance and support. Finally, I am very grateful to my family for encouraging me and keeping me motivated to finish the project on time.