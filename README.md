# Data Science Assignment – Phase 0

This repository includes three mini-projects completed as part of the **Introduction to Data Science - CA0** assignment. Each task is based on real-world data and aims to apply fundamental data science concepts such as probability theory, statistical inference, and simulation.

---

## 1. Roulette Simulation and Profit Analysis

**Objective**: Simulate the outcome of repeatedly betting on "black" in American roulette, evaluate the risk to the casino, and explore the Central Limit Theorem.

### Key Concepts:

- **Monte Carlo Simulation**: Used to simulate thousands of repetitions of roulette spins.
- **Expected Value Calculation**: Comparison of theoretical vs simulated average earnings per round.
- **Central Limit Theorem (CLT)**: Demonstrates how the distribution of sample means becomes normal with increasing sample size.
- **Risk Analysis**: Calculated the probability of the casino ending up with a net loss after a large number of bets.

### Implementation Highlights:

- Simulated the outcomes of 10, 25, 100, and 1000 rounds of betting.
- Visualized distributions of winnings and calculated variance.
- Estimated the probability that the casino loses money at different levels of N.
- Conclusions were drawn about how increasing N reduces the casino's risk.

---

## 2. 2016 US Presidential Election Poll Analysis

**Objective**: Analyze polling data from the 2016 Trump vs. Clinton election to estimate support and confidence intervals.

### Key Concepts:

- **Proportional Support Estimation**: Estimating % support for each candidate.
- **Confidence Intervals (CI)**: Calculated for both candidates using normal approximation.
- **Spread Measurement**: The difference in support between Clinton and Trump.
- **Statistical Testing**: Used to determine whether the spread is statistically significant.

### Implementation Highlights:

- Cleaned data for invalid/missing values.
- Calculated point estimates for Clinton and Trump’s support.
- Built 95% confidence intervals using standard error.
- Analyzed whether the election result was predictable based on polling margins.
- Used simulations to model potential election outcomes.

---

## 3. Drug Safety Statistical Evaluation

**Objective**: Analyze clinical trial data to test if a new drug has statistically significant effects compared to a placebo.

### Key Concepts:

- **Group Comparison**: Compare mean outcomes (e.g., white blood cell count) between drug and placebo groups.
- **Hypothesis Testing**: Using t-tests to evaluate significant differences.
- **Statistical Significance**: Decisions based on p-values and significance levels (α = 0.05).
- **Two-sample T-test**: Explored how `equal_var` and `alternative` parameters influence the outcome.

### Implementation Highlights:

- Summarized means and standard deviations by treatment group.
- Performed two-tailed and one-tailed t-tests for various clinical metrics.
- Interpreted statistical results to evaluate drug safety and effectiveness.
- Discussed the implications of assumptions (e.g., equal variance).

---

## Included Files

| Filename                                       | Description                                             |
| ---------------------------------------------- | ------------------------------------------------------- |
| `roulette.ipynb`                             | Monte Carlo simulation of betting outcomes in roulette. |
| `presidental_election.ipynb`                 | Polling data analysis for Clinton vs. Trump.            |
| `drug_safety.ipynb`                          | Clinical trial data and t-test evaluations.             |
| `2016-general-election-trump-vs-clinton.csv` | Dataset used in election analysis.                      |
| `drug_safety.csv`                            | Dataset for clinical trial evaluation.                  |
| `CA0.pdf`                                    | Full description of tasks and expected outcomes.        |

---

## Summary

This project demonstrates fundamental statistical reasoning and data simulation skills:

- How to use simulation to analyze expected outcomes and variability.
- Building and interpreting confidence intervals.
- Conducting hypothesis testing in real-world contexts.
- Making inferences from polling and clinical trial data.

These three notebooks form a solid foundation in data science practice and reasoning.
