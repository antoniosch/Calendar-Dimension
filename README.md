# Calendar-Dimension
In this repository provides scripts with which you can create a calendar dimension table for use in BI and Power BI projects

The implementation is with set operations and includes the basic holidays we have in Greece and in the USA and EU Institutions. 
It also contains the algorithms for finding Orthodox Easter and Catholic Easter, which is an important milestone in finding holidays on movable dates.

# Script Parameters
Before running, however, some values should be set in parameters that exist according to your needs, these are:



### SET DATEFIRST	
We set the first day of the week. It is valid for Calendar & Fiscal year as the ISO year starts from Monday. 1 is Monday to 7 which is Sunday

### SET LANGUAGE US_ENGLISH	
We define the language to be used. It's a good idea not to change it.

### SET DATEFORMAT YMD	
We define the format of the dates. It's a good idea not to change it.

### @startdate	
We set the start date that we want to have in calendar dimension table.

### @numberofyears	
We set the number of years we want to have in calendar dimension table.

### @ISOQuarterType	
We define the formula for the distribution of the quarters in ISO Year. The prices he can get are 445, 544, 454.

### @FiscalYearStartMonth	
We define the month we want the Fiscal year to start.

### @FiscalYearStartMonthDay	
We define the day we want the Fiscal year to start.

### @FiscalYearEndMonth	
We define the month we want the fiscal year to end.

### @FiscalYearEndMonthDay	
We define the day we want the Fiscal year to end.

### @FiscalYear	
We define the year we want to have in fiscal year. For example if we have Fiscal Year from 1/7/2019 - 30/6/2020 if we put the price one then this will be "FY 2019" if we put the value 2 will be "FY 2020". The usual is to be "FY 2020" for this and the starting value is 2.

### @NationalCulture	
We define the language that the fields containing the words of the days and months will have in an international language. That's why it has English as its original price.

### @LocalCulture	
We define the language that fields contain the words of days and months in the local language. Because we are in Greece the Greek language has been chosen as a starting price.

