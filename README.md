# Causal Machine Learning for Coupon Campaign Optimization

## Overview

This repository contains the implementation of a Double Machine Learning (DML) model designed to enhance the performance of a coupon campaign for a retail store. The model utilizes data sourced from Kaggle and is developed with the aim of improving the targeting and effectiveness of coupon distribution.

## Features

- **Double Machine Learning (DML):** The model employs a two-stage approach, predicting the likelihood of coupon provision in the first stage and estimating the impact on sales in the second stage, while addressing potential confounding factors.

- **Causal Inference:** Leveraging causal inference principles, the model aims to identify the causal relationship between coupon provision and sales, distinguishing it from mere correlation. This is particularly crucial for understanding the true impact of coupons on customer behavior.

- **Kaggle Dataset:** The data used for this project is sourced from Kaggle, providing valuable insights into customer behavior and coupon campaigns within a retail context. (https://www.kaggle.com/datasets/vasudeva009/predicting-coupon-redemption/data) 

- **Coupon Campaign Optimization:** The primary goal is to optimize coupon distribution by identifying key factors that contribute to increased sales, ensuring a more efficient and targeted campaign.

## Why Double Machine Learning and Causal Inference?

- **Causality vs. Correlation:** Traditional predictive models may capture correlations between variables but struggle to uncover causal relationships. DML, grounded in causal inference, goes beyond correlation to estimate the true impact of interventions like coupon distribution.

- **Addressing Confounding Factors:** In coupon campaign optimization, external factors can influence both coupon provision and sales, leading to biased results. DML addresses confounding variables, providing more accurate and reliable estimates of the causal effect.

- **Robustness in Decision-Making:** Understanding the causal impact of coupon campaigns empowers retailers to make more informed decisions. DML ensures that the observed effects are more likely to be genuine, contributing to robust and effective strategies.

## Usage

### Prerequisites

- Python 3.x
- Dependencies listed in `requirements.txt`

### Installation

```bash
pip install -r requirements.txt
```

### How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/dml-coupon-campaign.git
   cd dml-coupon-campaign
   ```
2. Run the main script:
   ```bash
   python main.py
   ```
3. Explore the results and model performance.

### Results
Provide insights into the model's performance, key metrics, and any noteworthy findings. Include visualizations and comparisons to highlight improvements achieved through the Double Machine Learning approach.

### Acknowledgments
Kaggle for providing the dataset used in this project.
Open-source libraries and frameworks that contributed to the implementation.

### Contributing
Contributions are welcome!

### Questions or Comments

If you have any questions, suggestions, or just want to chat about this project, feel free to reach out:

- **Email:** hhaeri0911@gmail.com
- **GitHub Issues:** [Project Issues](https://github.com/hhaeri/Causal-Machine-Learning-for-Coupon-Campaign-Optimization/issues)
  
Your feedback is highly appreciated!




