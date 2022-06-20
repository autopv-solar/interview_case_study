## Interview case study

The code contained in `main.py` is written as a procedural script.  We want to send an email to all customers in our database (`customers.csv`) informing them of the discounts the are eligible for in the upcoming month.

The business rules are as follows:
1. On your birthday you get 10% discount
2. If you are a pensioner (older than 62) you get 15% discount
3. You get maximum of birthday and pensioner discount

The task is to re-factor this code using OOA/D methodologies and will be evaluated against best practices of Object Oriented Design, Unit testing and Version control respectively.

### Object Oriented design
The use of OOA/D principles will be reviewed with the following outcomes in mind:
1. Design should reflect sensible use of OO principles including Inheritance, Polymorphism and Encapsulation where/if applicable.
2. Use of any common design patterns where/if applicable
3. Appropriate use of comments where/if applicable
4. Implementation of SOLID principles
5. Readability and maintainability of code including attention to naming conventions, repetition of code segments, use of methods, attributes etc
6. General impression of quality of code.

### Unit testing
The candidate should implement at least two unit tests testing different aspects of the code.  Any test framework can be used but `pytest` is preferred.

These tests will be evaluated according to the following criteria:
1. Applicability of tests (ie it is a sensible tests)
2. Structure of test code

### Version control
It is expected of the candidate to fork this repo and proceed to refactor the code to achieve the above outcomes.  On completion, the candidate should make the forked repo available.  In addition to the above, the candidate's use of `git`  will be evaluated against the following criteria:
1. Usage of branching where/if applicable
2. Size of code commits
3. Quality of commit messages.