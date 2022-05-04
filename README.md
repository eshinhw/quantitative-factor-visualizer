<p align="center">
  <img width="900" height="400" src="https://user-images.githubusercontent.com/41933169/165682213-9581daf4-9848-45ec-a09c-41f618a2d0ae.png">
</p>

# PyQuant

PyQuant is an investing portfolio management tool with Command Line Interface (CLI). PyQuant works with Questrade API to retrieve account information and financial data to:

- provide account status summary
- generate portfolio performance matrices 
- perform portfolio rebalancing

## Purpose

The main purpose is to implement historically-proven asset allocation strategies to provide optimal portfoloio management and remove human errors by following rule-based investing philosophy.

## Data Sources <a name="data-sources"></a>

- [yfinance](https://pypi.org/project/yfinance/)
- [Questrade API](https://www.questrade.com/api/documentation/getting-started)

## Fixed Asset Allocation Portfolios <a name="fixed-asset-allocations"></a>

- Traditonal 60% Equities + 40% Bonds Portfolio
- Four Seasons Portfolio
- All Weather Portfolio
- Permanent Portfolio

## Dynamic Asset Allocation Portfolios <a name="dynamic-asset-allocations"></a>

- [Dual Momentum](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2042750) by Gary Antonacci
- [Vigilant Asset Allocation (VAA)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3002624) by Wouter J. Keller
- [Defensive Asset Allocation (DAA)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3212862) by Wouter J. Keller
- [Lethargic Asset Allocation (LAA)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3498092) by Wouter J. Keller

## Usage

### Main Menu

<p align="center">
  <img width="500" height="300" src="https://user-images.githubusercontent.com/41933169/166627802-eae6970a-887d-4813-a732-46ee5b423488.png">
</p>

### Account Options

<p align="center">
  <img width="500" height="300" src="https://user-images.githubusercontent.com/41933169/166627895-3be04278-1b37-411f-8a14-592e7f298b85.png">
</p>

### Add New Account

New Questrade account can be added and will be saved in json file in the same location of `main.py`. Make sure new account number is correct!

<p align="center">
  <img width="500" height="300" src="https://user-images.githubusercontent.com/41933169/166627975-518800ed-c439-4da0-b22d-65a0cb4634f9.png">
</p>

### Portfolio Summary

#### Balance Summary, Investment Summary and Performance Against BenchMark

BenchMark Portfolio is Traditional 60% Equities + 40% Bonds Portfolio. Performance comparison against BM computes CAGR and MDD.

<p align="center">
  <img width="700" height="500" src="https://user-images.githubusercontent.com/41933169/166628294-66ded221-02a2-4d5b-b2c1-1c70b0b9655e.png">
</p>

#### Historical Dividends

<p align="center">
  <img width="500" height="500" src="https://user-images.githubusercontent.com/41933169/166628418-2abfd386-3ff9-4d88-9015-f802346e922d.png">
</p>

<p align="center">
  <img width="500" height="500" src="https://user-images.githubusercontent.com/41933169/166628419-0f04464d-0b92-4811-a7d4-8d8a822b55f7.png">
</p>

### Allocation Rebalancing

Currently, PyQuant only offers rebalancing outputs for VAA and LAA based on historical momentums.

<p align="center">
  <img width="500" height="300" src="https://user-images.githubusercontent.com/41933169/166628514-79c7e05a-3270-401c-b0fa-5abed9218256.png">
</p>
