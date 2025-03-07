# Portfolio Optimization using Principal Component Analysis (PCA)

## Overview

This project explores the use of **Principal Component Analysis (PCA)** for **portfolio optimization**. By transforming asset returns data into a lower-dimensional space, PCA helps identify key patterns while reducing noise and redundancy. The goal is to construct optimized portfolios that **maximize returns and minimize risk**, outperforming standard benchmarks.

## Features

- **Dimensionality Reduction**: Uses PCA to extract essential components from asset returns data that drive that drive portfolio performance. 
- **Portfolio Construction**: Utilizes PCA-transformed data to build portfolios optimized for variance and returns.
- **Benchmark Comparison**: Compares the optimized portfolio's performance against benchmarks, such as an equally weighted portfolio.

## Technologies Used

- **Python**: Core language for implementation.  
- **NumPy**: Efficient numerical computations.  
- **Pandas**: Data handling and preprocessing.
- **Scikit-learn**: Used for **PCA implementation** and **preprocessing**.   
- **Matplotlib & Seaborn**: Data visualization tools.  
- **yFinance**: Fetches historical financial data. 

## Getting Started

### Prerequisites

Ensure you have Python installed along with the following libraries:

```bash
pip install numpy pandas matplotlib seaborn yfinance 
