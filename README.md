### StudentOutcomePredictor-SegmentationAnalysis

##### Abstract

This study embarks on a comprehensive journey to refine predictive models for academic outcomes, employing a dual analysis of student performance metrics. We dissected categorical and numerical data to identify pivotal factors impacting student success. The study introduces a novel segmentation-based approach, leveraging clustering and tailored Random Forest classifiers to outperform traditional models. Enhanced by SMOTE and GridSearchCV, this methodology provides superior predictive accuracy, especially for the critical 'Enrolled' class.

##### Introduction

Addressing the challenge of student retention and success, this research leverages data from the Polytechnic Institute of Portalegre, aiming to preemptively identify students at risk of underachievement. Traditional models often fall short due to class imbalances and diverse factors. Our segmentation-based approach, enriched with advanced statistical tests and feature selection methods, reveals unique predictors across student segments, offering a more precise tool for educational institutions.

##### Methodology

   * Data Acquisition: Utilizing data from the UCI Machine Learning Repository.
   * Preprocessing: Segmentation of categorical and numerical features, employing Chi-square and Kruskal-Wallis tests, respectively.
   * Feature Selection & Normalization: Application of RFECV for insightful feature selection; normalization to standardize data scales.
   * Predictive Modeling: Comparison between traditional models and our segmentation-based approach, using Random Forest classifiers.
   * Evaluation: Benchmarking model performance with classification reports and key metrics.

##### Conclusion

The segmentation-based approach significantly improves the prediction of academic outcomes, particularly for the 'Enrolled' class. This research underscores the value of tailored predictive models in educational settings, paving the way for targeted interventions to boost student retention and success.
