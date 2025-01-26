# Lab 3: Querying a Knowledge Base in Prolog

## Objectives

  1. Develop a knowledge base by implementing a given family tree.
  2. Query the knowledge base for information retrieval.
  3. Validate the implementation using various queries.
  4. Extend the knowledge base by adding additional rules and re-evaluating queries.

## Background Theory<br>

Propositional Logic – A branch of logic that deals with statements or propositions, focusing on their truth values (true or false).
<br>

Forward and Backward Chaining:<br>

Forward Chaining begins with known facts and applies inference rules to derive conclusions until the desired goal is reached. <br>

Backward Chaining starts with a goal and works backward to identify supporting facts and rules that satisfy the goal.<br>

Production Rule System – A framework that consists of rules, facts, and an inference engine to draw conclusions. The rules typically follow an "if-condition-then-action" structure.

## Procedure

1. Defining the Family Tree:
  - Establish Prolog facts to represent family relationships (e.g., male, female, husband, father).
  - Define rules to determine relationships such as grandfather, mother, and uncle using Prolog predicates.
2. Consulting the Knowledge Base:
  - Load the knowledge base into the Prolog interpreter (e.g., SWI-Prolog) using the consult command.
3. Executing Queries:
  - Test the knowledge base with queries such as:
    - ?- brother(Who,ram).
    - ?- uncle(Who,kush).
    - ?- sister(Who,preeti).
4. Enhancing the Knowledge Base:
  - Incorporate more sophisticated rules, such as handling uncles both by blood and through marriage.
  - Rerun queries to validate the updated rules.

## Results
The following are sample outputs from executed queries:


## Conclusion

The Prolog-based family tree was successfully developed and tested with various queries. Relationships such as brother, uncle, grandfather, and sister were verified. Expanding the rules improved the knowledge base's reasoning capabilities, highlighting Prolog’s strength in handling relational data and inference processing.
