# The Expression Problem and Lenses

The Expression Problem (TEP), a new name by Phil Wadler for an old problem, has
presented challenges to programmers for decades. The practical considerations
are particularly pertinent in safe, purely-functional programming where
accurate representations of software models are a primary goal.

Proposed approaches to TEP have consistently fell short of a reasonable
solution.

In this talk, I will use the Haskell lens library to propose a resolution to TEP
that achieves all the desired benefits, with minimal penalty. I will first
describe The Expression Problem, the principles of the lens library, then
demonstrate a principled resolution to TEP.
