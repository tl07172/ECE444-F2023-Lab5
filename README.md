# ECE444-F2023-Lab5
Lab5-TDD (See the section at the end for Pros & Cons)

## First Test
![First_Test_passed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/e1d860c5-02e7-4d58-a7e4-3a9e3453869e)

## Database Setup 
![Database_test_passed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/6088a2a6-06cc-417e-8643-dc1cab27caa3)

## Templates and Views 
### Failed
![Template_failed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/730496f6-6f6e-4a0d-b46d-3e4885ba1c54)

### Error
![Template_error](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/e1bf9fde-9c2e-4478-a869-527c1660b939)

### Passed
![Template_passed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/1069b400-8790-4bbe-8e86-bc2ba3db993f)

## Javascript
![Javascript_passed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/9b6eae43-0670-44d0-8459-c6d9d3e81c88)

## Bootstrap
![Bootstrap](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/1d33417e-ffa0-4624-b0c6-569f5db9e30b)

## SQLAlchemy
![SQLAlchemy_passed](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/99353306-e106-4288-a9a2-2de48919dfd1)

## Webpage screenshot
![Web](https://github.com/tl07172/ECE444-F2023-Lab5/assets/84355002/b33ccf82-0a25-4c7b-afae-5c6c867fd803)

# Pros & Cons of TDD
## Pros:
**Better structure and more maintainable code**: TDD encourages developers to have a clear picture of the code structure before implementation, and allows them to write easily maintainable code with a modular design.

**Easier debugging:** Since unit tests are designed in a modular fashion before the actual code implementation, it is much easier and faster to track down the error and bug when facing issues with each test module. Different developers will be able to better collaborate with each other to debug the problem.

**Better collaboration:** The modular design of TDD makes the collaboration between developers much easier and faster, since they can easily understand a specific chunk of code from other developer rahter than reading through hundreds lines of codes.

## Cons:
**Slower implementation process:** Since TDD starts with test implementation, it will make the initial process slower since the developers need to understand the functionality first and start creating tests for each functionality.

**Test suite Maintenance:** With more functionalities being modified and implemented, the size of the test suite will grow accordingly. Eventually the test suite can be really large and hard to maintain.

**Complicated set up process:** Setting up the testing environment could also slow down the developing process, especially when the project itself is complicated.
