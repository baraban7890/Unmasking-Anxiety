# Unmasking Anxiety: The hidden groups of anxiety and depression since 2020

## Table of Contents
1. Project Overview
2. Objectives
3. Usage and Installation Instructions
4. Analysis and Insights
5. Data License and Fair Use
6. Potential Bias
7. End Goal
8. At-Risk Groups
9. Data Description
10. Methodology
11. Results
12. Conclusion and Recommendations
13. Contributors
14. Acknowledgments
15. Contact Information

## Project Overview
This project, conducted by Northwestern AI Bootcamp participants Alexander Baraban, Ryan Hough, and Michael Nicholas, aims to evaluate the frequency of weekly reported symptoms of anxiety since 2020, using data from the US Department of Health and Human Services.

**Dataset:** _[Indicators of Anxiety or Depression Based on Reported Frequency of Symptoms During Last 7 Days](https://catalog.data.gov/dataset/indicators-of-anxiety-or-depression-based-on-reported-frequency-of-symptoms-during-last-7-)_

## Objectives
**1. Trend Evaluation:** Assess trends within specific sub-categories of the population to explore the varying impacts of the COVID-19 lockdown on mental health.\
**2. Cause Identification:** Identify other potential causes of anxiety, such as holidays and seasonal changes, and interpret specific findings or correlations within the time series data.\
**3. Resource Planning:** Provide insights to clients to aid in evaluating key needs within the industry and planning resources to support the mental health of various demographic groups.

## Usage and Installation Instructions
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/project-1.git
cd project-1
Create a Virtual Environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Download the Dataset:
Download the dataset from Data.gov and place it in the data/ directory.

Usage
Run the Analysis Script:

bash
Copy code
python analysis.py
Generate Reports:
The results and insights will be saved in the output/ directory.

Jupyter Notebook:
You can explore the data and analysis by running the Jupyter notebook:

bash
Copy code
jupyter notebook analysis.ipynb

## Analysis and Insights
### Analysis 
Our analysis focused on understanding the trends and causes of anxiety symptoms since the COVID-19 lockdown. We performed the following steps:

* **Descriptive Statistics:** Calculated mean, median, and standard deviation of anxiety symptoms across different demographic groups.
* **Time Series Analysis:** Analyzed trends over time, focusing on periods during and after the lockdown.
* **Correlation Analysis:** Examined relationships between anxiety levels and potential influencing factors such as age, gender, and race.
* **Predictive Modeling:** Used machine learning models to predict groups at risk for anxiety symptoms.

### Insights
* Seasonal variations in anxiety symptoms.
* Differences across age groups, gender, and race.
* Impact of time periods during and after lockdown.

## Data License and Fair Use**
* This data is intended for public access and use, as per the website.
* The data has been sourced from Data.gov and provided through the US Department of Health and Human Services. Specific restrictions may exist regarding the use of text, trademarks, logos, and images, which have not been duplicated in this project.

## Potential Bias
* **Voluntary Response:** May underrepresent or overrepresent people with depression or anxiety symptoms.
* **Internet Questionnaire:** Households without internet, computers, phones, or emails are underrepresented.
* **Housing Units:** Underrepresents homeless individuals.
* **Single Respondent per Housing Unit:** Potential bias from only one respondent per unit.

## End Goal
The project's ultimate goal is to predict whether a group may be at risk for depressive or anxiety symptoms and provide insights to potential clients for resource allocation in mental health services.

## At-Risk Groups
* **By Age:** 18-29
* **By Gender Identity:** Transgrender
* **By Disability Status:** With Disability
* **By Sexual Orientation:** Bi-Sexual
* **By Race:** Non-Hispanic, other races and multiple races

## Data Description
The dataset used for this project is sourced from the US Department of Health and Human Services and contains indicators of anxiety or depression based on reported frequency of symptoms during the last seven days. Key features include:

* **Indicator** _Symptoms of Anxiety Disorder_, 
* **Subgroup:** Demographic subgroups (age, gender, race, state, ).
* **Anxiety Frequency:** The reported frequency of anxiety symptoms.
* **Depression Frequency:** The reported frequency of depression symptoms.
* **Weighted Percentage:** The weighted percentage of respondents reporting symptoms.

## Methodology
Overview of the analysis process, tools, and techniques used:

## Data cleaning and preprocessing
Feature engineering
Statistical analysis
Machine learning models
Validation methods
Results
Detailed findings with visualizations such as charts, graphs, and tables to illustrate key points.

## Conclusion and Recommendations
Summary of insights gained from the analysis and actionable recommendations for stakeholders.

## Contributors
* Alexander Baraban
* Ryan Hough
* Michael Nicholas

## Acknowledgments
Thank any individuals or organizations that contributed to the project.

## Contact Information
For questions or collaborations, please contact:

**Alexander Baraban** - alexbaraban17@gmail.com
**Ryan Hough** - hough.ryanj@gmail.com
**Michael Nicholas** - mpnicholas21@gmail.com