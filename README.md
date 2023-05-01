# Useful-Macros-for-creating-large-unit-date-Panel-datasets
Generating a shell for your large panel data can be a tedious task, especially when dealing with a large number of units. However, this repository provides valuable Excel macros that can streamline the process of creating a framework. This project is a working progress.

When starting with a list of units, I recommend using the add rows VBA for the amount of years(/dates/other) that you will need. You can then use a simple "fill with above" function in all blank cells to past the units down. 

I then recommend taking your list of years(/dates/other) and entering it into the first unit. Then, use the Paste Down N Times VBA to paste it for your remaining units. 

Simply adjust the numbers in the macro accordingly. This will provide you with your full shell data. This is particulary useful with spatial data that has thousands of units that you want to capture in various time increments. 
