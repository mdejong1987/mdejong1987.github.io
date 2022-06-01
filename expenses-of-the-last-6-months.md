## Expenses of the last 6 months

**Project description:** Get insights of the monthly fixed chargers in a clear and visual way in order to recognize the biggest expenses. The data and visualisation will then be used to get more control over the monthly spendings and to look for opportunities to save money.

### Collecting the data
To get a good overview of the expenses it was important to not use very old data. I decided to export bank transaction data from the past 6 months that can be used and transformed in programs like Google Sheets/Excel.

Both programs have their size and function limits. But because of the size of the exported data I was able to perform my tasks in Google Sheets and the available option where sufficient.

### Cleaning and Analysing
I will outline the steps taken to get the data ready for analysing and visualisation

- Imported data into Google Sheets
- Made a copy of the original data sheet that can be used for transformation
- Removed duplicate rows, formatting and excessive white spaces
- Used conditional formatting to see rows where money was added to the bank account and manually removed these because they were not necessary for this analysis
- Converted the money column type to numbers and remove the subtraction signs so we would not run into any problems when using it in analysis.
- Because the date column was not in a format that could be used by Google Sheet functions I had to create new columns to separate the date parts into day, month, year by using the LEFT, MID, RIGHT function to subtract these parts. Then I combined these new columns with the DATE function.
- Copied the new dates as value in a new column because I could not use the date column with function code.
- Created new columns for organisation. These new columns were category, company and monthly recurring.
- Used conditional formatting again to see which transactions are recurring each month and updated the previous newly created columns with the correct data.
- Researched some transactions that were not clearly descriptive as to where the transaction was from and what was bought. Then updated these rows in the sheet.
- Because the data had rows with not recurring transaction I created a filter so I could filter out these non recurring transactions
- Created visualisation to the cleaned data and export this to a PDF file.
- Downloaded all working files to store locally and removed these from the cloud.

### Visualisation

<img src="images/personal_project_uitgaven_afgelopen_6_maanden.png?raw=true"/>

### Results

The data and visualisation showed clearly what the biggest monthly expenses were. To put this in the context of saving money I found out the most of the money was going towards subscriptions like Netflix, Disney+, Xbox Live and my personal habits.

The actions I took after this analysis was finding out what I still used and what not. If I decided I did not use it for a while and was not planning on using it in the near future I cancelled the subscription. I will be keeping an eye on the next couple of months to see if my choices and actions made any differences.
