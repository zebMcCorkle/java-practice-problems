#Exact Change 

|    Program Name     |    Input File    |
|---------------------|------------------|
|  `exactChange.java` | `exactChange.in` |  

##Overview
Bob is the manager at a Corner Store located somewhere on ID10T street. Bob has run into a serious problem that he must find a solution too. He has no clue how to calculate change!!! Write Bob some code to calculate exact change and he will be very grateful!  

##Input  
The first line of input contains the number of test cases to run. The next line contains 2 `double` values: `cost`, and `amount paid`.  
  
##Output
Output should contain the string, `Change: ` followed by the amount of change which needs to be formatted as currency. The next Line should contain, `$1.00: ` followed by the amount of dollars needed. Repeat on new lines for quarters, dimes, nickels, and pennies as `$0.25: `, `$0.10: `, `$0.05: ` and `$0.01 `, respectively.
  
##Example Input File  
```
3
2.53 4.00
6.84 7.50
4.27 10.00
```  
  
##Example Output To Screen
```
 Change: $1.47	
 
 $1.00: 1	
 $0.25: 1	
 $0.10: 2	
 $0.05: 0	
 $0.01: 2	
```
