# Lab 3: KhataPe Lending Case

## Business Background

KhataPe is a fictional digital lender in Indore. It provides small loans to kirana shops and college students through its app.

Every month, KhataPe has a fixed budget to lend and must choose between two loan products: Option A and Option B.

## Business Problem

The CFO asks:

"Can AI help us pick the more profitable option every month? Can we trust a quick answer, or must the AI show its working?"

## Decision Rules

1. Net Return = Interest Rate + Processing Fee - Expected Default - Cost of Funds.
2. Profit = Net Return × Loan Budget.
3. Choose the option with the higher profit.
4. If both profits are equal, choose the option with the lower expected default.

## What to Ignore

- Operating costs
- Taxes
- Timing of payments

## Worked Example

Option A:
Interest = 22%
Processing Fee = 2%
Expected Default = 6%
Cost of Funds = 10%

Net Return = 22 + 2 - 6 - 10 = 8%

Budget = ₹50 crore

Profit = 8% × ₹50 crore = ₹4 crore

Option B:
Interest = 18%
Processing Fee = 1%
Expected Default = 3%
Cost of Funds = 10%

Net Return = 18 + 1 - 3 - 10 = 6%

Profit = 6% × ₹50 crore = ₹3 crore

## Final Decision

KhataPe should choose Option A because its profit is higher: ₹4 crore compared with ₹3 crore.
