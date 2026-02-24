# powerball-statistical-analysis
A Python-based statistical analysis of historical Powerball data using frequency modeling, chi-square testing, and probability-driven predictions.

# 🎯 Powerball Statistical Model

## 📌 Overview
This project analyzes historical Powerball data (from 1992 to present) using Python to uncover number frequency trends, evaluate randomness, and generate probability-based predictions.

⚠️ This project is for **educational and analytical purposes only**. Lottery results are random and cannot be predicted with certainty.

---

## 📊 Features

- Frequency analysis of white balls (Columns B–F)
- Powerball number frequency tracking
- Chi-square statistical test for randomness
- Rolling trend insights
- Prediction engine based on historical frequency
- Random ticket generator for comparison

---

## 📂 Dataset Format

Your dataset (`powerball.xlsx` or `.csv`) should follow this structure:

| Column | Description |
|--------|------------|
| A      | Date       |
| B–F    | White Balls |
| G      | Powerball  |

Example:

| Date       | B | C | D | E | F | PB |
|------------|---|---|---|---|---|----|
| 01/01/2020 | 5 | 12 | 23 | 34 | 45 | 12 |

---

## ⚙️ Requirements

Install dependencies (if using standard Python):

```bash
pip install pandas numpy scipy openpyxl
