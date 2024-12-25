# DeFi Calculator Toolbox

An interactive Jupyter notebook containing essential DeFi calculators for optimizing trading and liquidity provision strategies.
Colab link:
https://colab.research.google.com/drive/19rR1TAGPDkcQcAiFyL7RVsMszc1JyHGi#scrollTo=iAU6Vzwfj4Bg

## Tools Included

### 1. Money Market & Perpetual Calculator

A comprehensive calculator for determining optimal position sizes and capital allocation when executing money market borrowing and perpetual futures strategies.

#### Features:
- Calculates optimal long/short position allocations
- Determines leverage for both positions
- Estimates transaction fees and capital efficiency
- Provides detailed breakdown of:
  - Position sizes in dollar amounts
  - Token quantities
  - Swap fees and transaction costs
  - Notional exposure

#### Input Parameters:
- Current Price
- LTV (Loan-to-Value ratio)
- Liquidation Factor
- Long/Short Liquidation Prices
- Total Investment Amount
- Swap Fee Percentage
- MMR (Maintenance Margin Ratio)

### 2. Liquidity Pool Calculator

A tool for calculating optimal token ratios and splits when providing liquidity to AMM pools.

#### Features:
- Price ratio calculator between token pairs
- Optimal split calculator for LP positions
- High precision calculations (18 decimal places)
- Automatic ratio transfer between calculators

#### Input Parameters:
##### Ratio Calculator:
- Sample Token A Amount
- Sample Token B Amount

##### Split Calculator:
- Total Token A Available
- Price Ratio (auto-filled from ratio calculator)

## Usage

1. Open the notebook in a Jupyter environment
2. Run all cells to initialize the calculators
3. Input your parameters using the interactive widgets
4. Results will update automatically as you adjust the inputs

## Requirements
- Python 3.x
- IPython
- ipywidgets
- decimal

