KhataPe – AI Lending Decision: Chain-of-Thought

1. Project Overview

This project is based on KhataPe, a fictional digital lending company.

The objective is to compare two AI prompting approaches:

* Direct Answer Prompting
* Step-by-Step (Chain-of-Thought) Prompting

The project evaluates how AI can help a financial analyst choose between two lending options based on expected profit.

2. Business Problem

KhataPe has eight monthly loan decision scenarios. In each scenario, the company must choose between Option A and Option B.

The goal is to select the option that provides the higher expected profit while considering interest rates, processing fees, expected defaults and cost of funds.

3. Profit Calculation Formula

Net Return = Interest Rate + Processing Fee − Expected Default − Cost of Funds

Expected Profit = Net Return × Loan Budget

All percentages are converted into decimal form when calculating profit.

If both options have equal profit, the option with the lower expected default is selected.

4. Project Files

The repository contains the following files:

File	Description
01_case_study.md	KhataPe business case and problem
02_scenarios.md	Eight synthetic lending scenarios and calculations
03_direct_simple.md	Simple direct-answer prompt
04_direct_decision.md	Direct decision prompt and AI output
05_cot_decision.md	Step-by-step decision prompt and AI output
06_scorecard.md	Verification, comparison and final reflection

5. Methodology

Step 1: Understand the Case

Understand KhataPe’s lending problem and the profit formula.

Step 2: Create Scenarios

Prepare eight fictional lending scenarios with different financial values.

Step 3: Calculate the Answer Key

Calculate the expected net return and profit independently using a spreadsheet.

Step 4: Direct Simple Prompt

Ask AI to perform a simple calculation using the given formula.

Step 5: Direct Decision Prompt

Ask AI to select the better lending option for all eight scenarios.

Step 6: Chain-of-Thought Prompting

Ask AI to show the calculation steps and explain the decision for each scenario.

Step 7: Verification and Scorecard

Compare AI results with independent spreadsheet calculations and test a changed default rate.

Step 8: GitHub Submission

Organise the project files and publish the completed work in this repository.

6. Results Summary

The calculations produced the following decisions:

Scenario	Selected Option	Expected Profit
S01	B	₹4.75 crore
S02	B	₹3.50 crore
S03	B	₹6.00 crore
S04	A	₹4.20 crore
S05	A	₹1.625 crore
S06	A	₹10.35 crore
S07	A	₹3.375 crore
S08	B	₹6.40 crore

These results are based on the synthetic dataset created for this project.

7. Key Learnings

* Direct prompting can provide quick answers.
* Step-by-step calculations make financial decisions easier to verify.
* Higher interest rates do not always mean higher profits.
* Expected default and cost of funds affect profitability.
* AI-generated calculations should always be checked independently.
* A clear prompt improves the structure and usefulness of AI responses.

8. Limitations

This is a fictional educational case study, not a real lending recommendation.

The model uses simplified financial assumptions. Actual lending decisions also require credit-risk assessment, regulatory compliance, collection costs and customer affordability checks.

The original scenario design intended one equal-profit case, but the final dataset contains two tie scenarios: S04 and S08. Both are resolved using the lower-default rule.

9. Conclusion

This project demonstrates how direct prompting and step-by-step prompting can be used for financial decision-making. Independent verification is important because AI answers should not be accepted without checking the calculations.

Project: KhataPe AI Lending Decision
Subject: Prompt Engineering, AI & Machine Learning
Domain: FinTech
