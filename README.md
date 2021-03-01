# End of Day (EOD) Batch Process

Financial institutions have to perform Start of Day (SOD) process before it can carry out transactions for a specific date. Similarly, the End of Day (EOD) job must be run to process the transaction created during the day. When the scheduled EOD job completes, the system is advanced to the next date automatically. 
 
The EOD process can be performed manually, as well as automatically, as scheduled jobs through a job scheduler. The EOD jobs involved closing down daily activities, processing transactions and backing up all data.

Keywords
end of day, start of day, intraday, capital market, trading system, financial solution

1.	How to schedule an automatic End of Day job  in FinPricing?
•	Click the BatchRisk tab at the top-left corner of the application. Then, expend Batch -> Auto -> End of Day. If you created an auto end of day (EOD) scheduler already, it will be displayed in the main window.

 

•	A user can modify the scheduled time and then click the Save button to  save the changes.
•	If the user have never created an auto EOD scheduler, he can click the New button. A new auto EOD template is displayed in the main window.
•	Fill the time on which the user wants the EOD batch job to start daily and then click the Save button. A new auto EOD scheduler is created.

2.	How to run an End of Day job manually in FinPricing?
•	Click the BatchRisk tab at the top-left corner of the application. Then, expend Batch -> Manual and select End of Day.
 
•	A selection window pops up. You can select AllBooks or a particular leaf book (e.g., Interest Rate). All the EOD dates already generated in the system are displayed in the main window. You can either click the New button with a new Valuation Date to run a new EOD job right away or the Load button with a selected date to load existing EOD results.

 

	If you input a new Valuation Date (e.g., 2/5/2018) at the top-right corner of the selection window and click the New button. FinPricing start to run the EOD for the book "Interest Rate" on 2/5/2018. The results are shown in the Result tab of the main window.

 

•	Note that all tradeIds in the results are underlined that means you can further drill down the results. Click a tradeId (e.g., T000000120010000026). The drill-down results are displayed in the DrillDownResult tab of the main window.

 

•	In addition, a more visually intuitive book composition distribution graph is given in the Graph tab.
 

3.	How to run the profit & loss (P&L) job manually in FinPricing?
•	Click the BatchRisk tab at the top-left corner of the application. Then, expend Batch -> Manual and select Profit and Loss (P&L).

 

•	A selection window pops up. You can select AllBooks or a particular leaf book (e.g., Interest Rate). After that, a P&L selection template is displayed in the main window. You choose the FirstDate and SecondDate, and then click the Load button. Note that the second date should be larger/later than the first date.
 
•	The total P&L and all the deal-level P&Ls are displayed in the Result tab of the main window.
 

•	The P&L distribution based on asset classes is shown in the Graph tab of the main window.
 

You can find more details at
https://finpricing.com/faq.html

