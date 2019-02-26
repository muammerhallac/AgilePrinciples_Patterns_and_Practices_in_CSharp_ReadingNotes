# Chapter 5 - Refactoring Notes

Refactoring is:  "the process of changing a
software system in such a way that it does not alter the external behavior of the code yet improves
its internal structure." - Martin Fowler @ Refactoring

Every Software module has 3 functions:

1. The function it performs while executing (the reason for the module's existence)
2. To afford change (almost all modules changes during their lives. it is the responsibility of developers to make sure that such changes are as simple as possible to make)
3. To communicate to its readers (developers who are not familiar with the module should be able to read and understand without undue mental gymnastic)

