<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSST 104 Advanced Machine Learning (IS 104)</title>
    <style>
        /* Body style */
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2; /* Light gray background */
            padding: 20px;
            margin: 0;
        }

        /* Header style */
        h1 {
            color: #333; /* Dark gray text */
            text-align: center;
            margin-bottom: 20px;
        }

        /* Section style */
        section {
            background-color: #fff; /* White background */
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Soft shadow effect */
        }

        /* Link style */
        a {
            color: #007bff; /* Blue link color */
            text-decoration: none;
        }

        /* Link hover style */
        a:hover {
            text-decoration: underline;
        }

        /* Table of Contents style */
        ol {
            list-style-type: none;
            padding-left: 0;
        }

        /* Table of Contents item style */
        li {
            margin-bottom: 10px;
        }

        /* Pastel design */
        .pastel {
            background-color: #ffd6d6; /* Pastel pink */
            border: 1px solid #ffb3b3; /* Lighter pink border */
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>CSST 104 Advanced Machine Learning (IS 104)</h1>

    <!-- Table of Contents -->
    <section>
        <h2>Table of Contents</h2>
        <ol>
            <li><a href="#exercise5">Exercise 5 - Linear Regression</a></li>
            <li><a href="#exercise6">Exercise 6 - Logistic Regression</a></li>
            <li><a href="#exercise7">Exercise 7 - Netflix Userbase Analysis</a></li>
            <li><a href="#exercise8">Exercise 8 - Pollution Data Time Series Analysis Using ARIMA</a></li>
            <li><a href="#midterm">Midterm - Forecasting with ARIMA Model</a></li>
        </ol>
    </section>

    <!-- Exercise 5 - Linear Regression -->
    <section id="exercise5" class="pastel">
        <h2>Exercise 5 - Linear Regression</h2>
        <p><strong>Objective:</strong> Predict whether a customer will subscribe to a term deposit based on their demographic and account information using logistic regression.</p>
        <p><strong>Dataset:</strong> Imagine we have a dataset named bank_customers.csv with the following columns:</p>
        <p><a href="https://www.kaggle.com/datasets/kidoen/bank-customers-data">Dataset Link</a></p>
    </section>

    <!-- Exercise 6 - Logistic Regression -->
    <section id="exercise6" class="pastel">
        <h2>Exercise 6 - Logistic Regression</h2>
        <p><strong>Objective:</strong> Develop a logistic regression model to predict the customer feedback (positive/negative) on online food orders. This task involves data loading, preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization.</p>
        <p><strong>Dataset:</strong> You will use a dataset that contains information on online food orders, including customer demographics, order details, and feedback. The dataset includes features like Age, Gender, Marital Status, Occupation, Monthly Income, and Feedback.</p>
    </section>

    <!-- Exercise 7 - Netflix Userbase Analysis -->
    <section id="exercise7" class="pastel">
        <h2>Exercise 7 - Netflix Userbase Analysis</h2>
        <p><strong>Objective:</strong> Leverage linear regression to predict Monthly Revenue and logistic regression to classify customers based on a positive or negative feedback proxy, using the Netflix Userbase dataset. This task will encompass data preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization.</p>
        <p><strong>Dataset:</strong> "Netflix Userbase.csv", containing user demographics, subscription details, and other relevant information.</p>
    </section>

    <!-- Exercise 8 - Pollution Data Time Series Analysis Using ARIMA -->
    <section id="exercise8" class="pastel">
        <h2>Exercise 8 - Pollution Data Time Series Analysis Using ARIMA</h2>
        <p><strong>Objective:</strong> The goal of this assessment is to simulate a time series dataset representing a country's annual pollution levels over a decade. You will apply time series analysis techniques, including the ARIMA (Autoregressive Integrated Moving Average) model, to understand the data's behavior, test for stationarity, and forecast future pollution levels.</p>
        <p><strong>Dataset:</strong> Simulate a time series dataset for a country's annual pollution levels over 10 years. Assume a trend component, a seasonal component, and some random noise in the data.</p>
    </section>

    <!-- Midterm - Forecasting with ARIMA Model -->
    <section id="midterm" class="pastel">
        <h2>Midterm - Forecasting with ARIMA Model</h2>
        <p><strong>Objective:</strong> To apply ARIMA modeling techniques to forecast the number of app updates in the Google Play Store for the next 12 months based on historical data.</p>
        <p><strong>Dataset:</strong> Google Play Store Dataset</p>
        <ul>
            <li><strong>Description:</strong> Contains information about the google play store.</li>
            <li><strong>Use Case:</strong> Ideal for time series analysis to predict continuous outcomes like the downloads based on various features (e.g., ratings, reviews, installs).</li>
        </ul>
    </section>
</body>
</html>
