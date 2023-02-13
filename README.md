# The-Finite-Automaton-and-operations-on-it
This project includes classes and methods that are built to perform various operations on FAs.(Final project for Fundamentals of Computational Theory)

# Overview

##Class DFA
#### This class contains methods that are called on Deterministic Automaton/Automatons.

### Method "isAccepted"
#### By receiving a string, this method determines whether the string is a member of the language or not.

### Method "generator"
#### By receiving the length number, this method Creates all possible strings up to the received length.(Limited SigmaStar)

### Method "isEmpty"
#### Determines whether the FA language is empty or not.

### Method "isInfinite"
#### Determines whether the FA language has an infinite number of members or not.

### Method "members_of_language"
#### Returns all members of the language as an list.

### Method "shortest_element"
#### Prints the shortest member of the language in the output.

### Method "longest_element"
#### Prints the biggest member of the language in the output.

### Method "supplement_dfa"
#### Returns the supplement FA of the current FA.

### Method "op"
####In this method, the following operations are implemented on two FAs.
####***(union,Subscription,the difference)
####***Detection of the subset of languages of two finite machines
####***Determining that the languages of two finite machines are separate from each other
####Note: operation op can be used in two ways: dfa1.op(dfa2) and DFA.op(dfa1,dfa2).

### Method "minimizing"
#### Prints the minimized form of current FA in the output.

## Class NFA
#### This class contains methods that are called on Nondeterministic Automaton/Automatons.

### Method "lambda_deleter"
#### Removes lambda transitions from the transition function.

### Method "fa_converter"
#### Converts NFA to DFA and returns it as an element of DFA class.

## Examples
### For better understanding, some examples are given along with the commands. (all methods covered)
