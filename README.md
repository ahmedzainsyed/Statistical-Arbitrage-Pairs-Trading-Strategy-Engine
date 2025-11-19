# Statistical-Arbitrage-Pairs-Trading-Strategy-Engine
#Developed by: Syed Zain Ahmed

#Inspired by: Anthony Li's Pairs Trading Strategy

#Introduction
#A pairs trading strategy is a market-neutral trading strategy that involves identifying two or more closely related assets, such as two stocks, whose prices move together. Once these pairs of stocks are identified, the idea is to trade any divergence in the prices in hope that the prices will converge once again in the near future. This usually involves buying the 'cheaper' asset and shorting the 'expensive' asset.

#In this project, we will build a basic pairs trading strategy and follow up by exploring different ways to improve on this. We will analyse the performance of these strategies and discuss any assumptions made when backtesting. The project will involve difference based approach, cointegration, kalman filters, copulas, and PCA.

#Table of Contents
#Libraries and Preprocessing Data

#1. Distance Based Pairs Trading Strategy

#2. Cointegration Approach: Basic
#2.1 What is cointegration?
#2.2 Identifying Pairs: Engle and Granger Test for Cointegration
#2.3 Trading Strategy and Returns Calculation
#2.4 Performance and Analysis

#3. Cointegration Approach: Annual Cointegration and Stop-Loss Implementation

#3.1 Identifying Cointegrating Pairs Annually
#3.2 Calculating Strategy Returns and Implementing a Stop-loss
#3.3 Performance and Analysis

#4. Cointegration Approach: Adding a Profit Exit Strategy


#5. Cointegration Approach: Relaxing Assumption of Daily Rebalancing


#6. Kalman Filter


#7. Copula Approach


#8. PCA Approach

