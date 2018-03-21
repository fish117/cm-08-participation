# cm-08-participation
class 08 participation
For (1) and (2) below, you're choosing between two candidates to hire. Discuss the pros and cons of choosing one candidate over the other in the following situations.

1.Both are predicted to have the same productivity score of 75, but have the following probabilistic forecasts.

For A: it has higher variance and lower bias.If you hire A, you will have less risk.
For B: it has lower variance and higher bias.If you hire B,it’s like a gamble. You might get very low productivity, but you can also get very high score like 80 which you cannot get from A.



2.Two "non-overlapping" forecasts:
A:it has high variance and lower bias. Most data are centered around 60.
B:it has lower variance and higher bias. But most data are centered around [75,85]
Therefore, we should choose B because even if it’s variance is larger, the minimum productivity it gets will still be larger than the maximum productivity of A.


3.You've formed a probabilist forecast for a particular value of the predictors, displayed below as a density.
You then collect test data for that same value of the predictor, indicated as the points below the density.
What is the problem with the probabilistic forecast?

From the test data, all points are located in the left side of the distribution which means the the model is bias.
The forecast cdf to the corresponding outcome -- the resulting sample will not be Uniform(0,1).
Therefore, we might need to reduce the window width.

