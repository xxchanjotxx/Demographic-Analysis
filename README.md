# Demographic-Analysis

Exploring the 1994 USA demographic census data to answer the following questions:
- How many people of each race are represented in this dataset?
- What is the average age of men?
- What is the percentage of people who have a Bachelor's degree?
- What percentage of people with advanced education (Bachelors, Masters, or Doctorate) make more than 50K?
- What percentage of people without advanced education make more than 50K?
- What is the minimum number of hours a person works per week?
- What percentage of the people who work the minimum number of hours per week have a salary of more than 50K?
- What country has the highest percentage of people that earn >50K and what is that percentage?
- Identify the most popular occupation for those who earn >50K in India.

## Data: 
---

| Variable         | Data Type |
|------------------|-----------|
| age              | int64     |
| workclass        | object    |
| fnlwgt           | int64     |
| education        | object    |
| education-num    | int64     |
| marital-status   | object    |
| occupation       | object    |
| relationship     | object    |
| race             | object    |
| sex              | object    |
| capital-gain     | int64     |
| capital-loss     | int64     |
| hours-per-week   | int64     |
| native-country   | object    |
| salary           | object    |

---
## Analysis:

- Number of each race:
| Race               | Count |
|-------------------|-------|
| White             | 27816 |
| Black             | 3124  |
| Asian-Pac-Islander| 1039  |
| Amer-Indian-Eskimo| 311   |
| Other             | 271   |
- Average age of men: 39.4
- Percentage with Bachelors degrees: 16.4%
- Percentage with higher education that earn >50K: 46.5%
- Percentage without higher education that earn >50K: 17.4%
- Min work time: 1 hours/week
- Percentage of rich among those who work fewest hours: 10.0%
- Country with highest percentage of rich: Iran
- Highest percentage of rich people in country: 41.9%
- Top occupations in India: Prof-specialty

