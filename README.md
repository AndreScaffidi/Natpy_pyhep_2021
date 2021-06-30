# Natpy pyhep 2021

In high energy physics, the standard convention for expressing physical quantities is natural units. The standard paradigm sets c = ℏ = ε₀ = 1 and hence implicitly rescales all physical quantities that depend on unit derivatives of these quantities.

We introduce NatPy, a simple python module that levarages astropy.units.core.Unit and astropy.units.quantity.Quantity objects to define user friendly unit objects that can be used and converted within any predefined system of units.

In this talk, we will overview the algebraic methods utilized by the NatPy module, as well as some worked examples to demonstrate how NatPY can seemlesly integrate into any pythonic particle physics workflow.