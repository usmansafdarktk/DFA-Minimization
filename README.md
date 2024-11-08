# DFA Minimization Program

## Overview
This program takes a deterministic finite automaton (DFA) as input and outputs an equivalent minimized DFA with the smallest possible number of states, preserving the original language.

<br>

## Instructions

#### BUILD & EXECUTE
Run the following commands in the root directory:
- Compilation: 
```bash
g++ -o "dfa-minimization" dfa-minimization.cpp
```
- Run the executable: 
```bash
./dfa-minimization
```

#### INPUTS
You need to provide following details of the dfa:
- number of states;
- size of alphabet;
- alphabet;
- transition table;
- index of initial state;
- number of final states;
- indices of final states;

#### OUTPUTS
Following details will be printed:
- reachable states in the input dfa;
- reachable non-final states of the input dfa;
- reachable final states of the input dfa;
- number of equivalence states partitions;
- all equivalence states partitions;
- transition table of the equivalent minimized states dfa;
