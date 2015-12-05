Lazy evaluation illustrated
===========================
  for Haskell divers
  ------------------

This is an illustrated document about lazy evaluation in Haskell

Here is: [Lazy evaluation illustrated for Haskell divers]
(http://takenobu-hs.github.io/downloads/haskell_lazy_evaluation.pdf) (PDF).


Contents
--------
1. Introduction
  - Basic mental models
  - Lazy evaluation
  - Simple questions
2. Expressions
  - Expression and value
  - Expressions in Haskell
  - Classification by values and forms
  - WHNF
3. Internal representation of expressions
  - Constructor
  - Thunk
  - Uniform representation
  - WHNF
  - let, case expression
4. Evaluation
  - Evaluation strategies
  - Evaluation in Haskell (GHC)
  - Examples of evaluation steps
  - Examples of evaluations
  - Controlling the evaluation
5. Implementation of evaluator
  - Lazy graph reduction
  - STG-machine
6. Semantics
  - Bottom
  - Non-strict Semantics
  - Lifted and boxed types
  - Strict analysis
  - Sequential order
7. Appendix
  - References
