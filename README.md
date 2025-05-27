# Kosada-Bhat-ElevateLabs-TASK2

# TASK2: EDA

Exploratory Data Analysis (EDA)
A thorough EDA was conducted to understand the dataset's structure, uncover patterns, and identify important features influencing survival.

🔹 Summary Statistics
Descriptive statistics (mean, median, standard deviation, etc.) were generated for numerical features such as Age, Fare, SibSp, and Parch. These helped in understanding central tendencies and distributions. For categorical features like Sex and Embarked, value counts and frequencies were calculated to assess class imbalance.

🔹 Data Visualization
Histograms revealed the skewness in Fare and the distribution of Age.

Boxplots were used to detect outliers and compare the distribution of numeric features across survival status.

Count plots and bar charts highlighted survival trends across categorical features like Sex, Pclass, and Embarked.

A correlation matrix heatmap identified relationships between numeric features.

A pairplot helped visualize interactions between multiple variables and their relation to survival.

🔹 Key Insights
Gender and class were the strongest indicators of survival. Females and 1st class passengers had the highest survival rates.

Younger passengers, particularly children, showed better survival chances.

Higher fare amounts generally correlated with higher survival, likely due to better accommodations and priority.

Passengers who embarked from Cherbourg had higher survival, which may be tied to the class they traveled in.

Small families (1–2 members aboard) had better survival outcomes than solo travelers or those in large groups.

These insights were critical in guiding the feature selection and engineering process for the next phase of model building.
