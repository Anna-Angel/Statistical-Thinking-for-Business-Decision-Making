# Decision Log

## Assignment 2: Dataset (2026-07-19)
- Dataset: salaries and season leaders for 2021 from ESPN
- Main variable of interest: Salary because the group as a whole decided it would be interesting
- Key decision: In a group discussion, we decided to use sports data because it would be readily available and real

## Assignment 3: Descriptive Stats (2026-07-26)
- Cleaning done: There were enough rows in the combined dataset to have enough for the project and still drop the rows that had outliers or missing data. The columns that had more than three categories were recoded to only have three categories.

## Assignment 4: Probability (2026-07-26)
- Normal vs. empirical, and why: We used an empirical approach for our probibility modelling because all of our histograms were right skewed.

## Assignment 5: Inference (2026-08-09)
- What we tested, alpha, conclusion: Our first test was if the average NBA player was paid more than $6,000,000 at a significance level (alpha) of 0.05. For this test, there was statistically significant evidence to show that the mean salary was greater than $6,000,000. Our second test was to see if the average season points total was different from 500 at a significance level (alpha) of 0.05. For this test, there was not enough evidence to conclude that the main season points total differed from 500.

## Assignment 6: Regression (2026-08-12)
- First predictor removed and why: The first predictor we removed was Position=Forward because the p-value was the highest at 0.941, meaning it was the least significant predictor in our model.
- Multicollinearity handling: One interesting thing I found was that when we were removing each statistically insignificant predictor one at a time, multicollinearity started showing in the insignificant ones as the p-values for some would actually jump up after another one was removed, so there wasn't that much multicollinearity in the end.
