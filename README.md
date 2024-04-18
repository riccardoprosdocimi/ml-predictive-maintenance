# 🛠️ Machine Learning for Predictive Failure in Industrial Machinery
📋 **Features**
- Utilizes the Microsoft Azure Predictive Maintenance dataset with 36,500 instances.
- Implements logistic regression, MLP, RNN, LSTM, and GRU models using PyTorch.
- Addresses challenges such as computational limitations, feature engineering, and overfitting.
- Evaluates model performance using AUROC, accuracy, precision, and recall metrics.

🔍 **Methodology**
- Dataset preprocessing: Merges telemetry data, maintenance records, failure history, error logs, and machine features.
- Features are aggregated into 24-hour windows and segmented for modeling.
- Implements both non-sequential and sequential models to capture static and dynamic characteristics.
- Fine-tunes hyperparameters and evaluates models using a structured train-validate-test framework.

📈 **Results**
- Comparative performance analysis reveals insights into model effectiveness for predictive maintenance.
- Surprisingly, logistic regression demonstrates resilience, while more complex models achieve superior performance.
- The GRU model performs exceptionally well, showcasing robustness in predicting rare events (i.e., failures).

💡 **Discussion**
- Discusses the limitations and strengths of different models, highlighting the importance of aligning model complexity with data characteristics.
- Attributes the high performance to clean data, structured methodology, careful hyperparameter tuning, and feature engineering.

🔬 **Conclusion**
- Demonstrates the effectiveness of machine learning in predictive maintenance, aiming to minimize downtime and enhance equipment longevity.
- Proposes future directions for component-level prediction and real-time data integration to further optimize maintenance strategies.
