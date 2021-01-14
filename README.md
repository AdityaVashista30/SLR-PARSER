# SLR-PARSER

It is SLR parser, which is second stage of compiler construction, made using python 3.

The program takes a context free grammar from a text file. The program reads the input grammar and creates augmented rules for same along with list of terminals and non-terminals present in the grammar. 
Using these generated data program identifies the various transaction states which are further used with intial grammar to build GOTO and REDUCTION tables. 
Then the program asks for a string as input. 

Using the tables formed before, the program decides whether the input string follows the rules of given grammar or not.
