# How to create [if] logic statements in Excel 
## For Excel beginners

When working with a large amount of data, [if] logic statements can be a 
powerful way to organize information. You can sort through data by
adding conditions to cells. 

For example, if you had a spreadsheet filled with data and wanted to pick 
and choose data that was less than 10, you would writCe an [if] statement. 

Write  [=if(A1<10,A1,"")]
	*This statement means: if cell A1 is less than 10, then the 
	original value in A1 is populated in the cell
	*AND if it is not the case that the value in A1 is less than 10,
	then no content will appear in the cell. 

Logic statement | Excel statement format
-------------------------|--------------------------------
[(A1<10)?(A1)]?[{¨{A1<10)}?(A1)] |  =if(A1<10,A1,"")
Expressing an And statement | Omitting the And component 

