# COVID-19 Data Analysis Project
This project analyzes the global spread and impact of COVID-19 using Python, Pandas, and Matplotlib. It explores country-wise trends, compares India and the US, calculates fatality rates, and visualizes the top 10 most affected countries.
# Objectives 
- Load and explore a real-world COVID-19 dataset  
- Clean and preprocess the data  
- Compare the pandemic trends in India and the United States  
- Calculate fatality rates across countries  
- Visualize insights using line and bar charts  
# Dataset 
- Source: [Our World in Data](https://ourworldindata.org/coronavirus)  
- Format: CSV file  
- Features used: `location`, `date`, `total_cases`, `total_deaths`, `population`  
# Tools Used 
- Python  
- Pandas  
- Matplotlib  
- Google Colab  
# Visualizations 
- Line Chart: India vs US – Total COVID-19 Cases Over Time  
- Bar Chart: Top 10 Countries by Fatality Rate  
- Additional insights based on filtered and cleaned data  
# Data Cleaning Steps 
- Handled missing (`NaN`) values in key columns  
- Filtered dataset for selected countries  
- Created new column: `fatality_rate = (total_deaths / total_cases) * 100`  
- Fixed an issue where a graph was showing blank due to `NaN` values — handled missing data to correct the visualization  
# Key Insights 
- Initially, one of the graphs appeared blank — this was caused by missing values (`NaN`) in the dataset. After cleaning the data properly, the graph displayed correctly  
- The US had a higher case count than India, but trends followed similar waves  
- Some smaller countries had significantly higher fatality rates  
- Data visualization helps to highlight severe impact zones globally  
# How to Run 
1. Download the `.ipynb` notebook  
2. Open it in Google Colab or Jupyter Notebook  
3. Make sure the required CSV file is in the same directory or update the file path  
4. Run the notebook cells one by one to see the analysis and graphs  
# Project Status 
- Completed – Beginner-level data analysis project  
- Future Work – Planning to add Power BI dashboard or interactive maps  
# Contact 
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/radhika-singla-864610328/) or message me for collaboration.
