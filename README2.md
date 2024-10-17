# Sales Forecasting
The file is WalmartSalesRFR.
本專案使用 Walmart 提供的銷售數據來分析45家商店的每週銷售表現，並預測未來銷售。數據包括關鍵假日（聖誕節、感恩節、超級盃、勞動節）週次，目的是了解這些假日對銷售的影響，並利用機器學習模型進行銷售預測。
- The primary objective is to build a model that predicts weekly sales based on time-related and store-specific features, with a focus on how holiday weeks influence store sales.
# Key Steps
1. Data Preprocessing
- Handling Missing
- ValuesFeature Engineering
- Data Encoding and Scaling

2. Exploratory Data Analysis
- Time-Based Analysis
- Store-Based Analysis
- Correlation Analysis
3. Random Forest Model
- Train a Random Forest Regressor to predict weekly sales. Perform hyperparameter tuning to improve model accuracy.
4. Evaluation Metric
- WMAE (Weighted Mean Absolute Error): This metric is used to evaluate model performance, giving higher importance to sales during holiday weeks by applying weights.
5. Model Comparison and Results
- Several RandomForestRegressor models were trained with different configurations, and the performance was evaluated using Weighted Mean Absolute Error (WMAE). The following table summarizes the results:
# Conclusion
