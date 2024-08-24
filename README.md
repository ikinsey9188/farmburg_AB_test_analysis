# Analyzing Farmburg's A/B Test

## Project Overview

This project analyzes the results of an A/B test conducted by Farmburg, a farming simulation social network game. The goal is to determine the optimal price point for a new microtransaction feature based on user purchase behavior. The project involves performing statistical tests using Python to analyze the data and make informed business decisions.

## Narrative

Brian, a Product Manager at FarmBurg, has been running an A/B test with three different price points for a new microtransaction feature: $0.99, $1.99, and $4.99. He needs to determine which price point will generate enough revenue to justify the cost of developing the feature. This project analyzes the test results to identify the best pricing strategy.

## Project Goals

1. Analyze the purchase data from three different price points using a Chi-Square test.
2. Determine the number of purchases needed to justify the feature development cost.
3. Perform binomial tests to evaluate if the observed purchase rates at each price point meet the required threshold.

## Files

- `analyze_farmburg_ab_test.py`: The Python script containing the analysis code.
- `clicks.csv`: The dataset used for the analysis.
- `README.md`: This file, which provides an overview of the project.
- `.gitignore`: Optional file to exclude unnecessary files from the repository.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/farmburg-ab-test-analysis.git

2. Install the required Python libraries:
pip install pandas scipy

3. Run the Python script:
python analyze_farmburg_ab_test.py
