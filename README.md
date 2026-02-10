## AML/CFT Transaction Monitoring Project
# Project Overview

This project demonstrates a rule-based Anti-Money Laundering (AML/CFT) transaction monitoring framework using Python.
It simulates how financial institutions identify, flag and assess potentially suspicious transactions in line with risk-based compliance principles.

# Objectives

Detect potentially suspicious transactions using AML/CFT red-flag logic

Apply a risk-scoring approach to prioritize alerts

Demonstrate analytical thinking aligned with FATF-based AML/CFT frameworks

Produce outputs suitable for compliance review and escalation

# AML Rules Implemented

The following rule-based indicators were applied:

-Large Cash Transactions

Cash transactions exceeding KES 1,000,000

-Structuring (Smurfing)

Multiple transactions by the same customer on the same day with cumulative value exceeding KES 1,000,000

-High-Risk Jurisdictions

Transactions involving predefined high-risk countries

-Politically Exposed Persons (PEPs)

Transactions involving PEPs above KES 500,000

# Risk Scoring Methodology

Each red flag contributes to a cumulative risk score:

Indicator	Risk Points
Large Cash Transaction	3
Structuring	4
High-Risk Country	3
PEP Exposure	5

Transactions with a risk score ≥ 5 are classified as High Risk

High-risk transactions are flagged for further review or escalation

# Key Outputs

Flagged suspicious transactions dataset

Risk scores and risk classification

Summary statistics on flagged activity

Visualization of suspicious transaction patterns

# Key Insights

Rule-based monitoring effectively highlights high-risk behavior such as structuring and PEP exposure

Risk scoring enables prioritization of alerts, supporting efficient compliance review

Even simple AML rules can significantly reduce undetected financial crime risk when applied consistently

# Limitations

Uses synthetic data for demonstration purposes

Rule-based logic does not replace advanced transaction monitoring systems or machine learning models

Thresholds are illustrative and should be calibrated to institutional risk appetite and regulatory guidance

# By Faith N. Weyombo -Finance & AML/CFT Analyst
