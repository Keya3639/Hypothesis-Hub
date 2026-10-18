# Hypothesis Hub — Experiment Plan

## 1. Business Problem

The e-commerce company wants to determine whether redesigning its checkout page increases the percentage of users who complete a purchase.

## 2. Experiment Objective

Evaluate whether the redesigned checkout experience improves purchase conversion compared with the existing checkout page.

## 3. Experiment Design

- **Control Group (A):** Existing checkout page.
- **Variant Group (B):** Redesigned checkout page.
- **Assignment:** Randomly assign eligible users to one of the two groups.
- **Analysis approach:** Compare outcomes according to users' original group assignments.
- **Dataset:** Simulated data for a reproducible portfolio case study.

## 4. Business Question

Does the redesigned checkout page increase the purchase conversion rate compared with the existing page?

## 5. Hypotheses

- **Null Hypothesis (H0):** The variant's true purchase conversion rate is less than or equal to the control's.
- **Alternative Hypothesis (H1):** The variant's true purchase conversion rate is greater than the control's.

## 6. Metrics

### Primary Metric
Purchase conversion rate = users who complete a purchase / eligible users assigned to the group.

### Guardrail Metrics
- Checkout abandonment rate.
- Average order value among purchasing users.

Guardrail metrics will help identify potential trade-offs. Average order value will be interpreted alongside conversion and total business impact.

## 7. Statistical Approach

- Significance level: 0.05.
- Test direction: One-sided.
- Primary analysis: Two-proportion comparison.
- Confidence interval: Estimate the difference in conversion rates and quantify uncertainty.
- Practical impact: Assess the size and business relevance of any observed improvement.

## 8. Decision Principles

A launch recommendation will consider statistical evidence, the estimated effect size, confidence intervals, guardrail metrics, and experiment validity.

A statistically significant result alone will not automatically justify a launch.

## 9. Limitations

This portfolio project uses simulated data and cannot establish that a real checkout redesign would produce the same results.

Conclusions will depend on the assumptions used to generate the data and the validity of the statistical analysis.

## 10. Reproducibility

The project will document the data-generation process, analysis steps, statistical methods, and dependencies so that the results can be reproduced.