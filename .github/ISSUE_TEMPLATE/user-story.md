---
name: User Story
about: This feature allows users to assign due dates to tasks, helping them manage
  time and meet deadlines efficiently.
title: ''
labels: ''
assignees: ''

---

**As a** user
**I need** to set due dates on my tasks
**So that** I can manage my time and meet deadlines

###Details and Assumptions
* [The user can select a date from a calendar widget
Tasks without due dates are still valid
Notifications are triggered based on the due date]


 ### Acceptance Criteria  

 ```gherkin

Given I have a task in my board
When I click on the task and select a due date
Then the due date should be saved and displayed on the task card

 ```
