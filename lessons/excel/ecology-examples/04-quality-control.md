# Basic quality control and data manipulation in spreadsheets #

When you have a well-structured data table, you can use several simple techniques within your spreadsheet to ensure the data you’ve entered is free of errors. 

*Tip! before doing any quality control operations, ensure your data is stored as “values” and not as formulas.  Because formulas refer to other cells, and you may be moving cells around, you may compromise the integrity of your data if you do not take this step!

[Example: converting all data to values: use soybean aphid suction trap dataset for this section]

## Sorting ##
Bad values often sort to bottom or top of column. Sort your data by each field, one at a time. Scan through each column, but pay the most attention to the top and the bottom of a column. 
If your dataset is well-structured and does not contain formulas, sorting should never affect the integrity of your dataset.

[Example: sorting]

## Conditional formatting ##
 Use with caution! But a great way to flag inconsistent values when entering data.

[Example: conditional formatting]

## Check on cell formats ##
A good way to check if you’ve got data of the wrong type in a column is by checking column format. This can also help prevent issues when you export your data.

[Example: variable format]

## Pivot tables ##
Pivot tables are a very powerful tool in Excel. They’re useful to check for issues with data integrity because they provide a quick, visual way to spot things that are amiss, including with categorical variables. They are also great for reshaping data and obtaining summary statistics quickly in a drag and drop interface.

[Example in Pivot Table]

Why would I need to reshape my data? Different analyses require data to be in different formats- example: taking a species list to a diversity analysis.

[Use species list example]

Note: these operations can be done in most statistical or programming packages (i.e. using reshape2, plyr  in R)