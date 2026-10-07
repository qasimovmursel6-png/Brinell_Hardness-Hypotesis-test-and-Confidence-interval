# 📊 One-Sample T-Test: Brinell Hardness Analysis of Ductile Iron

## 📌 Project Overview
This project evaluates whether the mean Brinell Hardness (HB) of subcritically annealed ductile iron castings exceeds the target benchmark of **170 HB**. Using Python (`scipy`, `statsmodels`, `seaborn`), the analysis covers data cleaning, descriptive statistics, normality diagnostics, hypothesis testing, and confidence interval estimation.

## 🧮 Statistical Methodology
1. **Descriptive Statistics**: Sample size ($N=25$), sample mean ($\bar{X}$), standard deviation ($S$), and standard error ($SE$).
2. **Normality Testing**: Shapiro-Wilk Test to evaluate distribution assumptions ($p = 0.0400$).
3. **Hypothesis Testing**: One-Sample T-Test ($H_0: \mu = 170$ vs. $H_1: \mu > 170$).
4. **Confidence Intervals**: 95% One-sided lower bound & 95% Two-sided interval.

## 📈 Key Findings
- **Sample Mean ($\bar{X}$)**: `172.52 HB`
- **T-Statistic**: `1.22` | **Critical T-Value**: `1.7109`
- **P-Value**: `0.117`
- **Decision**: Fail to reject $H_0$ at $\alpha = 0.05$. There is insufficient evidence to conclude that the average hardness exceeds 170 HB.
- **95% Lower Bound**: `169.10 HB`

## 🛠️ Tech Stack
- **Python 3.x**
- **Libraries**: `pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib`, `seaborn`

## 🚀 How to Run
```bash
git clone [https://github.com/USERNAME/brinell-hardness-hypothesis-testing.git](https://github.com/USERNAME/brinell-hardness-hypothesis-testing.git)
cd brinell-hardness-hypothesis-testing
pip install -r requirements.txt
jupyter notebook notebooks/hypothesis_testing_brinell.ipynb
