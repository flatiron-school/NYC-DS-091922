# Tests for Multiple Samples

High level: Introduce the concept of ANOVA, especially the F-Test, as a generalization of t-tests for multiple groups.

## Learning Goals

- Understand the issues of multiple comparisons
- Compare and contrast t-tests with ANOVA
- Implement ANOVA in Python

## Lecture Materials

[Jupyter Notebook: Tests for Multiple Samples](tests_for_multiple_samples.ipynb)

## Lesson Plan

### Preparing Data (5 Mins)

Section to introduce data and motivation to make multiple comparisons.

### Two Sample t-Test (10 Mins)

Introduce the concept of two sample t-tests since this the first time seeing it directly. Relate to comparing to a population but now we have two samples that could be "extreme" and hence the pooled variance.

### Multiple t-Test (10 Mins)

Demonstrate multiple t-tests and discuss the issues in doing so.

### F-statistic (15 Mins)

Introduce the concepts of the F-statistics and distribution but don't go over the exact math since this tends to hinder understanding. Emphasize how we can find the probability of getting an F-statistic with the area under an F-distribution.

### Performing ANOVA (15 Mins)

Perform the actual ANOVA and walk through what the results mean and how to interpret these.
