# Latar

A mini [RDF Surfaces](https://w3c-cg.github.io/rdfsurfaces/) playground in Prolog.

Latar, Indonesian for 'surface', is an attempt to create a new RDF Surfaces implementation in Prolog using Peirce's [Existential Graph](https://en.wikipedia.org/wiki/Existential_graph) methods.

In the early experimental stage only the **Alpha** version of graphs is supported 
(isomorphic to propositional calculus).

# Install

Install SWIPL : https://www.swi-prolog.org/download/stable

# Run

`./test.sh`

# Examples

## Alpha

Propositional logic

- alice : a simple conditional `(Alice a Human) -> (Alice a Person)` 
- disjunction : a simple disjunction `(Alice likes Coffee) OR (Alice likes Tea)`
- nested_negation : 4 level deep negation eventually is an assertion
- lists : a simple lists test
- built-in : a simple built-in test

## Beta

First-order logic

- socrates : an OWL subClassOf example
- socrates2 : socrates but with two subClassOf statements
- abc : disjunction example
- abcd : disjunction plus triple nested negative surface example

See also: https://github.com/eyereasoner/eye/tree/master/reasoning/blogic
