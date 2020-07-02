## Problem Statement

Given the `Company Name` and `Business Description`, the task is to classify a company into its category. There are in total **62** categories


## Approach
* Removed duplicate entries
* Wordcloud visualization across categories
* Baseline model with **BOW** and **Multinomial Naive Bayes** obtaining `F-1` and `AUC` scores of **0.59** and **0.685** respectively.
* Improving with **RoBERTA** with `F-1` and `AUC` scores of **0.743** and **0.847** respectively with training for `20` epochs.
