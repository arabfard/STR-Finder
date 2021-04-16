# STR-Finder
C# tools for Short Tandem Repeat (STR) Finder Base ensembl 
How does nucleotide Tandem Repeats Finder work?
In order to find short tandem repeat sequences in a large sequence, a repeating loop is designed equal to the length of the large sequence Inside this loop.
All consecutive nucleotides are examined and their list is extracted.
This process is checked by a regular expression algorithm. 
A regular expression is a sequence of characters that defines a search pattern.
These patterns are usually used by sequence search algorithms to "find" operations on sequences.
This is a technique used in computer science, especially in formal language theory.
The following state machine automata represent all algorithm states.

This process is repeated for the length of the sequence for each nucleotide pair.
The implemented algorithm does not support mismatches (only perfect/pure STRs are analyzed). 
 
