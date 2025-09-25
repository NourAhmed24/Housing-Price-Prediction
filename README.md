<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>
    <div class="container">
        <h1>Housing Price Prediction README 🏡</h1>
        <p>This project is a predictive modeling task to estimate housing prices using a Linear Regression model.</p>
        <hr>
        <h2>Project Overview 📈</h2>
        <p>The objective of this project is to accurately predict the selling price of a house. The model is trained on a dataset containing various features of houses. The entire process, from data loading to model evaluation, is implemented in a Jupyter Notebook.</p>
        <h3>Dataset</h3>
        <p>The dataset used is <code>Housing.xls</code>. It contains a variety of features that influence house prices, including:</p>
        <ul>
            <li><strong>price</strong>: The price of the house 💰</li>
            <li><strong>area</strong>: The area of the house in square feet 🏠</li>
            <li><strong>bedrooms</strong>: The number of bedrooms 🛏️</li>
            <li><strong>bathrooms</strong>: The number of bathrooms 🛁</li>
            <li><strong>stories</strong>: The number of stories in the house 🪜</li>
            <li><strong>mainroad</strong>: Whether the house is on a main road</li>
            <li><strong>guestroom</strong>: Presence of a guestroom</li>
            <li><strong>basement</strong>: Presence of a basement</li>
            <li><strong>hotwaterheating</strong>: Presence of a hot water heating system</li>
            <li><strong>airconditioning</strong>: Presence of an air conditioning system</li>
            <li><strong>parking</strong>: The number of parking spaces 🚗</li>
            <li><strong>prefarea</strong>: Whether it is in a preferred area</li>
            <li><strong>furnishingstatus</strong>: The furnishing status of the house</li>
        </ul>
        <hr>
        <h2>Methodology ⚙️</h2>
        <p>The following steps are taken to build the predictive model:</p>
        <ol>
            <li><strong>Data Loading and Preprocessing</strong>: The dataset is loaded into a pandas DataFrame. Categorical features are converted into numerical representations, and all features are scaled using <code>StandardScaler</code> to standardize the data.</li>
            <li><strong>Model Building</strong>: A Linear Regression model from the <code>scikit-learn</code> library is used to predict the <code>price</code> based on the other features. The data is split into training and testing sets to validate the model's performance.</li>
            <li><strong>Model Evaluation</strong>: The model's performance is evaluated using the following metrics:
                <ul>
                    <li><strong>R² Score</strong>: Measures how well the model predicts the outcome.</li>
                    <li><strong>Mean Absolute Percentage Error (MAPE)</strong>: Provides a clear percentage-based measure of prediction accuracy.</li>
                </ul>
            </li>
        </ol>
        <hr>
        <h2>Required Libraries 📚</h2>
        <ul>
            <li><code>numpy</code></li>
            <li><code>matplotlib</code></li>
            <li><code>seaborn</code></li>
            <li><code>pandas</code></li>
            <li><code>scikit-learn</code></li>
        </ul>
    </div>
</body>
</html>
