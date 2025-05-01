<h1>Tesla Stock Data Analysis (2010–2024)</h1>
<p>
      This project conducts a time-series analysis of Tesla’s stock performance over a 14-year period (2010–2024). 
      Using R and tidyverse libraries, the notebook explores historical trends, volatility, and moving averages to help 
      investors and analysts better understand Tesla's stock behavior and make more informed decisions.
    </p>
    <h2>Project Objective</h2>
    <p>To uncover trends and performance factors of Tesla's stock price to support investment decision-making through visual analysis and statistical insight.</p>
    <h2>Dataset Overview</h2>
    <p>Dataset sourced from 
      <a href="https://www.kaggle.com/datasets/simronw/tesla-stock-data-2024" target="_blank">Kaggle</a> includes:
    </p>
    <ul>
      <li>Date: Daily trading date</li>
      <li>Open, High, Low, Close: Stock pricing metrics</li>
      <li>Adj Close: Adjusted close price with splits/dividends</li>
      <li>Volume: Number of shares traded</li>
    </ul>
    <h2>Key Questions Answered</h2>
    <ul>
      <li>How has Tesla’s stock price evolved from 2010 to 2024?</li>
      <li>What are the patterns in daily returns?</li>
      <li>How volatile is the Tesla stock?</li>
      <li>What do short-term and long-term moving averages reveal about price trends?</li>
    </ul>
    <h2>Visualizations & Insights</h2>
    <ul>
      <li><span class="highlight">Daily Returns Graph:</span> Highlights significant daily fluctuations and high volatility.</li>
      <li><span class="highlight">Moving Averages Plot:</span> Shows Tesla’s closing price alongside 10-day (SMA_10) and 30-day (SMA_30) moving averages.</li>
    </ul>
    <p><strong>Key Observations:</strong></p>
    <ul>
      <li>Tesla's stock was relatively stable from 2010 to 2019.</li>
      <li>A dramatic price rise began around 2020 and continued through 2024.</li>
      <li>Stock shows high volatility during the 2020–2024 period.</li>
    </ul>
    <h2>Tools & Libraries Used</h2>
    <ul>
      <li><strong>R Language</strong></li>
      <li><strong>tidyverse</strong>: Data wrangling and transformation</li>
      <li><strong>ggplot2</strong>: Data visualization</li>
      <li><strong>zoo</strong>: Calculating rolling/moving averages</li>
    </ul>
