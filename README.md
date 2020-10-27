# ECE444-F2020-Lab6

This repo is a copy of: https://github.com/mjhea0/flaskr-tdd

### What are the pros and cons of TDD?

Pros
- TDD forces your code to be more modular since you are writing small test cases at a time.
- Encourages good architecture because you need to write unit tests before writing code. Writing unit tests can unveil architectural problems early on in the design process.
- Provides a safety net by allowing designers to know which parts of the code work. Enables easier refactoring of code and testing to see if they still work.
- Provides documentation that does not become outdated because it runs frequently.
- Team members can modify other members' code and have the ability to run the unit tests to ensure they did not break functioning code.
- Helps programmers better understand their code.
- Helps programmers establish concretely what inputs they need and what outputs to expect.
- Streamlines maintenance

Cons
- Tests may be difficult to write.
- Slows down development initially.
- The entire team needs to consistently create and use unit tests for TDD to work properly.
- Sometimes unit tests might require you to mock complex functionality not yet implemented.
- Can fall into the trap of spending too much time and effort on unit tests. Unit tests should be simple.
- Difficult to incorporate unit tests into existing legacy code.
