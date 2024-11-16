# transaction_fraud_detector
This ML project performs Binary Classification to detect whether a financial transaction is fraudulent.

This project is a Fraud Detection Tool designed to classify transactions as either fraudulent or non-fraudulent using Python's Google Colab environment. The tool leverages the NumPy and Pandas libraries for data manipulation and preprocessing, and applies a logistic regression model for binary classification.
Key Features:

    Dataset Handling:
        The tool processes transactional data with features such as transaction amounts, customer details, and merchant characteristics.
        Uses Pandas to load, clean, and explore the dataset.

    Preprocessing:
        Handles missing values, scales numerical features, and encodes categorical variables to prepare the dataset for modeling.
        Normalizes quantitative data using StandardScaler for optimal logistic regression performance.

    Model Building:
        Implements logistic regression from the scikit-learn library for binary classification.
        Models the relationship between transaction features and the likelihood of fraud.

    Training and Testing:
        Splits the dataset into training and testing subsets to evaluate model performance.
        Uses stratified sampling to maintain class balance.

    Evaluation Metrics:
        Computes metrics like accuracy, precision, recall, F1-score, and ROC-AUC to assess the model's effectiveness.
        Outputs a confusion matrix and classification report for detailed insights.

    Colab-Friendly:
        Fully compatible with Google Colab, allowing users to easily run and modify the tool in the cloud.
        Includes visualization features (e.g., fraud vs. non-fraud distributions) using Matplotlib and Seaborn.

How It Works

    Data Loading and Exploration:
        Load a transactional dataset in CSV format using Pandas.
        Perform exploratory data analysis (EDA) to understand feature distributions and correlations.

    Data Preprocessing:
        Normalize quantitative features (e.g., transaction amounts).
        Encode categorical variables using one-hot encoding or label encoding.

    Logistic Regression Model:
        Train the model using the training set and optimize hyperparameters for better results.
        Predict probabilities of fraud for the test set and classify transactions based on a threshold.

    Model Evaluation:
        Analyze precision and recall to focus on fraud detection (minimizing false negatives).
        Plot the ROC curve and calculate the AUC score for a visual performance overview.

This tool can be extended to include more advanced models (e.g., random forests, neural networks) or additional preprocessing techniques for improved accuracy.
