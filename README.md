# Introduction

Company has developed an application to increase the number of paying users for their product. They are conducting an AB test to see the results of this new page.
Two equally-sized groups are created as control and treatment groups, labeled A and B. The treatment group (B) is presented with the new webpage while the control group (A) is presented with the old one, and the experiment is run.

# About the Dataset

user_id: unique users number

timestamp: time

group: treatment and control group

landing_page: old_page and new_page

converted: Sign up status after viewing the page (0-1)

# AB testing
## Create Hypothesis

H0: There is not statistically significant difference between the old page and new page

H1: There is statistically significant difference between the old page and new page

## Assumption Check
### Normality Assumption

H0: The assumption of normal distribution is provided
H1: The assumption of normal distribution is not provided

### Variance Homogeneity

H0: Variances are homogeneous
H1: Variances are not homogeneous

# Conclusion
The hypothesis will be concluded based on the p-value obtained from the parametric/non-parametric test we will perform. This result will answer the question: Is there a significant difference between the new and old page?
