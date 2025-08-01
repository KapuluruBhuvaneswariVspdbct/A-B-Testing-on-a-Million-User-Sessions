# A-B-Testing-on-a-Million-User-Sessions
Analyzed website conversion data for control (A) and treatment (B) groups. Found Group B had significantly higher conversion using hypothesis testing. Visualized uplift across device types and regions.
# A/B Testing on a Million User Sessions

## 📊 Project Overview
This project analyzes a simulated dataset of 1,000,000 user sessions to evaluate the effectiveness of a new website design. Using A/B testing, we determine whether the treatment group (Group B) shows a statistically significant improvement in conversion rates over the control group (Group A).

## 🧪 Methodology
- Simulated 1M user records with attributes: group (A/B), device, region, and conversion outcome.
- Performed A/B testing using independent t-tests to compare conversion rates between groups.
- Visualized results by group, device type, and region using Matplotlib.

## ✅ Key Findings
- **Group A (Control)**: ~14.5% conversion rate  
- **Group B (Treatment)**: ~17.9% conversion rate  
- **P-value < 0.001** → Statistically significant difference.  
- The treatment performed better across all devices and regions, with **tablet users** and **South America** showing the highest lift.

## 📌 Skills Demonstrated
- Data Manipulation with Pandas
- A/B Testing (Hypothesis Testing)
- Data Visualization with Matplotlib
- Handling Big Data (1M+ rows)
- Deriving business insights from user behavior

## 📁 Files Included
- `bigdata_ab_test_dataset.csv`: Full dataset with 1 million rows
- `ab_testing_100k_excel_ready.csv`: Sample for Excel visualization (100K rows)
- `README.md`: This project summary file
- Jupyter Notebook (optional): Contains full code and charts

## 🚀 How to Use
1. Open the dataset in Jupyter Notebook or Excel.
2. Run the provided Python code to generate insights and visualizations.
3. Modify or extend the analysis with device-level or region-based filters.

## 🔗 Author
**Bhuvaneswari Kapuluru**  
[Portfolio Website](https://kapulurubhuvaneswarivspdbct.github.io/MY-PORTFOLIO-DATA-ANALYST/)  
[LinkedIn](https://linkedin.com/in/bhuvaneswari-kapuluru-2892682bb/)  
[GitHub](https://github.com/KapuluruBhuvaneswariVspdbct)
