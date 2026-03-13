### Part-A

1. Identify the significance of a compiler with an example.
2. Define tokens, patterns and lexemes.
3. Differentiate bottom-up and top-down parsers with an example.
4. Compute regular definition for an identifier.
5. Differentiate LR, CLR and LALR with a suitable example.
6. Build a grammar by eliminating left recursion: `S->S*C/C; C->Cb/F; F->id`
7. Discuss handle pruning with an example.
8. Differentiate NFA and DFA.
9. Depict the schematic diagram for a language processing system.
10. Define the term coercion.
11. Differentiate compiler and interpreter.
12. Define ambiguous grammar with an example.
13. Eliminate the left recursion for the grammar: `A -> Ac | Aad | bd | c`
14. What is the need for type checking?
15. Mention the role of semantic analysis.
16. Illustrate error handling and recovery in a syntax analyser.
17. Define sentinel and input buffering.
18. Mention the role of syntax analysis.
19. Mention the role of lexical analysis.
20. Define Context Free Grammar.
21. Mention the compiler construction tools.
22. Define Thompson's rule.
23. Define recursive descent parsing with backtracking.

### Part-B

1. Illustrate the stack implementation of shift-reduce parsing for the grammar 
    ```
    E -> E - E
    E -> E * E
    E -> id
    ```
    with the input string `id1 - id2 * id2`.
2. Illustrate type checking with a necessary example.
3. Describe the various phases of a compiler with the output for the source program 
   `a = b + c * 45`.
4. Construct the minimized DFA for the regular expression `(a | b) * abb`.
5. Construct the predictive parser for the following grammar
    ```
    S -> ( L ) | a
    L -> L , S | S
    ```
    Construct the parser table on the sentence `(a, (a, a))` for the grammar specified.
6. Consider the following grammar:
    ```
    E -> E + T | T
    T -> T * F | F
    F -> ( E ) | id
    ```
    Construct predictive parsing table for the given grammar.
7. Construct the SLR parser table for the following grammar.
    1. `E -> E + T`
    2. `E -> T`
    3. `T -> T * F`
    4. `T -> F`
    5. `F -> ( E )`
    6. `F -> id`
8. Describe CLR parsing with an example.
9. Describe LALR parsing in detail with an example set of productions.
10. Define the following.
    1. Input buffering
    2. Specification of tokens
    3. Recursive descent parser
11. Identify the role of a lexical analyser and explain how input buffering is used to analyse source code.
12. Illustrate how backtracking is used in a recursive descent parser with an example.
13. Discover the significance of `lexeme_begin` and `forward` pointer in an input buffering scheme with pseudocode.
