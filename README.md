# Computation-of-LR-0-Items

Aim - 

To implement LR(0) Items

Algorithm –

Step 1 – Create structure for production with LHS and RHS.
Step 2 – Open file and read input from file.
Step 3 – Build state 0 from extra grammar Law S’ -> S $ that is all start symbol of grammar and one Dot ( . ) before S symbol.
Step 4 – If Dot symbol is before a non-terminal, add grammar laws that this non-terminal is in Left Hand Side of that Law and set Dot in before of first part of Right Hand Side.
Step 5 – If state exists (a state with this Laws and same Dot position), use that instead.
Step 6 – Now find set of terminals and non-terminals in which Dot exist in before.
Step 7 – If step 6 Set is non-empty go to 8, else go to 9.
Step 8 – For each terminal/non-terminal in set step 6 create new state by using all grammar law that Dot position is before of that terminal/non-terminal in reference state by increasing Dot 
point to next part in Right Hand Side of that laws.
Step 9 – Go to step 4.
Step 10 – End of state building.
Step 11 – Display the output.
