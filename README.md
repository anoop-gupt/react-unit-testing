# ReactUnitTesting
This repository is meant to showcase various part of react unit testing with example code snippets
Web Url: https://anoop-gupt.github.io/react-unit-testing/

# Jest Test React - Testing React Apps with Jest and Enzyme (With Code Snippets)

-Types of Tests
  - Unit Testing
  - Integration Testing
  - Functional Testing
  - E2E Testing
  - Test Runner v/s Test Environment v/s Test Suite
  - Convention and Organization of tests
- React Unit Testing
- Snap Shot Testing
- What is Jest
  - Basic Concepts
  - Mocking/ Stubbing
  - Expect/ Assert
  - Matchers
- What is Enzyme
  - Shallow
  - Mount
  - Static
- Enviornment Setup
  - Installation
  - Run
  - Coverage and reporting
- How to test
  - Test Pure Components
  - Test Stateful Components
    - component.state()
  - Test Life Cycle Methods
  - Test Redux mapStateToProps and mapDispatchToProps
      - Test Actions
      - Test Reducers
      - Test Store
  - Test Custom Methods
  - Test Routes
  - Test Async/ Promises
    - <service-name>.mockImplementationOnce(() => Promise.resolve());
    - <service>.mockImplementation(() => Promise.resolve(({ key: 'value' })));
    - mock.onAny().replyOnce(200, {});
- Test Axios/Fetch
- Test Browser Object Modal - Window and Document Objects
- Test Timers
- Debug your test
- Appendix



# Types of Tests
During this stage of web application development, issues such as that of web application security, the functioning of the site, its access to handicapped as well as regular users and its ability to handle traffic is checked. Purpose is to address issues before the system is revealed to the public. 

Basically there are 6 ways to test a web application. They are
  - Unit Testing
  - Integration Testing
  - Functional Testing
  - E2E Testing
  - Test Runner v/s Test Environment v/s Test Suite
  - Convention and Organization of tests


# Unit testing
Unit test is a function that test the behaviour of small unit of functionality resulting in pass or fail. It is used to test all the possible scenarioes including edge case scenarios by mimicking the same behaviour. 

It is used consistently and can cover major part of your code. Higher no of covered test scenarios give developer confidence to refactor the code anytime without thinking about breaking any scenrio or functionality.

# Integration Testing
Integration Testing is next level of testing where individual units are combined and tested as a group. This is used to expose faults in the interaction among unit components. It occurs after unit testing.

# Functional Testing
Functional Testing is a type of black box testing where objective is to make sure that system is meeting all the functional requirements. In other words, it is a way of checking software to ensure that it has all the required functionality that is specified within its business rules ducument.

# E2E Testing
End to end testing is more about the actual flow through a system in a more realistic end user scenario. It is a technique used to examine if the flow of an application right from start to finish is behaving as expected. The purpose of performing end-to-end testing is to identify system dependencies and to ensure that the data integrity is maintained between various system components and systems.

# Test Runner v/s Test Environment v/s Test Suite
A test runner is the tool or the library that picks set of unit test cases and a set of configuration settings then executes those test cases and write the result of execution in a log file. 
Test environment is generally setup of softwares and hardware to execute test cases.
A test suite is also known as 'validation suit', it is a collection of test cases that are intended to be used to test a software program to show that it has some specified set of behaviours.

# Convention and Organization of tests

