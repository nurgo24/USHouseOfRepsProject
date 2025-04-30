<h1>US House Of Representatives Project</h1>

<h2>Description:</h2>

This project explores how rising expenditures by the U.S. House of Representatives correlate with broader economic challenges, including median family income and employment trends. By analyzing House Disbursement Data alongside U.S. Census API data, I investigated how taxpayer dollars are spent, which categories are driving cost increases, and how these patterns may contribute to inflationary pressure on American households.

<h2>Tools & Technologies:</h2>

- Python (Pandas, Altair, Matplotlib)
- Jupyter Notebook
- US House Dispersement Reports
- US Census Beareu API
- Data cleaning, trend analysis, visualization

<h2>Project walkthrough:</h2>

Loading in the CSV file with the House Disbursement Data.
<img width="1359" alt="Screenshot 2025-04-30 at 1 56 36 PM" src="https://github.com/user-attachments/assets/b43aba22-61e8-4002-a8e4-0e10963e4801" />
 

Taking the "CATEGORY" and "AMOUNT" columns from the dataset and adding the total amount spent per year on each category. In this disbursement dataset "CATEGORY" refers to what the money is being spent on, and "AMOUNT" refers to the amount of money (USD) being spent.
<img width="1343" alt="Screenshot 2025-04-30 at 2 19 05 PM" src="https://github.com/user-attachments/assets/78bd98e0-9e02-4755-9170-bd1ac427169e" />


Using Altair to create a stacked bar chart showing the total amount spent on each category per year.
<img width="1339" alt="Screenshot 2025-04-30 at 2 21 12 PM" src="https://github.com/user-attachments/assets/2757eee8-79da-44f3-9624-8397cbc0d1a2" />


