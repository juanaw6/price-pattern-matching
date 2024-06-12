# Price Pattern Matching

![GitHub last commit](https://img.shields.io/github/last-commit/juanaw6/price-pattern-matching)
![GitHub license](https://img.shields.io/github/license/juanaw6/price-pattern-matching)

This repository contains a Python script that implements a price pattern matching algorithm using a modified Boyer-Moore approach with tolerance. The script analyzes historical price data to identify patterns and make trading decisions based on these patterns.

## Table of Contents

- [Overview](#overview)
- [Usage](#usage)

## Overview

The Price Pattern Matching script is designed to provide insights into the movement of prices within a given timeframe. It focuses on analyzing price changes, identifying patterns, and making decisions based on these patterns.

The key features of this repository include:

- Data collection from historical price data.
- Normalization of price data into percentage changes.
- Construction of a bad character table with tolerance for pattern matching.
- Application of the modified Boyer-Moore algorithm to identify price patterns.
- Evaluation of patterns to make trading decisions (buy, sell, hold).

## Usage

To use this script, follow these steps:
1. Make sure you have Python installed on your system. You can download and install Python from the [official python website](https://www.python.org/downloads/).
2. Clone the repository to your local machine:

   ```
   git clone https://github.com/juanaw6/price-pattern-matching.git
   ```
3. Navigate to the project directory:
   ```
   cd price-pattern-matching
   ```
4. Install the required Python packages using pip:
   ```
   pip install -r requirements.txt
   ```
5. Place the CSV file containing your historical price data in the project directory. The CSV file should have columns: Open time, Open, High, Low, Close, Volume, Close time, Quote asset volume, Number of trades, Taker buy base asset volume, Taker buy quote asset volume, Ignore.

6. Update the csv_file_path variable in the script to point to your CSV file.

7. Run the Python script to process the data and make trading decisions:
   ```
   python main.py
   ```