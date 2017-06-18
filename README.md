# Instacart
## F1 score
In statistical analysis of binary classification, the F1 score (also F-score or F-measure) is a measure of a test's accuracy. It considers both the **precision p** and the **recall r** of the test to compute the score: **p is the number of correct positive results divided by the number of all positive results**, and **r is the number of correct positive results divided by the number of positive results that should have been returned**. The F1 score can be interpreted as a weighted average of the precision and recall, where an F1 score reaches its best value at 1 and worst at 0.

- TP: 预测为正， 实际为正
- FP: 预测为正， 实际为负
- TN: 预测为负，实际为负
- FN: 预测为负， 实际为正
- 准确率： TP/ (TP+FP)
- 召回率： TP/ (TP +FN)

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/7d63c1f5c659f95b5dfe5893213cc8ea7f8bea0a)
