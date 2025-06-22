# CS320-8-2-Journal-Portfolio-Item
<body>
  <h2>7-2 Project Two Submission</h2>

  <h3>How can I ensure that my code, program, or software is functional and secure?</h3>
  <p>
    To ensure my code is both functional and secure, I prioritize comprehensive unit testing using frameworks like JUnit.
    In this project, I implemented tests for each core feature—<strong>Appointment</strong>, <strong>Task</strong>, and <strong>Contact</strong>—to validate
    not only expected use cases but also edge cases and invalid input scenarios. I enforced constraints like unique IDs,
    maximum character lengths, and format validation through constructor logic and service classes. I used assertions such as
    <code>assertThrows</code> to verify that invalid inputs were properly rejected, helping to guard against common security pitfalls like null
    references and format violations.
  </p>

  <h3>How do I interpret user needs and incorporate them into a program?</h3>
  <p>
    I interpret user needs by aligning my code with documented software requirements and translating them into specific
    validations and test cases. For example, if a requirement specifies that phone numbers must be exactly 10 digits,
    I ensure this is enforced both in code and in unit tests. I take on the user's perspective by anticipating
    misuse—such as duplicate IDs or inputs that exceed character limits—and use these insights to harden the system
    against real-world input.
  </p>

  <h3>How do I approach designing software?</h3>
  <p>
    My software design approach begins with modular development: separating concerns into distinct classes and service layers.
    Each service handles the core logic for its associated feature. I then use Test-Driven Development (TDD) principles
    to build around unit tests, validating each feature’s logic independently before integration. For this project, I focused
    on clarity, using descriptive method names, organizing test files around functionality, and documenting each test case
    for maintainability. In future projects, I plan to incorporate tools like JaCoCo for code coverage and SonarQube for
    static analysis to further enhance code quality.
  </p>

  <h2>Conclusion</h2>
  <p>
    This project strengthened my understanding of writing reliable and maintainable code. By thoroughly testing each method
    under both valid and invalid conditions, I improved my ability to develop software that not only meets requirements but
    also withstands misuse. These practices—modular design, defensive programming, and rigorous testing—will remain core
    components of my development methodology.
  </p>
</body>
