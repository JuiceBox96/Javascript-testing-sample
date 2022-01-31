# Javascript-testing-sample
JavaScript testing
Came a across on codecademy for writing and testing javascript 


Tests As Documentation
Imagine explaining this Cake Bar app to someone else. How does it behave? Does it rely on other software? How do you run it on a computer? You could read every line in every file to figure that out. Or you could read the documentation.

Documentation is any content separate from implementation code that explains how it works or how to use it. It may provide more concise summaries and explanation than the implementation code can.

Documentation can come in many forms, including plain text, diagrams…and tests! Tests as documentation provide what many other forms cannot: both human-readable text to describe the application and machine-executable code to confirm the app works as described.

Regression
The new “clear order” button feature has been implemented to satisfy the new test.

When adding a new feature to your product, it’s possible that something will break. If that break occurs within a feature developed earlier, it is called regression. When functionality previously developed and tested stops working, you may say the functionality regressed.

Running an automated test suite is fast and repeatable, which means you can run tests after every change to confirm that old features still work. If they have regressed, the test output should notify you.



The TDD has 3 phases:





RED. First write a unit test in failure. The impossibility of compiling is a failure.

GREEN. Write as soon as possible the production code sufficient to pass this unit test even if it means allowing the “worst” solutions. Of course if a clean and simple solution appears immediately, it must be realized but otherwise it is not serious the code will be improved incrementally during the refactoring phases. The aim here is to obtain as soon as possible the green bar of success of the unit tests.

REFACTOR. This phase is often neglected but is essential because it eliminates possible code duplications but also makes it possible to make changes in architecture, factorization, presentation… This refactoring concerns both the production code and the test code and must not modify the external behavior of the program, which is materialized by a test execution bar that remains green.
