<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Airbnb Pricing Optimization</title>

<style>
    body {
        font-family: 'Segoe UI', sans-serif;
        background-color: #f4f6f9;
        margin: 0;
        padding: 0;
        color: #333;
    }

    .container {
        width: 85%;
        margin: auto;
        padding: 40px 0;
    }

    h1 {
        text-align: center;
        color: #1f4e79;
        font-size: 36px;
    }

    h2 {
        color: #2c3e50;
        margin-top: 40px;
        border-bottom: 2px solid #ddd;
        padding-bottom: 5px;
    }

    p {
        line-height: 1.6;
        font-size: 16px;
    }

    ul {
        margin-left: 20px;
        line-height: 1.6;
    }

    .card {
        background: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        margin-top: 20px;
    }

    .highlight {
        background: #e8f0fe;
        padding: 15px;
        border-left: 5px solid #1f4e79;
        margin-top: 15px;
        border-radius: 5px;
    }

    .kpi {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
        gap: 20px;
        margin-top: 20px;
    }

    .kpi-box {
        background: #1f4e79;
        color: white;
        padding: 20px;
        border-radius: 8px;
        text-align: center;
        font-weight: bold;
    }

    footer {
        text-align: center;
        margin-top: 50px;
        padding: 20px;
        background: #1f4e79;
        color: white;
        border-radius: 10px;
    }
</style>
</head>

<body>

<div class="container">

<h1>🏠 Airbnb Pricing Optimization – NYC Market Analysis</h1>

<div class="card">
<h2>📌 Project Overview</h2>
<p>
This project analyzes the New York Airbnb Open Data dataset to develop a data-driven pricing optimization framework for Airbnb hosts. 
The objective is to identify how pricing strategies based on location, room type, demand indicators, and reviews can maximize estimated revenue while maintaining competitive occupancy levels.
</p>
</div>

<div class="card">
<h2>🎯 Business Problem</h2>
<div class="highlight">
How can Airbnb hosts optimize their pricing strategy to maximize revenue without significantly reducing occupancy?
</div>
</div>

<div class="card">
<h2>📊 Dataset Information</h2>
<ul>
<li><strong>Source:</strong> Airbnb NYC Open Data (Kaggle)</li>
<li><strong>Rows:</strong> ~9,984 Listings</li>
<li><strong>Sector:</strong> Hospitality & Tourism Analytics</li>
<li><strong>Tools Used:</strong> Google Sheets, Excel, GitHub</li>
</ul>
</div>

<div class="card">
<h2>🧹 Data Cleaning & Preparation</h2>
<ul>
<li>Removed duplicate listings</li>
<li>Standardized categorical variables</li>
<li>Handled missing values</li>
<li>Converted price from text to numeric</li>
<li>Treated pricing outliers</li>
<li>Created Occupancy Rate & Estimated Revenue columns</li>
</ul>

<div class="highlight">
<strong>Estimated Revenue Formula:</strong><br>
Price × (365 − availability_365)
</div>
</div>

<div class="card">
<h2>📈 KPI Framework</h2>

<div class="kpi">
<div class="kpi-box">Average Market Price</div>
<div class="kpi-box">Average Occupancy Rate</div>
<div class="kpi-box">Average Estimated Revenue</div>
<div class="kpi-box">Best Performing Room Type</div>
<div class="kpi-box">Optimal Price Band</div>
</div>

</div>

<div class="card">
<h2>🔍 Analytical Approach</h2>
<ul>
<li>Revenue by Room Type Analysis</li>
<li>Revenue by Neighbourhood Group</li>
<li>Price Band Segmentation</li>
<li>Price vs Occupancy Correlation</li>
</ul>
</div>

<div class="card">
<h2>💡 Key Insights</h2>
<ul>
<li>Manhattan commands the highest pricing premium.</li>
<li>High price band listings generate the strongest revenue.</li>
<li>Occupancy does not significantly decline at higher price levels.</li>
<li>Location is the dominant pricing lever.</li>
</ul>
</div>

<div class="card">
<h2>📌 Recommendations</h2>
<ul>
<li>Implement borough-based dynamic pricing.</li>
<li>Prioritize high-performing room types.</li>
<li>Optimize minimum night policies.</li>
<li>Use mid-to-high price band strategy in premium locations.</li>
</ul>
</div>

<div class="card">
<h2>🚀 Future Scope</h2>
<ul>
<li>Predictive pricing models</li>
<li>Seasonal demand forecasting</li>
<li>Sentiment analysis on reviews</li>
<li>Automated data pipeline integration</li>
</ul>
</div>

<footer>
Group 18 – Newton School of Technology<br>
Airbnb Pricing Optimization Project
</footer>

</div>

</body>
</html>
