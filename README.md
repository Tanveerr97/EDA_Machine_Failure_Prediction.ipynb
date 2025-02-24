# Project Summary: Machine Failure Prediction and Maintenance Optimization #

* Data Preparation and Cleaning:

Imported data using pandas and performed data wrangling to handle missing values, outliers, and ensure data consistency.
Utilized exploratory data analysis (EDA) on the training data to avoid data leakage and ensure unbiased model evaluation.

* Exploratory Data Analysis (EDA):

Analyzed the distribution of key features like Torque [Nm], Tool wear [min], Rotational speed [rpm], Air temperature [K], and Process temperature [K] using KDE plots and pair plots.
Discovered multimodal and bimodal distributions in Air temperature [K] and Process temperature [K], respectively, indicating different operational modes.
Highlighted the normal distribution of Torque [Nm] and the uniform distribution of Tool wear [min] to guide maintenance planning.

* Product ID Prioritization for Maintenance:

Identified high-failure products such as L53258, L49305, and L55686 for priority maintenance.
Monitored consistent failure patterns in products like M18795 and L54716 for proactive maintenance.
Suggested using bar plots or heatmaps to visualize product failure rates.

* Failure Type Analysis:

Analyzed machine failure types (TWF, HDF, PWF, OSF, RNF) to optimize maintenance strategies.
Focused on RNF and OSF as the most common failures, while moderately prioritizing PWF and HDF.
Recommended using pie or stacked bar charts for better visualization of failure type distributions.

* Temperature and Torque Relationships:

Found a strong positive correlation between Air Temperature [K] and Process Temperature [K], advising joint management of temperature control systems.
Identified a moderate correlation between Torque [Nm] and machine failures, emphasizing torque management to reduce stress and improve reliability.
Suggested scatter plots with trend lines to visualize these correlations.

* Machine Type Analysis:

Evaluated machine types (H, L, M) based on operational temperatures:
Type H: Low temperature, energy-efficient, requires monitoring for inefficiencies.
Type L: High temperature, ideal for demanding tasks, needs temperature management.
Type M: Balanced temperature, offers stable performance with lower maintenance needs.
Proposed box plots or violin plots for comparing temperature distributions across machine types.

* Targeted Maintenance Based on Torque Ranges:

Highlighted failure-prone torque range (22-60 Nm) and identified stress levels through torque fluctuations.
Recommended histogram plots to monitor torque ranges for operational efficiency.

* Predictive Modeling with Random Forest:

Utilized Random Forest Classifier to predict machine failure, achieving valuable insights into influential features like Torque [Nm] and Rotational speed [rpm].
Prioritized maintenance tasks and optimized resource allocation to enhance operational efficiency.
Suggested model tuning using GridSearchCV and feature importance analysis for better model performance.

* Business Impact:

Proposed data-driven maintenance strategies to reduce machine downtime, improve productivity, and achieve cost savings.
Focused on long-term sustainability and machine optimization through predictive maintenance and proactive operational adjustments.

#python #Jupyternotebook #tatasteel #MachineFailurePrediction
