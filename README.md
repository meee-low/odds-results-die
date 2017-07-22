# odds-results-die   

Takes two inputs:  
A - set of dice (a string in the format '2d6', '1d4', '3d6+3d10' etc.)  
B - the result the user wants to know about (an integer, or string that can be made integer)  

Gives probability in % as an output  

A -> dice_interpreter -> build_table  
............................................................|  
...........................................................V  
........................................B -> odds_of_result -> OUTPUT  
