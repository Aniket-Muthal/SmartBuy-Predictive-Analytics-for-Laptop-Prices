# SmartBuy-Predictive-Analytics-for-Laptop-Prices
An AI-powered tool for analyzing and predicting laptop prices using machine learning.

# A. Problem Statement

Laptop prices vary significantly based on multiple factors such as specifications, brand, and market demand. Businesses and consumers often struggle to determine a fair price for a laptop, leading to inefficiencies in purchasing and pricing decisions. SmartBuy: Predictive Analytics for Laptop Prices aims to solve this problem by developing an intelligent pricing model that accurately predicts laptop prices based on key attributes, enabling data-driven decision-making.

# B. Objective

- Develop an AI-driven predictive model to estimate laptop prices using machine learning techniques.
- Identify critical factors (e.g., processor type, RAM, storage, display resolution, brand) that significantly impact pricing.
- Provide accurate price recommendations to help consumers make informed purchasing decisions and businesses optimize pricing strategies.
- Enhance inventory management for retailers by forecasting price trends and adjusting stock accordingly.
- Enable competitive analysis by benchmarking laptop prices against market trends to improve profitability and customer engagement.

# C. Key Takeaways

The **Gradient Boosting Regressor** demonstrated strong predictive performance for laptop price estimation, achieving an R2 score of 0.9066 and a Mean Absolute Error (MAE) of 0.1349. These metrics indicate that the model successfully captures key patterns in the data, leading to accurate price predictions.

1. **High Accuracy (R2 Score = 0.9066)** --> The model explains 90.66% of the price variance, making it a reliable predictor.
2. **Low Error (MAE = 0.1349)** --> Predictions are close to actual values, minimizing deviation.
3. **Gradient Boosting's Strengths** --> Handles nonlinear relationships effectively, leading to superior generalization.

## Critical Factors
- 'RAM', 'PPI'('Screen Size' and 'Resolution'), 'Storage Type', 'CPU Company, Model & Frequency', 'Weight' and 'Type' of laptops are among the top 5 important features contributing significantly in deciding the price of the laptop.
- **'RAM & Storage Type'**: Larger RAM and SSDs usually increase price more than HDDs.
- **'Screen Size and Resolution'**: Higher resolution and large screens contribute to pricing
- **'Processor Type and Speed'**: High-performance processors (e.g., Intel Core i7) significantly impact cost.
- **'Brand Premiums**': Some brands may have higher baseline pricing, impacting predictions.

# D. Conclusion

SmartBuy successfully leverages predictive analytics to enhance laptop price estimation, ensuring informed decisions for both consumers and businesses. By utilizing machine learning models such as Gradient Boosting, Random Forest, and XGBoost, the system achieves high accuracy in price predictions based on key specifications like RAM, storage, display quality, processor type and brand.

### Key Outcomes

1. **Improved Pricing Accuracy** --> Helps buyers and sellers make data-driven decisions.
2. **Optimized Inventory Management** --> Retailers can adjust stock based on pricing trends.
3. **Competitive Market Insights** --> Businesses can benchmark prices against competitors.
4. **Enhanced Consumer Experience** --> Consumers receive fair pricing recommendations tailored to their needs.

### Future Enhancements

- **Real-Time Market Adjustments** --> Incorporating dynamic pricing based on demand fluctuations.
- **Feature Expansion** --> Considering additional elements like battery life, thickness, warranty & support, keyboard type and build material for refined predictions.
- **Integration with E-commerce Platforms** --> SmartBuy can be connected with online retailers to provide seamless pricing insights.

With its robust predictive capabilities, SmartBuy transforms laptop pricing into a strategic advantage, benefiting both businesses and consumers by delivering accurate, data-driven price recommendations.

# E. Streamlit App

### "Laptop Price Wizard: SmartBuy at Your Service"

[app_demo.pdf](https://github.com/user-attachments/files/20459597/app_demo.pdf)


