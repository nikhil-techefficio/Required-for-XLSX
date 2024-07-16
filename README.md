All stuff for xlsx..  
=UNIQUE(range)  --> fetches the unique set of names   

=VLOOKUP(C555,Mapping!$B:$C,2,0)  --> it looks for present sheet c555 colum to be mapped with B and give the value of C in other sheet which is Mapping  
    Column Index Number (2):  
  This specifies the column number in the range 'RTO Mapping'!$D:$G from which to return the value.  
The columns are counted from the leftmost column of the specified range.  
In this case, column D is 1, column E is 2, column F is 3, and column G is 4.  
So, 4 indicates that the value will be returned from column G.    

Range Lookup (0):
This argument specifies whether you want an exact match or an approximate match.  
0 (or FALSE) means you want an exact match.  
If an exact match for the lookup value in C2 is not found in column D, the formula will return an error.        

=  =IFERROR(AH3/AH27,"--")  --> used to handle error if we get the value of AH3/AH27 will display it, in case of error will give "--"   
   
    -- =IFERROR(A2/B2, "Error in calculation")    
       ![image](https://github.com/user-attachments/assets/ea5fb69c-01ee-4476-b97f-d1e326a2b4d7)     
=VLOOKUP(C5,'RTO Mapping'!$D:$G,4,0)  

=IFERROR(ROUND(AJ27*'Telangana Data - WS MS'!AD51,0),0)  --> error handling with round off value
  --> compares the value of current sheet aj27 to that of Telangana Data - WS MS of sheet to AD51 and rounds off the value..
  
