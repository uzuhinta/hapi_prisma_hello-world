# The online grading system

## Model

- User: a person with an account. A user can be either a teacher or a student throught their relation to a course. In other words, the same user who's a teacher of one course can be a student in another course.

- Course: a learning course with one or more teachers and students as well as one or more test.

- Test: a course can have many tests to evaluate the students' comprehension. Tests have a date and are related to a course.

- Test result: each test can have multiple test result records per student. Additionally, a TestResult is also related to the teacher who graded the test.

m-n:
- A single course can have many associated users (as students or teacher).
- A single user can be associated with many courses.