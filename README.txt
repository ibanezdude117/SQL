URL: https://github.com/ibanezdude117/SQL
Author: Chris Graves 
Email: chris.a.graves@gmail.com


1.  SQL Row Count by View:
	I was asked by a coworker how to get row counts fo all views in a database.  Unlike getting row counts from tables like the use of sys.partions, getting row counts for views, you must query the view itself.  I turned to google to help out my coworder but there was a mess of various attempts but did not yield the right results.  After about 10 minutes I thought I would script it out instead.  So here it is. 

2.  SQL Database Mail: 
	Most folks that I have worked with are not completely knowledgable in he use of SQL's databse mail command. Either they use it to provide some detail in txt form because they do not know how to enable HTML.  A little more complicated is using HTML with HTML and CSS tags to create a clean and professional looking email from the SQL's database mail funciton.  Just posting this heavily commented script 

3.  SQL Search All Databases
	I have often found myself needing to search for a key name in a database.  However thee does not seem to be a data dictionary or a seasoned enough analyst or DBA that can provide assistance when I am looking for a key name.  When working with a pluthera of tables, views, stored procedures or even UDF it is pretty simple to search in the current database. However it is pretty simple to use a simple select statment and use sys.objects or sys.tables or views but I really wanted a true global search.  The ability to run one query or create a stored procedure with one parameter to search across all objects and databases would save me time. 
	In query form, simply enter just the key word or words and this will fetch all results from various object types and display the results.  This can very easily be adapted to a UDF or stored procedure where you can pass the search term(s) and get the results back after creation. 

