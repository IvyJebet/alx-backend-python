## 0x03. Unittests and Integration Tests

## Unittests and Integration Tests
Welcome to the "Unittests and Integration Tests" project! This README will guide you through the tasks and requirements for this project, which focuses on writing unit tests and integration tests using Python's unittest framework.

## Testing Overview
## Unit Tests
Unit tests focus on individual functions and methods. They verify that a function returns the expected results for a given set of inputs. Unit tests should:
- Test only the logic inside the function.
- Use mocking for external calls (e.g., network or database interactions).
- Integration Tests
- Integration tests check the interaction between various parts of your code. They:

- Test end-to-end functionality.
- Use less mocking compared to unit tests, typically only mocking external calls.
- Instructions
- Running Tests

## To execute your tests, use the following command:
$ python -m unittest path/to/test_file.py

##Learning Objectives
By the end of this project, you should be able to:
- Explain the difference between unit and integration tests.
- Describe common testing patterns, such as mocking, parameterization, and fixtures.

## Resources
- unittest — Unit testing framework
- unittest.mock — mock object library
- How to mock a readonly property with mock?
- parameterized
- Memoization
