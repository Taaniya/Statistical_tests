# Statistical_tests
This repository contains conceptual and practical understanding of statistical tests.


### Hypothesis testing 
#### T-test
* T-tests tell us how significant the difference is between to sets of observations.

*  It is a parametric test and assumes that the data come from a normal disrtibution.

#### Dependent t-test / paired samples test
This test is performed on 2 sets of observations that are related in some way or are captured from the same objects.

Here, dataset is the blood pressure of people from two different points of time - before and after a treatment.


**Null hypothesis** H0: mu_diff = 0 
There is no difference between the means of the samples
Hypothesized value of the mean difference between the 2 set of observations under hypothesis is 0.

**Alternate hyothesis** - The means are different.


##### Terminologies - 

##### Type-1 error

Type-1 error or alpha or significance level is the probability of us accepting the alternate hypothesis when the Null hypothesis  is true.

##### Type-2 error -

Type-2 error or beta is the chances of falsely accepting the Null hypothesis when it's not true.

##### P-value -

This is a calculated value from our analysis of the 2 set of samples and indicates the probability of us obtaining the test results given the null hypothesis is true i.e it is the probability of an event happening as per the alternate hypothesis assuming Null hypothesis H0 is true.

Lower p-value indicates lower probability of observing the result under null hypothesis.Hence, decreased support for null hypothesis.

Small p-values are associated with large t-statistic.

References

* [Hypothesis testing in ML using python](https://towardsdatascience.com/hypothesis-testing-in-machine-learning-using-python-a0dc89e169ce)
* [T-table](http://www.sthda.com/english/wiki/t-distribution-table)
* [MANOVA analysis paired sample t-test](https://www.statisticssolutions.com/manova-analysis-paired-sample-t-test/)
* [Paired t-test](https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Paired_T-Test.pdf)

