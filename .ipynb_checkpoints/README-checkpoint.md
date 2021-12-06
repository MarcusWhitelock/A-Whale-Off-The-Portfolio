# a_whale_off_the_portfolio
Week 3-4 Homework assingment 

The Elements Directory contains all the csv files and the whale_analysis_main jupyter source file containing the finalised code. 

The following is the approach and plan I followed as stated in the whale_analysis_main file:

- I will be creating a tool to analyse the major metrics of portfolios and that determines which ones outperform others.
- I will be completing the first section with given portfolios that need to be analysed 
- I will then be completing the second section where I gather my own information from google sheets with googlefinance formula and then comparing it
  to the first sections portfolios to see which ones outperform and evaluate if my portfolio is better. 
The process will go as follows:

1. Initail imports
Section 1
2. Setting paths for and reading in the csv's given
3. Cleaning the data and combining all portfolios
4. Analysing the data and ploting for clear results
Section 2
5. Setting paths for and reading in the downloaded csv's from my google sheets 
6. Cleaning the data and combining all my portfolios
7. Converting to daily returns
8. Combining with section 1 combined dataframe
9. Analysing the data of both sections together and plotting for clear results


I used google sheets to pull the info for my csv's as required.
All requirements a met as seen in the requirements below. 

The following is the requirements for this task:
Requirements

Data Preparation  (20 points)

To receive all points, you must:

Use Pandas to read each CSV file in as a DataFrame. (3 points)
Detect and remove all null values. (4 points)
Convert the S&P 500 closing prices to daily returns. (5 points)
Join the Whale Returns, Algorithmic Returns, and the S&P 500 Returns into a single DataFrame with columns for each portfolio's individual returns. (8 points)


Quantitative Analysis (20 points)

To receive all points, your code must:

Calculate and plot the daily and cumulative returns of all portfolios. (2 points)
Create a box plot for each of the returns. (2 points)
Calculate the standard deviation for each portfolio. (2 points)
Determine which portfolios are riskier than the S&P 500. (3 points)
Calculate the annualized standard deviation for each portfolio. (2 points)
Calculate and plot the rolling standard deviation for all portfolios using a 21-day window. (3 points)
Calculate and plot the correlation between each stock to determine which portfolios may mimic the S&P 500. (3 points)
Choose one portfolio, then calculate and plot it's beta as compared to the S&P 500. (3 points)


Sharpe Ratios (15 points)

To receive all points, your code must:

Use the daily returns to calculate the Sharpe ratios. (4 points)
Visualize the Sharpe ratios using a bar plot. (3 points)
Determine whether the algorithmic strategies outperform both the market (S&P 500) and the whales portfolios. (8 points)


Custom Portfolio (15 points)

To receive all points, your code must:

Use the Google Finance function to choose a portfolio. (3 points)
Download the data needed as CSV files and calculate the portfolio returns. (4 points)
Add the portfolio returns to the DataFrame with the other portfolios, then analyze and compare all portfolios. (8 points)


Coding Conventions and Formatting (10 points)

To receive all points, your code must:

Place imports at the beginning of the file, just after any module comments and docstrings and before module globals and constants. (3 points)
Name functions and variables with lowercase characters and with words separated by underscores. (2 points)
Follow Don't Repeat Yourself (DRY) principles by creating maintainable and reusable code. (3 points)
Use concise logic and creative engineering where possible. (2 points)


Deployment and Submission (10 points)

To receive all points, you must:

Submit a link to a GitHub repository that’s cloned to your local machine and contains your files. (5 points)
Include appropriate commit messages in your files. (5 points)


Code Comments (10 points)

To receive all points, your code must:

Be well commented with concise, relevant notes that other developers can understand. (10 points)