# Investigating Goal Differences in Men's and Women's FIFA World Cup Matches

## Project Overview

This project aims to explore whether **more goals are scored in women’s international soccer matches than in men’s**. As a sports journalist specializing in soccer analysis, you have been observing international soccer for years, and your intuition suggests that more goals are scored in women’s matches. To substantiate this hypothesis, you will conduct a statistical analysis using match results from official **FIFA World Cup matches** since **January 1st, 2002**.

The analysis will compare the number of goals scored in men's and women's matches using hypothesis testing at a **10% significance level**.

## Hypothesis Formulation

The question is framed in the context of hypothesis testing. You have defined the null and alternative hypotheses as follows:

- **Null Hypothesis (H₀)**: The mean number of goals scored in women's international soccer matches is **equal to** that of men's.
- **Alternative Hypothesis (H₁)**: The mean number of goals scored in women's international soccer matches is **greater than** that of men's.

## Dataset Description

Two datasets have been created for this analysis, containing results from international soccer matches. Both datasets include matches from the **official FIFA World Cup** (excluding qualifiers) since 2002:

- **`women_results.csv`**: Contains official women's FIFA World Cup match results.
- **`men_results.csv`**: Contains official men's FIFA World Cup match results.

### Columns

- **Date**: The date the match was played.
- **Home Team**: The team that played at home.
- **Away Team**: The visiting team.
- **Home Goals**: The number of goals scored by the home team.
- **Away Goals**: The number of goals scored by the away team.
- **Total Goals**: The total number of goals scored in the match (sum of home and away goals).

## Project Structure

```bash
.
├── data/
│   ├── women_results.csv   # Results of official women's FIFA World Cup matches
│   └── men_results.csv     # Results of official men's FIFA World Cup matches
├── src/
│   ├── analysis.py         # Python script for data analysis and hypothesis testing
├── results/
│   └── hypothesis_test.pdf # Report on hypothesis test results
├── README.md               # This README file
└── requirements.txt        # Python dependencies
```

## Steps to Follow

### 1. Exploratory Data Analysis (EDA)

Conduct an initial exploratory analysis of the datasets to:

- Inspect the distributions of goals scored in men’s and women’s matches.
- Identify potential outliers or trends in the data.
- Visualize the average goals scored per match for both genders.

### 2. Hypothesis Testing

Use the datasets to perform a one-sided **t-test** to determine if there is a statistically significant difference in the mean number of goals scored between men's and women's matches.

- Set a significance level (α) of **10%**.
- Calculate the mean and standard deviation of goals scored in both men's and women's matches.
- Perform the t-test and interpret the results.

### 3. Results

Summarize the findings of the hypothesis test, discussing whether the null hypothesis was rejected or not. Additionally, provide insights into any patterns found in the data.

## Dependencies

Install the required Python libraries using the following command:

```bash
pip install -r requirements.txt
```

### Key libraries:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **scipy**: For performing statistical hypothesis tests.
- **matplotlib**: For visualizing the data.

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/yourusername/goal-comparison-analysis.git
```

2. Navigate to the project directory:

```bash
cd goal-comparison-analysis
```

3. Run the analysis script:

```bash
python src/analysis.py
```

4. Check the **results** folder for the hypothesis test report.

## Conclusion

This analysis will reveal whether more goals are scored in women's international soccer matches compared to men's. The results will contribute valuable insights to your investigative article and enrich the understanding of trends in the international soccer world.

## License

This project is licensed under the MIT License.

---

Feel free to explore further questions and add more analysis to this project!
