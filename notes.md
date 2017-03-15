# Notes
## Polymorphism
### Parametric
Parametric polymorphism refers to when the type of a value contains one
or more (unconstrained) type variables, so that the value may adopt any
type that results from substituting those variables with concrete
types. [source](https://wiki.haskell.org/Polymorphism#Parametric_polymorphism)

e.g.
```haskell
id :: a -> a
id a = a
```

### AdHoc

Ad-hoc polymorphism refers to when a value is able to adopt any one of
several types because it, or a value it uses, has been given a separate
definition for each of those
types. [source](https://wiki.haskell.org/Polymorphism#Ad-hoc_polymorphism)

e.g. **Typeclasses(Show)**
