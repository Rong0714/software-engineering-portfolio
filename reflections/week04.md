# Task 1

Sprint: One-day simulation
Sprint goal: Improve the booking management experience by providing a daily booking schedule and online payment functionality.

What’s done?
Story #9, the daily booking schedule for centre managers, has been completed in our simulation and moved to Done. Story #6, online payment, has progressed to In review and is awaiting testing.

What’s next?
We will test the online payment functionality, check that payments are handled correctly, and address any issues identified during the review. We will then consider starting the booking confirmation email story (#4), provided capacity is available.

Any blockers?
Online payment testing may depend on access to a suitable payment gateway or test environment. If this is unavailable, we will use a mock payment environment for the simulation and record the dependency as a blocker.
Overall progress: One story completed, one in review, and the sprint goal partially achieved. The next priority is to validate online payment before considering additional work.

# Task 2
Issues:
As a student, I want to view my personal weekly timetable, so that I can plan my classes and manage my time effectively.
As a student, I want to see the room and lecturer details for each class, so that I know where to go and who will be teaching me.
As a student, I want to receive a notification when a class is rescheduled or cancelled, so that I can adjust my plans accordingly.
As a student, I want to export my timetable to my phone's calendar app, so that I can view my classes alongside my other appointments.
As a lecturer, I want to mark a specific class as cancelled or relocated, so that students are informed of changes to their scheduled sessions.
As an administrator, I want to see which timetable slots are over capacity, so that I can resolve scheduling issues and ensure classes have sufficient space.

Story 1: View weekly timetable
Acceptance criteria:
Given that a student is logged in, when they open their timetable, then the system displays their classes for the current week.
Each class displays its date, start time, end time, room, and lecturer.
The student can navigate to the previous or following week.
Only classes assigned to that student are displayed.

Story 3: Receive timetable notifications
Acceptance criteria:
Given that a student's class is rescheduled, when the change is saved, then the student receives a notification showing the updated date, time, and location.
Given that a class is cancelled, when the cancellation is confirmed, then the affected students receive a cancellation notification.
Notifications identify which class has changed.
Students do not receive timetable change notifications for classes they are not enrolled in.

# Task 3

Continuous Integration is an XP practice where developers frequently merge their code into a shared codebase and run automated builds and tests to identify problems early. It helps prevent “integration hell”, where separately developed features become difficult to combine, and its main benefits are early defect detection and reduced integration effort. However, CI can be challenging to maintain because automated tests may be unreliable (flaky) or pipelines may take too long to run.

A real-world example is GitHub, which uses GitHub Actions for continuous integration. In a 2023 engineering blog post, GitHub described how its engineering teams used Actions larger runners to scale CI and run 15,000 CI jobs within an hour. Source: GitHub Engineering Blog.

In my PitchPerfect Scrum/Kanban simulation, CI would help ensure that features such as online payments and the daily booking schedule work correctly when changes are combined. Automated tests would identify defects before a story moved from In Progress to In review or Done, reducing rework and helping the team deliver features quickly without sacrificing software quality.

