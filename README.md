# ECE444-F2020-Lab6
This code is a copy of https://github.com/mjhea0/flaskr-tdd

## Question 3

**Pros**:
1. Makes code easier to maintain since TDD provides small tests.
2. Since tests are unit-tests, forces code to have a good architecture
3. Eases collaboration between developers - the unit tests forces programmers to code small sections, making it easier to divide the work amongst peers
4. Eases refactoring of code - since TDD unit tests are written before code, refactoring of code is made easier
5. Helps with requirement satisfaction. Since the tests written specify what is expected, the code has to be written to satisfy the test and thus the requirement.
6. Aids with regression testing - when adding new code to the code base, makes it easier since we know each granular part works as well

**Cons**:
1. Tests takes a lot of time to write, along with writing the actual code
2. Difficult to apply to older code
3. Has to be done by the whole team - otherwise still has to maintain code with dedicated test writing
4. Tests must be maintained - and may sometimes be outdated due to external libraries
5. Difficult to switch to TDD if another method was used prior
6. Hard to determine what to write unit tests for and not write unit tests for non-core functionalities
