# Ch.1

Chapter 1 explains why functional data structures are so hard compared to imperative data structures.

1. Functional programming requires immutable data, so programmers must not use destructive update.
2. Meanwhile, functional programming expects data structures update to keep the old copy around
3. There are some theoretic upper-bound on functional data structures as compared to their imperative counterpart; however, in practice this gap can be shrunken significantly by carefully crafting.

## Terminlogy

"Data structure" can mean many things in many context. Okasaki distinguishes the following:

- *An Abstract data type* -- a type can a set of related functions. Okasaki calls this an **abstraction**
- *A concrete realization of an abstract data type* -- an **implementation**
- *An instance of a data type* -- an **object** or a **version**
- *A unique identity that is invariant through updates* -- a **persistent identity**
