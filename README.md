Download Link: https://assignmentchef.com/product/solved-stat480-homework-7
<br>
For this assignment, submit one .hive script file containing all the necessary Hive code to generate your results and one text-based report file (Word doc, pdf, or .txt file). The <strong>Hive script file should be an executable </strong><strong>.hive file</strong>

(If using the Hue editor or running your code in steps at command line, you may copy the code and paste it into a Notepad++ file with extension .hive.).




Use Hive for all exercises. Any code based on code from elsewhere (e.g. code provided with the text) must reference in comments the source of the original code.




All exercises are based on the stocks data set in stocks.csv which accompanies <em>Programming Hive: Data </em>

<em>Warehouse and Query Language for Hadoop</em> by Edward Capriolo, Dean Wampler, and Jason Rutherglen [<a href="http://proquest.safaribooksonline.com/book/databases/hadoop/9781449326944">Safari</a> <a href="http://proquest.safaribooksonline.com/book/databases/hadoop/9781449326944">Online</a><a href="http://proquest.safaribooksonline.com/book/databases/hadoop/9781449326944">]</a>. The data is available in the zip file available from the book’s <a href="https://github.com/oreillymedia/programming_hive">github page</a><a href="https://github.com/oreillymedia/programming_hive">.</a> You will need to download the book source from github (use the green “Clone or download” button, or click on the .zip file and then click “Download”), extract the files and get the stocks.csv file from the data folder.

<strong>Note:</strong> If you open stocks.csv in Excel, <strong>do not</strong> save the file. Large files may not open entirely in Excel and saving an incompletely opened file will result in a loss of data.

<strong>Exercises for All Students </strong>

<strong>Exercise 1: </strong>Create and populate a stocks table for the stocks data. The table should contain the same columns as the data set (market, stocksymbol, datemdy, price_open, price_high, price_low,

price_close, volume, price_adj_close). The first three fields should be STRING; the price fields should be FLOAT; and volume should be INT.




Show 5 records from the table.

<strong>Exercise 2: </strong>

Create a table for the records for IBM (stock symbol “IBM” in the NYSE market).  Show 5 results from that table.




Using Hive queries find the highest daily high price and the lowest daily low price for IBM within the data set, and the dates on which those max high and min low prices occurred.

<strong>Exercise 3: </strong>

Create a view for the max daily spread (high price – low price) for each stock symbol and include the market in the view (group by symbol and market in case the same symbol occurs on multiple markets).

Obtain the minimum, average, and maximum daily spreads from the data in this view.