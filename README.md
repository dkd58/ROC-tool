# ROC-tool
R/Shiny tool for showing the effect (and quality) of **classification** models 

We start with a very simple setup, training a decision tree on the poisonous mushroom data from Kaggle/UCI ML site.
The results in terms of a [ROC curve](https://www.unc.edu/courses/2006spring/ecol/145/001/images/lectures/lecture37/fig4.png) are displayed.

![ROC curve](https://www.unc.edu/courses/2006spring/ecol/145/001/images/lectures/lecture37/fig4.png)

Optionally, the prior proportion of poisonous (including non-edible species) mushrooms may be set
as well as the misclassification costs (which will probably be very skewed, showing the inadequacy of overall accuracy as a quality measure).

In subsequent releases, more features will be added, such as:
- Different model types to choose from (e.g. logistic regression, a 'business rule', naive Bayes, random forest, SVM, etc)
- Selecting variables/features to include, observations to use
- Inspecting created models, including variable importance
- Comparing models (AUC + CI, ROC curves)
