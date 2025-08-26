# 💸 pyZAR Interest Calculator

A simple Python script that helps users calculate **simple** or **compound interest** on their investments. It also supports **monthly contributions**, making it useful for savings planning and financial forecasting.

## 📦 Features

- Choose between **Simple** or **Compound** interest
- Input:
  - Initial deposit amount
  - Annual interest rate
  - Investment duration (in years)
  - Optional monthly contributions
- Outputs:
  - Total interest earned
  - Final value of the investment

## 🧮 How It Works
  ```
  Interest = (Principal + Contributions) × Rate × Time
  Future Value = Principal × (1 + Monthly Rate)^(Months)
  Compound Interest is calculated monthly
  ```

## 🚀 Getting Started

### Requirements
- Python 3.x

### Run the Script in your terminal
```bash
python interest_calculator.py
```

## Examle Usage
### Input
```
Choose interest type (simple/compound): compound
Enter initial deposit amount: R20000
Enter annual interest rate (e.g., 6.5 for 6.5%): 6.5
Enter investment duration in years: 5
Enter monthly contribution amount (R0 if none): R0
```
### Output
```
Results after 5 years:
Total Interest Earned: R7656.35
Final Value of Investment: R27656.35
```

## 🛠️ Future Improvements
- Add a GUI using Tkinter or WPF
- Export results to CSV or PDF
- Add support for different compounding frequencies (quarterly, daily)
