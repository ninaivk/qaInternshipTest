The application is a set of automated tests that test the manipulation of use cases in the sendbbos application.

The application contains 5 tests:

- Test 1:
* log in to the application
* goes to the use case creation page and creates 5 use cases with passed values for input fields

- Test 2:
* log in on the page
* goes to the use case creation page and edit existing use cases

- Test 3:
* log in on the page
* goes to the use case creation page and delete existing use cases

- Test 4:
* log in to the application
* goes to the use case creation page and creates 5 use cases with passed values for input fields, add one more Step value and toggle element for Automated indicator

- Test 5:
* log in to the application
* goes to the use case creation page and deletes another value for Step after waiting deletes the modified test case

No bugs were found during testing.
The tests were done using Selenium Chrome in the NUnit Framework.
