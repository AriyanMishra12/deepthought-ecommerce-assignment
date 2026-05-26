# Task 2: Dynamic Profitability Model

## Objective

The purpose of this model is to evaluate the financial viability of Amazon advertising campaigns under different business conditions.

The model allows users to modify key business variables and instantly observe the impact on:

- Profitability
- ACOS
- TACOS
- Revenue
- Contribution Margin
- Break-Even Advertising Spend

The goal is to support data-driven decision making rather than static reporting.

---

# Google Sheet Link

## Dynamic Profitability Model

[\[GOOGLE SHEET LINK\]](https://docs.google.com/spreadsheets/d/13zaS9f1v4jllvk97KvCauAfjNApTmPHd5U4AlKuzu7Q/edit?usp=sharing)

---

# Model Structure

The model consists of three sections:

1. Input Section
2. Output Section
3. Scenario Analysis Section

---

# Input Section

The following values can be modified by the user.

| Input Variable | Default Value |
|---------------|---------------|
| Selling Price (SP) | ₹800 |
| Cost of Goods Sold (COGS) | ₹280 |
| Amazon Referral Fee (%) | 12% |
| Monthly Ad Spend | ₹3,00,000 |
| Units Sold via Ads | 1,500 |
| Organic Units Sold | 2,000 |
| Fixed Costs | ₹1,50,000 |

These cells are highlighted to indicate editable inputs.

---

# Output Section

The model automatically calculates:

| Output |
|----------|
| Gross Margin per Unit |
| Amazon Fee per Unit |
| Ad Cost per Unit |
| Net Margin (Ad Units) |
| Net Margin (Organic Units) |
| Total Revenue |
| Total Monthly Profit |
| ACOS |
| TACOS |
| Break-Even Ad Spend |

No manual calculations are required.

---

# Key Formulas Used

## Gross Margin

Gross Margin = SP − COGS

---

## Amazon Fee

Amazon Fee = SP × Referral Fee %

---

## Ad Cost per Unit

Ad Cost per Unit = Ad Spend ÷ Ad Units

---

## Net Margin (Ad Units)

Net Margin = Gross Margin − Amazon Fee − Ad Cost Per Unit

---

## Net Margin (Organic Units)

Net Margin = Gross Margin − Amazon Fee

---

## Total Revenue

Revenue = SP × (Ad Units + Organic Units)

---

## Total Monthly Profit

Profit =

(Net Margin Ad × Ad Units)

+

(Net Margin Organic × Organic Units)

− Fixed Costs

---

## ACOS

ACOS =

Ad Spend ÷ Ad Revenue × 100

---

## TACOS

TACOS =

Ad Spend ÷ Total Revenue × 100

---

## Break-Even Ad Spend

Break-Even Ad Spend =

(Total Contribution Margin)

− Fixed Costs

Where:

Total Contribution Margin =

(SP − COGS − Amazon Fee)

×

Total Units Sold

---

# Scenario Analysis

The model was tested using multiple business scenarios to understand sensitivity and decision implications.

---

## Scenario 1: Price Increase

### Assumption

Selling Price increases from ₹800 to ₹950.

### Expected Impact

Positive:

- Revenue increases
- Gross Margin increases
- Monthly Profit increases
- Break-Even Ad Spend increases

Potential Risk:

- Lower conversion rate if customer demand becomes price sensitive

---

## Scenario 2: Cost Inflation

### Assumption

COGS increases by 20%.

New COGS:

₹280 × 1.20 = ₹336

### Expected Impact

- Gross Margin decreases
- Profitability decreases
- Break-Even Ad Spend decreases
- Margin for advertising becomes tighter

Business implication:

The company would need stronger advertising efficiency or pricing adjustments to maintain profitability.

---

## Scenario 3: Organic Growth

### Assumption

Organic units increase from 2,000 to 3,500.

Advertising spend remains unchanged.

### Expected Impact

- Revenue increases
- Profit increases
- TACOS decreases
- Dependence on paid advertising reduces

This is one of the healthiest growth scenarios because profitability improves without increasing ad spend.

---

## Scenario 4: Competitive Price Pressure

### Assumption

A competitor launches at ₹600.

GlowNest reduces SP from ₹800 to ₹700.

### Expected Impact

- Revenue per unit decreases
- Gross Margin decreases
- Net Margin decreases
- Break-Even Ad Spend decreases significantly

Business implication:

Price reductions should not be the first response to competition.

Alternative approaches:

- Improve product differentiation
- Improve conversion rate
- Improve product listing quality
- Strengthen brand positioning
- Increase customer reviews and trust signals

---

# Dashboard Features

The model includes visual indicators to simplify decision making.

## Conditional Formatting

Red:

- Monthly Profit < 0

Yellow:

- TACOS > 15%

Green:

- Positive profitability and acceptable TACOS

---

## Visualization

Profitability vs Ad Spend chart

The chart helps visualize:

- Diminishing returns
- Scaling opportunities
- Profitability thresholds
- Break-even points

---

# Key Insight

The most important lesson from building this model is that campaign success cannot be evaluated using ACOS alone.

A campaign with a higher ACOS may still be profitable if:

- Product margins are strong
- Organic sales are increasing
- TACOS remains healthy

The model therefore evaluates advertising decisions through both campaign efficiency and overall business profitability.