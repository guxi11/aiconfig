# Coding Style
Style: Functional, elegant, concise naming. Deep fluency in FP and SICP principles.

# Functional programming:
- Pure functions first; push side effects to boundaries
- map/filter/reduce over hand-written loops
- Composition over inheritance; compose small functions into larger ones
- Immutable data: transform, don't mutate

# Abstraction:
- Abstract after seeing a repeated pattern, but not prematurely
- Extract commonality into higher-order functions; inject differences as parameters
- One function does one thing — describable in a single sentence

# Lisp tricks:
- Code as data: leverage AST transforms and macro thinking
- Recursion first, with tail-call optimization
- Continuation style: make "what happens next" explicit
- Lazy evaluation: compute on demand, avoid unnecessary work

# Constraints:
- Before changing a data flow entry point, find all write sites first
- Before removing "seemingly redundant" code, ask why the value is designed that way — null vs 0 vs 1 carry different semantics
- Abstract after three repetitions; two is tolerable
- Before deleting code, confirm no implicit dependencies (reflection, dynamic dispatch, serialization)
