# Calendar-Dimension
This repository provides scripts with which you can create a calendar dimension table for use in BI and Power BI projects.

The implementation is with set operations, and includes the basic holidays we have in Greece, USA and EU Institutions. 
It also contains the algorithms for finding Orthodox Easter and Catholic Easter, which is an important milestone in finding holidays on movable dates.

# Script Parameters
Before running, however, some values should be set in parameters that exist according to your needs, these are:

### SET DATEFIRST	
Sets the first day of the week. It is valid for Calendar & Fiscal year as the ISO year starts from Monday. 1 is Monday ... 7 is Sunday.

### SET LANGUAGE US_ENGLISH	
Sets the language to be used. It's a good idea not to change it.

### SET DATEFORMAT YMD	
Sets the format of the dates. It's a good idea not to change it.

### @startdate	
Sets the start date that we want to have in calendar dimension table.

### @numberofyears	
Sets the number of years we want to have in calendar dimension table.

### @ISOQuarterType	
Sets the formula for the distribution of the quarters in ISO Year. Valid values are 445, 544, 454.

### @FiscalYearStartMonth	
Sets the month we want the Fiscal year to start.

### @FiscalYearStartMonthDay	
Sets the day we want the Fiscal year to start.

### @FiscalYearEndMonth	
Sets the month we want the fiscal year to end.

### @FiscalYearEndMonthDay	
Sets the day we want the Fiscal year to end.

### @FiscalYear	
Sets the year we want to have in fiscal year. For example if we have Fiscal Year from July 1, 2019 - June 30, 2020. if we set the value to 1 then this will be "FY 2019" if we set the value to 2 will be "FY 2020". The usual is to be "FY 2020" for this and the starting value is 2.

### @NationalCulture	
Sets the language that the fields containing the strings of the day name and month name will have in an international language.

### @LocalCulture	
Sets the language that the fields containing the strings of the day name and month name will have in our language.
