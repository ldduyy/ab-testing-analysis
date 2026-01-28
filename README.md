# Marketing A/B Testing Analysis

## Project Overview
Dự án này phân tích hiệu quả của một chiến dịch quảng cáo bằng cách sử dụng kiểm định thống kê. 
Mục tiêu là xác định xem quảng cáo có thực sự làm tăng tỷ lệ chuyển đổi (Conversion Rate) hay không.


## Dataset
- **Source:** [Kaggle - Marketing A/B Testing](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing/code)
- **Size:** 588,101 rows.
- **Features:** `user id`, `test group`, `converted`, `total ads`, etc.

## Tech Stack
- Python (Pandas, Numpy)
- Visualization: Matplotlib, Seaborn
- Statistics: Scipy (Chi-Square Test)

## Key Findings
- **Conversion Rate (Ad group):** 2.55%
- **Conversion Rate (PSA group):** 1.78%
- **Statistical Significance:** P-value < 0.05, bác bỏ giả thuyết H0.
- **Lift:** Chiến dịch quảng cáo giúp tăng tỷ lệ chuyển đổi lên ~43%.

![alt text](image.png) ![alt text](image-1.png)