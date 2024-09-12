# StackOverflow 2017 Survey Analysis

This repository contains an exploratory data analysis (EDA) of the Stack Overflow 2017 Developer Survey dataset. The project was conducted as part of Udacity's Data Science Nanodegree and aims to provide insights into programming language preferences, job satisfaction, and career satisfaction among developers.

## Project Goals
The primary goal of this project is to answer three key business-related questions:
1. **What are the most popular programming languages among developers with different experience levels?**
2. **What factors influence developer job satisfaction?**
3. **What factors contribute to developer career satisfaction?**

## Dataset
The dataset used in this project is the [Stack Overflow 2017 Developer Survey](https://www.kaggle.com/datasets/stackoverflow/so-survey-2017). The analysis was conducted on a subset of the data focusing on specific attributes related to the research questions.

## Structure of the Repository
- **`data/`**: Contains the dataset used for the analysis.
- **`notebooks/`**: Jupyter Notebooks with the data cleaning, analysis, and visualizations.
- **`visualizations/`**: Plots and charts generated during the analysis.
- **`scripts/`**: Python scripts that support the Jupyter Notebooks.
- **`reports/`**: PDF reports and other documentation summarizing the results.


## Installation
To run the notebooks, make sure you have the following Python libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install them using the following command:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Analysis
1. Popular Programming Languages by Experience Level
We analyzed the most frequently used programming languages based on the years of programming experience. A heatmap visualization was created to show language preference shifts among developers with different experience levels.

- Key Insights:

  - C and C++ are more commonly used by developers with 17+ years of experience, reflecting their long-standing presence.
  - Python and JavaScript dominate among developers with less than 10 years of experience.
  - Languages like CoffeeScript and Dart have very low adoption across all experience levels.

2. Factors Influencing Job Satisfaction
We explored the correlation between Job Satisfaction and Career Satisfaction. The analysis found a significant positive correlation of 0.65, indicating that career satisfaction plays an important role in overall job satisfaction.

- Key Insights:

  - Developers satisfied with their careers tend to also be satisfied with their jobs.
  - Companies can improve job satisfaction by investing in career development and growth opportunities.

3. Factors Contributing to Career Satisfaction
We examined how factors like Formal Education and Years of Programming Experience impact career satisfaction. The analysis suggests that neither education level nor years of experience significantly influence career satisfaction.

- Key Insights:

  - Developers with different education levels (Bachelor’s, Master’s, PhD) show minimal variations in career satisfaction.
  - Years of programming experience also does not guarantee higher career satisfaction.

## Results
- Programming language preferences vary with experience: senior developers tend to use older languages (e.g., C, C++), while junior developers prefer modern languages (e.g., Python, JavaScript).
- Job satisfaction is significantly influenced by career satisfaction, making career development a critical area for employers to focus on.
- Career satisfaction does not strongly correlate with formal education or programming experience, suggesting that other factors, such as work-life balance and personal interests, might be more influential.

These results provide valuable insights for companies in the tech industry, especially for recruitment and employee retention strategies.

## License

This project includes the following licenses:

- **Dataset License:** The Stack Overflow 2017 Developer Survey dataset is licensed under the [Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/dbcl/1-0/). See the dataset's page on Kaggle for details.

- **Code License:** The code in this repository is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file in this repository for details.

## Acknowledgments
Thanks to Udacity for the Data Science Nanodegree program and Stack Overflow for the data.
