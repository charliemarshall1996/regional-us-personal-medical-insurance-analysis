# US Personal Medical Insurance - Regional Analysis

This repository conducts an analysis on US medical insurance data across regions. Aided by visualizations, it has the potential to affect the policies set out by these organizations, as well as holding the ability to improve customer satisfaction.

## Scope

The following headings define the scope of this analysis. It identifies a problem at hand, sets out a goal of the analysis in solving the problem, and identifies potential actions that may be undertaken as a result of the analyses. It provides information as to the origins of the dataset, addresses ethical concerns and gives a brief overview of the analysis to be undertaken to attempt to achieve the set out goal.

### The Problem

The problem to address is understanding how regional differences impact insurance charges. This could significantly affect insurance policy pricing and customer satisfaction. Currently, insurers may use basic demographic data but may not have a deep understanding of regional factors' effects on insurance costs. Gaps might exist in localized health trends, regional economic conditions, and their interplay with insurance charges.

### The Goal

The goal is to quantify the impact of regional factors on insurance charges and to identify if certain regions are more prone to higher charges and why. Success would be measured by the ability to predict insurance charges based on regional data accurately and to identify actionable regional characteristics that influence costs.

### Potential Actionable Outcomes

The analysis could inform insurance pricing models, adjust risk assessments, and potentially guide customer engagement strategies depending on the region. It could also inform policyholders about factors that contribute to their premiums.

### The Data

The data used for this analysis comes from the dataset [Medical Cost Personal Datasets](https://www.kaggle.com/datasets/mirichoi0218/insurance?resource=download) from Kaggle and contains seven features, described as so:

- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, *(northeast, southeast, southwest, northwest)*.
- charges: Individual medical costs billed by health insurance

### Analysis

The analysis will involve both descriptive and predictive components. It will describe patterns in the data and predict charges based on regional factors. Model validation will occur through back-testing against historical data.

### Ethical Considerations

The data used for this analysis is anonymized. Transparency will be ensured by clearly communicating how data informs charges. Discrimination/equity issues will be monitored by analyzing how charges differ across demographics within regions.
