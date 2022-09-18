# Android_Testing_Example
An example repository showing how testing in done in android...

# Testing in Android
* Test cases test if our code is working or not. 
* Without tests, you need to do manual testing over and over to verify the cases. 
* With JUnit, we can test our code with a single click whenever we want.

## Types of Tests in Android 

  * UI Tests - 10% of the app
  * Integration Tests - 20% of the app
  * Unit Tests - 70% of the app

## Unit Tests 
They only tests single component in our app
E.g. There can be a function which calculates the sum of the list.
     We just have to pass the list and in return we get the sum. 

# Integration Tests
Tests how two components of our app work together
E.g. How fragments interact with viewModel

Note: Do not confuse integration tests with integrated tests because that is a big difference. 
      * Integration Tests - How to components of our app work together
      * Integrated Tests -  Tests that relies on Android Components. (therefore, must run on the emulator)
        E.g. Function that needs to access the app resources. 

## UI Tests
Tests that check if many or all components of your app work together well and if the UI looks like it should. 
E.g. If a recyclerview has a specific lists or textview has a specific text.

## How to Write Good Tests

Writing Test Driven Development 

## Test Driven Development

Main Principles: 

* Write the test cases before the implementation of actual functions (only for unit tests)
  1. Writing function signature 
  2. Write the test cases for that function 
  3. Write the function logic so the tests pass

* You should only have one assertion per test case
* We immediately want to know the case of a failed test case
* Sometimes there is no way around multiple assertions 

#What make a good test?

1. Scope - how much code is covered by our single test case. 
2. Speed - how fast our test case run. 
3. Fidelity - how close our test case is to real scenario. 
4. Avoid Flaky tests - sometimes succeeds and sometimes fails.
5. Never make the outcome of a test dependent on the outcome of another test. 

##How many test cases should you write? 
* Always write test cases as little as necessary, but also as many as necessary. 
* Equivalent classes help us to determine the amount of tests a function should have.
