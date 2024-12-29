
</head>
<body>
    <h1>Demand Forecasting</h1>

   <p>This repository contains code and analysis for a demand forecasting project using LightGBM.</p>

   <h2>Table of Contents</h2>
    <ul>
        <li><a href="#dataset-information">Dataset Information</a></li>
        <li><a href="#eda">Exploratory Data Analysis (EDA)</a></li>
        <li><a href="#feature-engineering">Feature Engineering</a></li>
        <li><a href="#model-selection">Model Selection</a></li>
        <li><a href="#lightgbm-choice">Why LightGBM?</a></li>
        <li><a href="#test-data-prediction">Test Data Prediction</a></li>
    </ul>

  <h2 id="dataset-information">1. Dataset Information</h2>
    <p>The dataset used for this project contains information about sales, including weekly sales data, prices, and other related attributes. Key columns include:</p>
    <ul>
        <li>Item ID</li>
        <li>Store ID</li>
        <li>Price</li>
        <li>Week</li>
        <li>Sales</li>
    </ul>

  <h2 id="eda">2. Exploratory Data Analysis (EDA)</h2>
    <p>EDA was conducted to understand the dataset's structure, identify missing values, and explore relationships between features. Key findings include:</p>
    <ul>
        <li>Sales trends over time</li>
        <li>Correlation between price and sales</li>
        <li>Seasonality patterns in sales data</li>
    </ul>

   <h2 id="feature-engineering">3. Feature Engineering</h2>
    <p>Six new columns were created based on price and week to enhance model performance. These include:</p>
    <ul>
        <li>Price Trend</li>
        <li>Weekday/Weekend Indicator</li>
        <li>Discount Percentage</li>
        <li>Rolling Average of Sales</li>
        <li>Sales Lag Features</li>
        <li>Price Elasticity</li>
    </ul>

   <h2 id="model-selection">4. Model Selection</h2>
    <p>Various models were evaluated, including:</p>
    <ul>
        <li>Linear Regression</li>
        <li>Random Forest</li>
        <li>LightGBM</li>
        <li>XGBoost</li>
    </ul>
    <p>LightGBM was selected for its superior performance and efficiency.</p>

   <h2 id="lightgbm-choice">5. Why LightGBM?</h2>
    <p>LightGBM was chosen for the following reasons:</p>
    <ul>
        <li>Fast training speed and low memory usage</li>
        <li>Excellent performance on large datasets</li>
        <li>Support for categorical features and missing values</li>
        <li>Strong predictive accuracy compared to other models</li>
    </ul>

  <h2 id="test-data-prediction">6. Test Data Prediction</h2>
    <p>The trained LightGBM model was used to predict demand on the test dataset. Results include:</p>
    <ul>
        <li>Mean Absolute Error (MAE): <code>&lt;insert value&gt;</code></li>
        <li>Root Mean Squared Error (RMSE): <code>&lt;insert value&gt;</code></li>
    </ul>
    <p>Predictions align closely with actual sales trends, validating the model's effectiveness.</p>
</body>
</html>
