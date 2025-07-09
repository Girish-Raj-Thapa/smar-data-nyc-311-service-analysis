# Data Analysis Project

## Project Overview

This project presents an in-depth analysis of a complaint dataset aimed at understanding patterns in complaint types, response times, and geographic distribution. The analysis is structured into several key phases: Data Understanding, Data Preparation, Data Analysis, Data Exploration, Statistical Testing, and Conclusion. Each phase builds on the previous to deliver actionable insights and validate hypotheses.

---

## Data Understanding

The initial step involved familiarizing with the dataset by examining its structure, sources, and collection methods. Understanding how the data was gathered and who uses it helped define the scope and objectives of the analysis. Key insights were drawn by reviewing the dataset’s attributes and identifying relevant stakeholders and potential use cases.

---

## Data Preparation

After gaining familiarity, the dataset was imported into the working environment. Data cleaning tasks included:

- Handling date-time columns and calculating request closing durations to derive meaningful time-based metrics.  
- Dropping irrelevant or redundant columns that did not contribute to the analysis goals.  
- Removing missing (NaN) values to ensure data quality and avoid skewed results.  
- Extracting unique values from each column to better understand the range and distribution of categorical data.

These steps prepared the dataset for reliable and accurate analysis.

---

## Data Analysis

With a clean dataset, the next phase involved generating summary statistics to describe the central tendencies and variability within the data. Correlation analyses were conducted to explore relationships among different variables, identifying which factors might influence complaint response times or volumes.

---

## Data Exploration and Visualization

Visualizations played a crucial role in uncovering trends and communicating findings effectively:

- **Bar Chart:** Displayed the top ten complaint types to highlight the most frequent issues.  
- **Pie Chart:** Showed complaint distribution across boroughs to understand geographic spread.  
- **Bar Chart:** Illustrated average request closing times by complaint type, revealing service efficiency variations.  
- **Line Chart:** Tracked monthly trends for the top five complaint types, indicating seasonal or temporal fluctuations.

These graphical representations helped identify patterns that might be less obvious in raw data.

---

## Statistical Testing

To validate the observed patterns, two main statistical tests were performed:

- **Test 1:** Examined whether the average response time differs significantly among complaint types, using appropriate statistical methods.  
- **Test 2:** Investigated the relationship between complaint types and their locations, assessing if certain complaints are location-dependent.

These tests strengthened the conclusions drawn from exploratory analyses by providing statistical evidence.

---

## Conclusion

The project culminated in key insights about complaint management, highlighting areas needing attention and suggesting potential improvements in operational processes. Additionally, the experience enhanced skills in data handling, visualization, and statistical reasoning. Future work could extend this analysis by incorporating additional data sources or advanced modeling techniques.

---

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/data-analysis-project.git
   
2. Then open the Project using Jupyter notebook or Anaconda(recommended)

## License

This project is licensed under the MIT License. See the LICENSE file for details.



