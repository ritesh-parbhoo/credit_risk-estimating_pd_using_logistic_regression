MODELLING PROBABILITY OF DEFAULT IN CREDIT RISK USING LOGISTIC REGRESSION


DESCRIPTION


This project, implemented in R, involves developing a credit risk model to estimate the probability of default for borrowers using logistic regression (GLM). The model examines how key factors - employment status (categorical), bank balance (numeric) and annual salary (numeric) - predict the probability of a counterparty defaulting on their credit obligations. The model is trained on a training set and tested on a validation set, and various methods are used to evaluate the discriminatory power of the model.


MOTIVATION


Credit risk - the risk that a counterparty will default on their financial obligations - is a principal concern of lenders and financial institutions. Key to measuring credit risk is estimating probability of default which will allow institutions to make data-informed lending decisions, manage risk exposure, and comply with regulatory requirements. By developing a logistic regression model using key predictors - employment status, bank balance and annual salary - this project can identify high risk borrowers and improve credit allocation, thus reducing potential financial losses.


REFERENCE LIST



Data:

Title: Loan Default Prediction (Beginners data set for financial analytics)

Source: Kamal Das, Kaggle
URL: https://www.kaggle.com/datasets/kmldas/loan-default-prediction
Licence: Data files © Original Authors
Filename: Default\_Fin.csv



Packages:
1. pROC
Xavier Robin, Natacha Turck, Alexandre Hainard, Natalia Tiberti, Frédérique Lisacek,

&nbsp; Jean-Charles Sanchez and Markus Müller (2011). pROC: an open-source package for R and

&nbsp; S+ to analyze and compare ROC curves. BMC Bioinformatics, 12, p. 77.  DOI:

&nbsp; 10.1186/1471-2105-12-77 <http://www.biomedcentral.com/1471-2105/12/77/>
2. PRROC
  Jens Keilwagen, Ivo Grosse and Jan Grau (2014). Area under Precision-Recall Curves for Weighted

&nbsp; and Unweighted Data. PLOS ONE (9) 3.



&nbsp; Jan Grau, Ivo Grosse, and Jens Keilwagen (2015). PRROC: computing and visualizing

&nbsp; precision-recall and receiver operating characteristic curves in R. Bioinformatics (31) 15, pp.

&nbsp; 2595-2597.R package version 1.4.

3\. ggplot2
H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016.

4\. broom
  Robinson D, Hayes A, Couch S, Hvitfeldt E (2026). \_broom: Convert Statistical Objects into Tidy

&nbsp; Tibbles\_. doi:10.32614/CRAN.package.broom <https://doi.org/10.32614/CRAN.package.broom>, R

&nbsp; package version 1.0.12, <https://CRAN.R-project.org/package=broom>.

5\. caret

&nbsp; Kuhn, M. (2008). Building Predictive Models in R

&nbsp; Using the caret Package. Journal of Statistical

&nbsp; Software, 28(5), 1–26.



REPRODUCIBILITY



R version 4.5.2 (2025-10-31 ucrt)





