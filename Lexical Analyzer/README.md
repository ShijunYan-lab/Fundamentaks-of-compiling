## Functions that can be achieved:
+ Use files for input and output;
+ Multiple errors can be found;
+ Each error has an error message, including the line where the error occurs and the error message;
+ Error message information is divided into categories;
+ Check for repeated storage of identifiers or constants with the same name;
+ Correctly establish links between word lists, name lists, and constant lists;
+ Handle comments correctly;
+ Output identifiers and C language keyword list.

## Principle:
- Use automata to identify input source code.
- If you want to add a category that the automaton can recognize, just add it in the case statement.

## Input and output
+ If you want to modify the input of the lexical analyzer, you need to modify the code segment in the file ‘test_to_dfa.txt’ to modify the input;
+ It will be output in the form of a file, and the output file name can be modified in the code segment.
