# COSM by Prof. Jasbir Singh, BCA 5th Batch 2023-26 | July 2025 to Dec. 2025 
This Repo contain the Practical File Code in C++ and Python 
## 📘 Practical List: C++ Logic + Python Visualization

Python : https://colab.research.google.com/drive/1NdA9-C5FiRsZPIMlHn9v75HBWKtNTSgE?usp=sharing

Each practical includes:
- 📌 Problem Statement
- 👨‍💻 C++ Code to compute
- 📊 Python Script to visualize
- 📝 Sample Input/Output
- 🔗 Dataset (if needed)
- 
Detailed Practical Statements for COSM (C++ + Python Visualization)
**🔹 UNIT I – Descriptive Statistics & Frequency Distribution**

1. Create a frequency distribution table for ungrouped data
C++: Write a program to input n numbers, calculate frequency count, and display it.
Python: Use matplotlib.pyplot.bar() to create a bar chart showing the frequencies.

2. Construct a histogram for a given dataset
C++: Accept numerical data, define class intervals, and count frequencies.
Python: Use matplotlib.pyplot.hist() to plot a histogram using the same intervals and frequency.

3. Plot a frequency polygon
C++: Calculate class midpoints and corresponding frequencies.
Python: Use matplotlib.pyplot.plot() to plot a line chart (frequency polygon) joining midpoints.

4. Compute the Arithmetic Mean, Median, and Mode
C++: Accept data and implement formulas to compute mean, median, and mode.
Python: Use pandas.Series.describe() and pandas.Series.mode() for cross-verification and presentation.

5. Calculate Geometric Mean and Harmonic Mean
C++: Implement formulas using pow() and 1/x summations.
Python: Use scipy.stats.gmean() and scipy.stats.hmean(); visualize differences in central tendency.

6. Analyze Measures of Dispersion: Range, Mean Deviation, Standard Deviation
C++: Write functions to compute these measures from raw data.
Python: Use seaborn.boxplot() and matplotlib to visually show spread and outliers.

7. Compute Coefficients of Dispersion (Range, Quartile, CV)
C++: Calculate Coefficient of Variation (CV), Coefficient of Range, and Quartile Deviation.
Python: Use plots to compare dispersion of different datasets visually (e.g., side-by-side boxplots).

🔹 UNIT II – Probability
8. Simulate coin toss and dice roll experiments
C++: Generate random outcomes and compute relative frequencies.
Python: Plot outcomes using matplotlib.pyplot.pie() or bar charts to show probabilities.

9. Verify the Addition and Multiplication Theorems of Probability
C++: Generate random events and check whether P(A∪B) = P(A) + P(B) - P(A∩B), etc.
Python: Visualize using Venn diagrams (via matplotlib_venn or matplotlib sets).

10. Calculate Conditional Probability and Independence
C++: Write code to compute conditional probability using user inputs.
Python: Use tree diagrams or annotated plots to demonstrate dependent vs. independent events.

🔹 UNIT III – Mathematical Expectation
11. Compute expected value for a discrete random variable
C++: Accept probabilities and values of X, then compute E(X).
Python: Plot the PMF and highlight the expected value on the graph.

12. Calculate the expected value of a function of a random variable
C++: Implement E[g(X)] for g(X) like X^2, 2X+3, etc.
Python: Compare graphs of X and g(X) and plot the corresponding probabilities.

13. Demonstrate properties of expectation and variance
C++: Verify linearity of expectation and formulas like Var(aX+b).
Python: Graph multiple scaled datasets and visualize changes in mean and variance.

14. Calculate covariance between two variables
C++: Input two arrays of values and compute covariance.
Python: Use seaborn.scatterplot() and add covariance as annotation.

🔹 UNIT IV – Correlation
15. Calculate Karl Pearson’s Correlation Coefficient
C++: Input two datasets (X and Y) and compute the correlation coefficient.
Python: Visualize the data using scatterplots with seaborn.regplot() and show correlation line.

16. Compute correlation from bivariate frequency distribution
C++: Extend Pearson’s method for grouped data.
Python: Visualize grouped data using heatmaps or 3D scatterplots (matplotlib or seaborn).

17. Calculate Spearman’s Rank Correlation Coefficient
C++: Rank the values, compute differences, and apply Spearman’s formula.
Python: Compare rank correlation visually with bar plots showing ranks side by side.

18. Compare all correlation methods visually
C++: Use stored correlation results.
Python: Use one chart to compare Pearson vs. Spearman for the same dataset using pandas and seaborn.
