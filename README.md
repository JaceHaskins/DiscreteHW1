To run program specfically for mac you must first open terminal in home directory of file.
Then you must preform the command clang++ -std=c++11 -o Cpp_Template.exe Cpp_Template.cpp
./Cpp_Template.exe.

Expected Output: 
FORALL x (P(x) OR Q(x)) = False
EXISTS x (P(x) AND NOT Q(x)) = True

The program successfully produces the expected truth values for both logical statements over the given domain. It correctly identifies x = -1 as a counterexample that makes the universal statement false, while finding x = -2 as a valid witness that satisfies the existential statement.
