# Gikomba Market Stall Analysis

## 1. Full Name
Swaleh Rama

## 2. Cohort
Software Development Data Analysis with Ai Module

## 3. Business Problem Summary
Wanjiku operates a fresh-produce stall at Gikomba Market. Over the past two weeks, she has recorded daily revenue figures and current stock levels manually in a notebook. To transition from informal guesswork to data-informed operations, she hired a freelance analyst to evaluate her sales trends, measure week-on-week growth, compare weekday versus weekend revenue, assess product profit margins, and identify inventory items requiring urgent reordering.

## 4. Solution
The solution is built entirely in core Python without external data processing libraries like pandas or NumPy. It processes 14-day daily sales data and stock metadata to evaluate business performance. Through custom modular functions (`week_totals`, `classify_day`, and `check_reorder_and_margins`), the project computes overall sales metrics, week-on-week growth, weekday vs. weekend averages, and gross profit margins per product while automatically flagging low-stock items. Finally, it outputs a clean terminal report and actionable business recommendations.

## 5. Top Three Findings
1. **Weekend Dominance:** Weekend daily sales average KES 4,900.00, generating **78.51% higher revenue** than weekday daily sales (KES 2,745.00). The best sales day was Saturday of Week 2 with KES 5,600.00.
2. **Positive Business Growth:** Week 2 total sales reached KES 24,400.00 compared to Week 1 sales of KES 21,550.00, representing a solid **13.23% week-on-week growth**.
3. **Critical Stock Alerts & Margins:** **Tomatoes** (18 kg stock vs 25 kg reorder level) and **Sukuma** (9 kg stock vs 15 kg reorder level) are below reorder thresholds. **Avocados** yield the highest gross margin at **42.86%**, while Sukuma yields 40.00%.

## 6. How to Run the Project Locally & Demo Script

### Open in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/plp-da-a1-gikomba-stall-analysis/blob/main/stall_analysis.ipynb)

*(Note: Replace `YOUR_GITHUB_USERNAME` in the link above with your actual GitHub username).*

### Run Locally (Demo Script)
To run the analysis locally using pure Python without Colab:

1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/plp-da-a1-gikomba-stall-analysis.git](https://github.com/YOUR_GITHUB_USERNAME/plp-da-a1-gikomba-stall-analysis.git)
   cd plp-da-a1-gikomba-stall-analysis
