<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Project Gallery</title>
  <style>
    body {
      font-family: "Segoe UI", Arial, sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 20px 0;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.2s ease;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card .content {
      padding: 15px;
    }

    .card h3 {
      margin: 0 0 10px;
      font-size: 1.2em;
      color: #333;
    }

    .card p {
      font-size: 0.95em;
      color: #555;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>My Visualization Portfolio</h1>
    <p>A collection of my projects and data visualizations</p>
  </header>

  <div class="gallery">
    <!-- Project 1 -->
    <div class="card">
      <a href="https://github.com/Favourson/PortfolioProjects/blob/main/Customer%20Churn%20Analysis%20and%20Prediction/Customer%20Churn%20Prediction.ipynb" target="_blank">
        <img src="Images/project1.png" alt="Project 1 Screenshot">
      </a>
      <div class="content">
        <h3>
          <a href="https://github.com/Favourson/PortfolioProjects/blob/main/Customer%20Churn%20Analysis%20and%20Prediction/Customer%20Churn%20Prediction.ipynb" target="_blank">
            Project 1: Customer Churn Analysis
          </a>
        </h3>
        <p>A visualization of customer churn trends using Power BI and Python.</p>
      </div>
    </div>

    <!-- Project 2 -->
    <div class="card">
      <a href="https://github.com/Favourson/PortfolioProjects/tree/main/International%20Student%20Demographics%20Tableau" target="_blank">
        <img src="Images/project2.png" alt="Project 2 Screenshot">
      </a>
      <div class="content">
        <h3>
          <a href="https://github.com/Favourson/PortfolioProjects/tree/main/International%20Student%20Demographics%20Tableau" target="_blank">
            Project 2: International Student Analysis
          </a>
        </h3>
        <p>Analysis of domestic and international student behaviour.</p>
      </div>
    </div>
	
	<!-- Project 3 -->
    <div class="card">
      <a href="https://github.com/Favourson/PortfolioProjects/tree/main/Layoffs%20Analysis%20Project%20with%20Tableau" target="_blank">
        <img src="Images/project3.png" alt="Project 3 Screenshot">
      </a>
      <div class="content">
        <h3>
          <a href="https://github.com/Favourson/PortfolioProjects/tree/main/Layoffs%20Analysis%20Project%20with%20Tableau" target="_blank">
            Project 3: Layoffs Analysis
          </a>
        </h3>
        <p>Understanding the layoff trends in different countries</p>
      </div>
    </div>
	
	<!-- Project 4 -->
    <div class="card">
      <a href="https://github.com/Favourson/PortfolioProjects/tree/main/FinanceTradingStrategies/Moving%20Average%20Crossover" target="_blank">
        <img src="Images/project4.png" alt="Project 4 Screenshot">
      </a>
      <div class="content">
        <h3>
          <a href="https://github.com/Favourson/PortfolioProjects/tree/main/FinanceTradingStrategies/Moving%20Average%20Crossover" target="_blank">
            Project 4: Financial Trading Model
          </a>
        </h3>
        <p>Variations of trading indicators with tests and results.</p>
      </div>
    </div>

	<!-- Project 5 -->
    <div class="card">
      <a href="https://github.com/Favourson/PortfolioProjects/tree/main/Covid%20-%2019%20Analysis" target="_blank">
        <img src="Images/project5.png" alt="Project 5 Screenshot">
      </a>
      <div class="content">
        <h3>
          <a href="https://github.com/Favourson/PortfolioProjects/tree/main/Covid%20-%2019%20Analysis" target="_blank">
            Project 5: Financial Trading Model
          </a>
        </h3>
        <p>Covid 19 Data Analysis</p>
      </div>
    </div>


    <!-- Duplicate and edit cards for more projects -->
  </div>

</body>
</html>


