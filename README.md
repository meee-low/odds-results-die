# odds-results-die   

Takes two inputs:  
A - set of dice (a string in the format '2d6', '1d4', '3d6+3d10' etc.)  
B - the result the user wants to know about (an integer, or string that can be made integer)  

Gives probability in % as an output  

A -> dice_interpreter -> build_table  
............................................................|  
...........................................................V  
........................................B -> odds_of_result -> OUTPUT  


I spread some assertions around the code to make sure the input is in the right format,
but I don't really know how to do error handling very well and I dont know how that's
going to work with JS.
