# Titanic: Predicting Survival through Data

An exploratory dive into the most famous shipwreck in history. This project uses Python to clean, analyze, and visualize the Titanic passenger manifest to uncover the patterns behind who survived and who didn't.


The Dataset

I utilized the Titanic dataset from the Data Science Dojo, which includes:

- Demographics: Age, Sex, Name.

- Socio-economic: Pclass (Ticket Class), Fare.

- Family Ties: SibSp (Siblings/Spouses), Parch (Parents/Children).

- Logistics: Embarked (Port of departure), Cabin, Ticket.

# Data Cleaning Process

1 - Handling Missing Values - Age: Instead of deleting rows, I filled missing ages with the median to keep our distribution realistic.

Embarked: Filled missing ports with the mode (the most frequent port).

Cabin: With over 70% of data missing, this column was dropped to avoid skewing the analysis.

2 - Feature Engineering: I converted Sex and Embarked into numerical values (0 and 1) so they could be processed by mathematical models.


# Key Insights & Visualizations

1 - The Survival Gap
My analysis confirmed the grim reality: only about 38% of passengers survived. A simple count plot reveals the heavy toll of the disaster.

2 - Women and Children First
The data backs up the legend. By plotting survival rates against gender, I see a massive disparity—females had a significantly higher probability of survival compared to males.

3 - The Age Distribution
Most passengers were young adults (20-40 range). By overlaying survival on an age histogram, I can see "bumps" in survival for children, showing that age played a crucial role in rescue priority.

4 - Correlation Heatmap
The correlation matrix helps us see how variables interact. For instance, there's a clear negative correlation between Pclass and Fare (higher class = lower class number = higher fare), and a notable correlation between Sex and Survival.


# How to Run

1 - Clone the repo
2 - Install dependencies - pandas , numpy , seaborn , matplotlib
3 - Run the notebook


