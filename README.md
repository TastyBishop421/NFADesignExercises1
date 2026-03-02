# 1.
- #20 took the longest because I spent a while trying to figure out if I could simplify it, but could not find a way.
- I did not avoid any specific problem, and I didn't find anything too challenging necessarily. I made a few mistakes in some of my first attempts but they were easily fixable.
- I searched online/asked AI to double-check some information(like if a dfa would be the most simplified nfa of a particular set)

# 2. 
- for #11, my initial design was set up to go to the next state after a 1, then move to the final state after any bit, where it would then remain if it received any more 1s, or go back to the starting state if it received a 0. However, if a string had entered the final state from a 0 bit, then read another 1, it would remain in the final state despite it's 2nd to last now being 0. 
- I did not draw out computation trees for my nfas until after I identified a gold-st-ring during multiple runs. I should draw them out even if I think my design is correct just in case I overlook anything, or I do not have access to jflap or other tools at the moment.

# 3. 
- if a set is a union of 2 conditions (OR/AND), then it appears likely that the most optimal NFA will also be a valid DFA.