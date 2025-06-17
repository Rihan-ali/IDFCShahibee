Extracted raw transaction data from a PDF IDFC bank statement using Python (pdfplumber, pandas) and structured it into a clean Excel file.

Loaded, transformed, and cleaned the data further using Power Query Editor in Power BI.

Built a custom Calendar Table to support time-based analysis and aggregation.

Designed an interactive dashboard with KPI cards, dynamic filters, and time series charts using DAX formulas.

 Dynamic Filtering & Interactivity:
Used slicers for filtering by:

Year

Month

Transaction Type

Enabled drill-through for individual transaction insights.

 DAX Measures Used:
Total Debit = SUM(Transaction[Debit])

Total Credit = SUM(Transaction[Credit])

Average Monthly Spend = AVERAGEX(MONTH(Transaction[Date]), SUM(Transaction[Debit]))

Closing Balance = LASTNONBLANK(Transaction[Date], SUM(Transaction[Balance]))

Tools & Tech Used:
Python: pdfplumber, pandas (for PDF extraction and structuring)

Power BI: Power Query Editor, Data Modeling, DAX, Interactive Charts


Key Insights :-
Sum total transation balance =316.34M
TOTAL debit and Creadit balance =141.53
From the bar chart the highest transaction balance in the month of febuary in all companies And if we talk about a single company so the SWIPE AGAIN highest trasaction in the month of  AuGUST WITH THE WORTH OF MORE THEN 30M.
SWIPE EXPERT SOLUTION highest transaction in the month of FEBUARY with the worth of 4M.
SWIPE AUCTION highest transaction in the month of DECEMBER with the worth of 51M



