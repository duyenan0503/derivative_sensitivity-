# derivative_sensitivity-

**Project Overview**
This priject focuses on financial derivative modeling using Python. It specifically provides tools for visualizing option Greeks for complex strategies and calculating implied volatility from market data.

**Features**
1. Bull Call Spread Visualization
The notebook calculates and plots the fundamental "Greeks" for a Bull Call Spread across various maturities (0.1, 1, 2, 5, and 10 years). The visualizations include:
Delta: Measures the rate of change of the spread's value relative to changes in the underlying spot price.
Gamma: Measures the rate of change in Delta relative to changes in the underlying price.
Vega: Measures sensitivity to the volatility of the underlying asset.

2. Implied Volatility Calculation
The notebook includes an implementation to solve for Implied Volatility using the Bisection Method. 
The script then iteratively finds the volatility that equates the theoretical Black-Scholes price with a target market price.

**Dependencies**
To run this notebook, you will need the following Python libraries:
- numpy: For numerical operations and array handling.
- matplotlib: For generating derivative sensitivity plots.
- scipy: Specifically scipy.stats.norm for cumulative distribution and probability density functions used in Black-Scholes calculations.

**Usage**
- Greeks Analysis: Execute the first cell to generate a three-panel visualization comparing Delta, Gamma, and Vega for a Bull Call Spread with strikes at 285 and 320.
- Implied Volatility: Execute the calculation cells and follow the prompts to enter market parameters. The implied_by_bisection function will output the calculated volatility.


<img width="1789" height="590" alt="image" src="https://github.com/user-attachments/assets/1642b4f8-6eca-4dce-8215-f4f6b3be2cc1" />
<img width="1789" height="590" alt="image" src="https://github.com/user-attachments/assets/e6534b7a-214d-4fc6-8927-393326733ef0" />
<img width="853" height="547" alt="image" src="https://github.com/user-attachments/assets/31899ce7-f402-4df6-b13e-d6baf2004196" />
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/8582855a-8ce9-4399-82cf-75eeadcf296c" />
