# Analyze A/B Test Results

This project is part of Udacity's Data Analyst Nanodegree certification.

## Dataset

This data was provided by Udacity for analysis as part of Data Analyst Nanodegree certification.
The data contain a result of an A/B test run by an e-commerce website.

A company has developed a new web page to try to increase the number of users who “convert”, meaning the number of users who decide to pay for the company’s product.

The goal is to help the company decide should implement the new page or not, through Statistical and practical interpretation.


## Summary of Findings

I found that no sufficient evidence that suggests the new treatment page has more conversions. The conversion probability for each page is almost the same. I will assume that the old page is better unless the new page proves to be better at a Type I error rate of 5% then the null and alternative hypotheses should be:

 
𝐻0:𝑃𝑛𝑒𝑤−𝑃𝑜𝑙𝑑≤0
𝐻1:𝑃𝑛𝑒𝑤−𝑃𝑜𝑙𝑑>0


Base on the p-value and z-score we fail to reject the null hypothesis.
