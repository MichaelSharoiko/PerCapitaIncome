# PerCapitaIncome
-Simple Regression and the Convergence Hypothesis-

This project will look at convergence and perform a simple regression.
The idea behind convergence is that poor economies should experience faster
rates of economic growth than richer economies.

In order test the convergence hypothesis, I will use data from www.bea.gov
to collect data from 48 U.S. states as each U.S. state is a separate economy.
Specifically, we will be looking at the per capita income in 1929 and 2018 for
each of the 48 states that existed in both 1929 and 2018. This data then was
stored into an excel spreadsheet to clean the data and include what was necessary.
For this, I had to exclude states such as Alaska, Hawaii, and the regions of the U.S. such as 
New England, Mideast since these are not U.S. states.

After cleaning the dataset I was left with 2 columns, percapinc1929 and percapinc2018 repectively.
Since I was going to be looking at growth I decided to use the growth formula of
growth = [(Per capita inc in 2018/per capita inc in 1929)^1/89 -1] * 100
to calculate the % growth from 1929 to 2018 for all 48 states in the excel sheet.
I labeled this new column "growth" and began to plot a scatter diagram for visualization
