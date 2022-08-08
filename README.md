# ood-principles
An Object Oriented Design Principles Solution

# SOLID Principles

SOLID is an acronym for the most popular design principles for object-oriented software development.
The acronym was created by Michael Feathers after noting that five principles of object orientation and code design — created by Robert C. Martin (a.k.a. Uncle Bob) and covered in The Principles of OOD — could fit this word.
These principles help the programmer to write cleaner code, separating responsibilities, reducing coupling, facilitating refactoring and encouraging code reuse.

| Acronym | Name | Description |
| ------------ | ------------|  ------------|
| SRP | The Single Responsibility Principle | A class should have one, and only one, reason to change. |
| OCP | The Open Closed Principle | You should be able to extend a classes behavior, without modifying it. |
| LSP | The Liskov Substitution Principle | Derived classes must be substitutable for their base classes.|
| ISP | The Interface Segregation Principle | Make fine grained interfaces that are client specific.|
| DIP | The Dependency Inversion Principle | Depend on abstractions, not on concretions.|

#### The first three package principles are about package cohesion, they tell us what to put inside packages:**

| Acronym | Name | Description |
| ------------ | ------------|  ------------|
| REP | The Release Reuse Equivalency | Principle	The granule of reuse is the granule of release.|
| CCP | The Common Closure Principle | Classes that change together are packaged together.|
| CRP | The Common Reuse Principle | Classes that are used together are packaged together.|

#### The last three principles are about the couplings between packages, and talk about metrics that evaluate the package structure of a system.**

| Acronym | Name | Description |
| ------------ | ------------|  ------------|
| ADP | The Acyclic Dependencies Principle | The dependency graph of packages must have no cycles.|
| SDP | The Stable Dependencies Principle | Depend in the direction of stability.|
| SAP | The Stable Abstractions Principle | Abstractness increases with stability.|

## Robert C. Martin Commandments

1. Software entities (classes, modules, etc) should be open for
extension, but closed for modification. (The open/closed
principle -- Bertrand Meyer)

2. Derived classes must usable through the base class interface
without the need for the user to know the difference. (The
Liskov Substitution Principle)

3. Details should depend upon abstractions. Abstractions should
not depend upon details. (Principle of Dependency Inversion)

4. The granule of reuse is the same as the granule of release.
Only components that are released through a tracking system can
be effectively reused.

5. Classes within a released component should share common closure.
That is, if one needs to be changed, they all are likely to need
to be changed. What affects one, affects all.

6. Classes within a released componen should be reused together.
That is, it is impossible to separate the components from each
other in order to reuse less than the total.

7. The dependency structure for released components must be a DAG.
There can be no cycles.

8. Dependencies between released components must run in the
direction of stability. The dependee must be more stable than
the depender.

9. The more stable a released component is, the more it must
consist of abstract classes. A completely stable component
should consist of nothing but abstract classes.

10. Where possible, use proven patterns to solve design problems.

11. When crossing between two different paradigms, build an
interface layer that separates the two. Don't pollute one side
with the paradigm of the other.

