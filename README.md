# CIO_MVPDemo
Android simple MVP demo with 100% Mockito test coverage

1. What the Model View Presenter (MVP) Pattern is
2. How a view interface is used to decouple the presenter from the UI Framework
3. How the In memory user repository works in relation to the user repository (Repository Pattern)
4. How to build a UserView interface and implement it on a Fragment, making the fragment the “V” in the MVP
5. Build a Presenter (the “P” in MVP) based off a contract (interface)
6. How to implement the interface in an implementation
7. How to to rely on the UserView (the view) and UserRepository (repository pattern) abstractions (interfaces) instead of their concrete implementations
8. How to have the presenter control all UI logic such as obtaining state, setting state, and UI messaging.
9. How to inject the presenter interface through Dagger into the View (the fragment).
10. How to wire up the presenter and the view together with the userPresenter#setView call.
11. How the presenter takes over all orchestration during execution of the application with a live walkthrough of the running application code.
12. How to write insanely fast unit tests within Android Studio with jUnit 4 and Mockito
13. How to create mock objects with mockito
14. How to create a simple mock interaction behavior
15. How to completely decouple your presenter for test with no dependencies on Android, internet, databases and the like through mock objects and interfaces
16. How to mock the repository layer
17. How to mock the view layer
18. What the @Before annotation in jUnit 4 is for and how it works
19. How to use the mockito ‘when’ method to return values for given mock interactions
20. How to use the ‘verify’ method to verify interactions on a mock
21. How to use the ‘times(…)’ and ‘never’ method to verify that mock methods were (or were not) interacted with during the execution of the test
22. How to use the built in Android Studio Code Coverage Tools
23. How to expect exceptions to be thrown during the execution of a test
24. How to use the built in Android Studio Code Coverage Tools
25. How to get to 100% Code Coverage
26. How and why the verify call needs a time(n) value when methods are called multiple times
27. How field variables in a test can be used as a pass through to verify presenter actions on the model
