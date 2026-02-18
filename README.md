<!DOCTYPE html>
<html>
<body style="font-family: Arial, sans-serif; line-height:1.6;">

  <h1>Airbnb Price Optimization Dashboard</h1>

  <h2>Project Overview</h2>
  <p>
    This project analyzes Airbnb listing data to identify pricing strategies that maximize revenue while maintaining competitive occupancy rates.
  </p>
  <p>The dashboard supports:</p>
  <ul>
    <li>Revenue optimization decisions</li>
    <li>Location-based pricing analysis</li>
    <li>Room type performance comparison</li>
    <li>Price band profitability evaluation</li>
  </ul>
  <p>
    The objective is to help Airbnb hosts make <strong>data-driven pricing decisions</strong> 
    using revenue trends, occupancy insights, and location performance.
  </p>

  <hr>

  <h2>File Details</h2>
  <ul>
    <li><strong>Project Name:</strong> Airbnb Price Optimization – G18</li>
    <li><strong>Total Records:</strong> ~9,900+ listings</li>
    <li><strong>Tool Used:</strong> Google Sheets (Pivot Tables + Dashboard)</li>
    <li><strong>Output:</strong> Interactive Analytical Dashboard for Airbnb Price Optimization</li>
  </ul>

  <hr>

  <h2>Data Dictionary</h2>
  <table border="1" cellpadding="8" cellspacing="0">
    <tr>
      <th>Column Name</th>
      <th>Description</th>
      <th>Data Type</th>
    </tr>
    <tr>
      <td>id</td>
      <td>Unique listing identifier</td>
      <td>Integer</td>
    </tr>
    <tr>
      <td>Neighbourhood_Group</td>
      <td>Borough (Bronx, Brooklyn, Manhattan, Queens, Staten Island)</td>
      <td>Categorical</td>
    </tr>
    <tr>
      <td>Room_Type</td>
      <td>Entire Home/Apt, Private Room, Shared Room</td>
      <td>Categorical</td>
    </tr>
    <tr>
      <td>Price</td>
      <td>Price per night (USD)</td>
      <td>Float</td>
    </tr>
    <tr>
      <td>Occupancy Rate</td>
      <td>Estimated occupancy ratio</td>
      <td>Float</td>
    </tr>
    <tr>
      <td>Estimated Revenue</td>
      <td>Calculated annual revenue per listing</td>
      <td>Float</td>
    </tr>
  </table>

  <hr>

  <h2>Key Dashboard KPIs</h2>
  <ul>
    <li>Average Price</li>
    <li>Revenue per Listing</li>
    <li>Average Estimated Revenue</li>
    <li>Optimal Price Band</li>
    <li>Average Occupancy Rate</li>
    <li>Correlation between Price & Occupancy</li>
  </ul>

  <hr>

  <h2>Key Analysis Sections</h2>

  <h3>1. Revenue by Room Type</h3>
  <p>
    Compares estimated revenue across different room types to determine 
    which listing type generates the highest returns.
  </p>

  <h3>2. Revenue by Neighbourhood Group</h3>
  <p>
    Evaluates borough-level performance to identify high-demand and 
    high-revenue locations.
  </p>

  <h3>3. Price Band Performance</h3>
  <p>
    Analyzes how different pricing tiers impact revenue and occupancy.
  </p>

  <h3>4. Reviews vs Revenue</h3>
  <p>
    Examines whether higher customer ratings are associated with increased revenue.
  </p>

  <h3>5. Price vs Occupancy Correlation</h3>
  <p>
    Measures the strength of relationship between price increases and occupancy rate changes.
  </p>

  <hr>

  <h2>Business Problem Statement</h2>
  <p>
    <strong>
    How can Airbnb hosts optimize pricing based on location, room type, and demand trends 
    to maximize revenue while staying competitive?
    </strong>
  </p>

  <hr>

  <h2>Data Cleaning Process</h2>
  <ul>
    <li>Removed blank and duplicate records</li>
    <li>Standardized neighborhood names</li>
    <li>Created Occupancy Rate calculation</li>
    <li>Generated Estimated Revenue formula</li>
    <li>Created Price Band categories</li>
    <li>Handled divide-by-zero and negative value errors</li>
  </ul>

  <hr>

  <h2>Analytical Techniques Used</h2>
  <ul>
    <li>Pivot Tables</li>
    <li>Aggregation (Average, Count, Sum)</li>
    <li>Correlation Analysis</li>
    <li>Data Categorization</li>
    <li>KPI Scorecards</li>
    <li>Interactive Dashboard with Slicers</li>
  </ul>

  <hr>

  <h2>Final Outcome</h2>
  <p>
    The dashboard provides clear, data-driven insights into pricing strategy, 
    occupancy behavior, and revenue optimization opportunities for Airbnb hosts.
  </p>

  <p><strong>Result:</strong> A structured pricing decision framework for maximizing Airbnb revenue.</p>

</body>
</html>
