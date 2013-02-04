SSISLoopWithFileName
====================

Loops through files and grabs file name as well to be entered into database.  To get filename into database, do one of two methods:

1.  On the CurrentFile connecting string, point it to an actual formatted file.  This should cause the derived column and flat file connection to recognize the format.  Only after everything is set up, then set the CurrentFile variable to blank.
2.  On the derived column, force a text field to pass into the database.
