# Implementing Cmm compiler in 4 phases

## Phase 1: Lexer & Parser
Implement all needed tokens using ANTLR4.\
Test the grammar using Parse Tree and print inputs and outputs.\
No need to check semantic rules.

## Phase 2: Semantic Analysis
First part of Semantic Analysis.\
Gathering informations about structures,functions,scopes and save in the symbol table.\
Creating AST, and implement Appropriate actions for C-- grammar.

## Phase 3: Type Checking
Compelete previous phase.Last part of Semantic Analysis.\
Finish semantic analysis, and implement typechecking.

## Phase 4: Byte Code
implementing bytecode generator.\
In this phase the final compiler can convert the C-- program into an underestandable code for computer.
