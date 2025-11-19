# Statistical Arbitrage Pairs Trading Strategy Engine

Developed by **Syed Zain Ahmed**  
Inspired by the work of **Anthony Li**  
Reference: https://github.com/anthonyli01/Statistical-Arbitrage-Pairs-Trading-Strategy

## Introduction

A pairs trading strategy is a market neutral trading approach that identifies two closely related assets whose prices move together. When the price relationship diverges, the strategy involves buying the undervalued asset and shorting the overvalued one with the expectation that the spread will revert.

This project builds a complete pairs trading engine and explores several methods to improve the strategy. It includes distance based methods, cointegration based methods, Kalman filtering, copulas, and principal component analysis. The project also evaluates performance and highlights assumptions used during backtesting.

## Table of Contents

1. Libraries and Data Preprocessing

2. Distance Based Pairs Trading Strategy

3. Cointegration Approach: Basic  
   3.1 What cointegration means  
   3.2 Identifying pairs using the Engle Granger test  
   3.3 Trading logic and return computation  
   3.4 Performance and analysis

4. Cointegration Approach: Annual Cointegration and Stop Loss  
   4.1 Annual identification of cointegrated pairs  
   4.2 Strategy returns and stop loss integration  
   4.3 Performance and analysis

5. Cointegration Approach: Profit Exit Strategy

6. Cointegration Approach: Relaxing the assumption of daily rebalancing

7. Kalman Filter Based Approach

8. Copula Based Approach

9. PCA Based Approach

---

