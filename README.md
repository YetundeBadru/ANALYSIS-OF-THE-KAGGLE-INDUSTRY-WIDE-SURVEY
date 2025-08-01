# ANALYSIS-OF-THE-KAGGLE-INDUSTRY-WIDE-SURVEY

This repository contains an in-depth analysis of the Kaggle Industry-Wide Survey, providing a comprehensive view of the state of data science and machine learning. The project focuses on processing and extracting insights from the 2019 survey, which gathered over 19,000 responses.

---

# About the Project

Every year, Kaggle conducts an industry-wide survey that presents a comprehensive view of the state of data science and machine learning. The 2019 survey was live for three weeks in October 2019, with over 19,000 responses. The results include raw numbers about who is working with data, what’s happening with machine learning in different industries, and the best ways for new data scientists to break into the field.

---

# Key Features

- Data Loading and Initial Exploration: Reads the raw survey data into a pandas DataFrame and displays the first few rows to understand its structure.

- Column Subsetting: Selects and focuses on the first 11 relevant columns for detailed analysis.

- Column Renaming: Renames the subsetted columns for clarity and ease of analysis, using descriptive labels based on the column's content.
  - Duration(secs): The amount of time taken to complete the survey.
  - Age: Age of the respective respondents.
  - Gender: Gender of the respective respondents.
  - Gender_(Other): Alternative gender category, if any.
  - Country: Country of residence of the respective respondents.
  - Education: The educational level of the respective respondents.
  - Job_title: The current job role of each respondent.
  - Job_title(Other): An alternative job role, if any.
  - company_size: The size of the respondent's company/employer.
  - dataScience_team: The employee's experience using the employee's workload.
  - ML_adoption: Indicates whether the respondent's current company/employer adopts Machine Learning in their business.

- Country-wise Educational Level Analysis: Subsets the dataframe to include one country from all continents (excluding Antarctica) to analyze educational levels.

---

# Technologies Used

- Python
- Pandas
- Numpy
- Jupyter Notebook

---

# Installation and Usage
To run this analysis, you will need to have Python installed along with the required libraries.

1. Clone the repository (or download the notebook):

       git clone <repository_url>
---
2. Navigate to the project directory:

       cd Yetunde_Badru_Kaggle_Industry_Wide_Survey
---
3. Install the necessary libraries:

       pip install pandas numpy
---
4. Download the dataset:

The project uses the 2019multiple_choice_responses.csv file. Ensure this CSV file is placed in the same directory as the Jupyter Notebook. You can typically find this dataset on Kaggle's official survey page.
---
5. Open and run the Jupyter Notebook:

       jupyter notebook "Yetunde_Badru_Kaggle_Industry_Wide_Survey.ipynb"

**Note: Follow the cells in the notebook to reproduce the analysis.**

---

# General Insights from all 3 Countries (France, India and South Africa)

- India and South Africa have the highest number of individuals with a bachelor's degree.
- All three countries have the highest number of individuals with a master's degree.
- They all have a low number of advanced degrees, which explains that individuals mostly get jobs with their bachelor's and master's degrees.

---

# Contributing
Feel free to fork this repository, contribute, and suggest improvements.

---

# Acknowledgments
- Dataset from Kaggle
- Tools from Python’s data science ecosystem

---

# Author
Yetunde Badru Data Scientist | AI/ML| AWS Cloud Practitioner

LinkedIn: www.linkedin.com/in/yetundebarakbadru

Email: yetundebarakbadru@gmail.com
