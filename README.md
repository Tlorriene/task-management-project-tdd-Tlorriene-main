# Task Management Project

[![JavaScript Language](https://img.shields.io/badge/language-JavaScript-F7DF1E.svg?logo=JavaScript)][1]
[![Jest Testing Framework](https://img.shields.io/badge/testing%20framework-Jest-339933.svg?logo=Jest)][2]
[![Node Package Manager](https://img.shields.io/badge/package%20manager-Node-C21325.svg?logo=NPM)][3]

[Replace with your Netlify Badge]<br/>
[Replace with a link to your **published** application on Netlify e.g. https://example-task-manager.netlify.app]

The purpose of this project is to build a simple JavaScript application to manage tasks, following a **test-driven development** approach. 

We want to ensure that the emphasis is on practicing all the test-driven development concepts covered by the course. Therefore, in building this simple application, we will focus on **happy path scenarios** to begin with.

When you have completed the requirements below, please feel free to add tests for **unhappy path scenarios**.

## Session Task 
Below is a list of empty user stories. Discuss and understand the project requirements, then [add your BDD user stories below](#user-stories-and-scenarios).

## How to Complete your Homework

Homework will be to build the application using TDD. Please refer to the [Getting Started Guide][10] to start working on the project.

🚨 **To complete this homework:**
1. Publish your application to (Netlify)[11].
1. Add the Netlify Status Badge for your application to the top of this README.md 
1. Add a link to your **published** application on Netlify to the top of this README.md 

## Requirements

- [Display tasks][4]
- [Create a task][5]
- [Edit a task][6]
- [Complete a task][7]
- [Delete a task][8]
- [Reorder a task][9]

### User Stories and Scenarios

## 1. Display Tasks

**Narrative:**
> **As a** user through a web browser <br/>
> **I want** to be able to display all the tasks <br/>
> **So that** I can plan and organise my day.

### **Acceptance Criteria: (Presented as scenarios below)**

**Scenario 1:** Review My Tasks
>	**Given** I would like to see my tasks <br/>
>	**When** I visit my task list <br/>
>	**Then** I should see a list of tasks

**Scenario 2: ...**

## 2. Create a Task

**Narrative:**
> **As a** user with of the task planner <br/>
> **I want** be able to add my gym sessions to my calendar <br/>
> **So that** I can see that I have a task to complete

### **Acceptance Criteria:**

**Scenario 1:** Adding gym sessions to my weekly planner  
>	**Given** That I would like to see my gym sessions on my calendar <br/>
>	**When** When I go into my planner for a Saturday <br/>
>	**Then** I should see that my plan for Saturday starts with a gym session 

## 3. Edit a task

**Narrative:**
> **As a** use who needs to edit a future task<br/>
> **I want** to be able to go into my task and make changes <br/>
> **So that** I can keep up to date correct information 

### **Acceptance Criteria:**

**Scenario 1:** Editing details on a task
>	**Given** That I want to change the time of my driving lesson <br/>
>	**When** I change the time and press save<br/>
>	**Then** I should see the updated time on the planner

## 4. Complete a task

**Narrative:**
> **As a** teacher who has completed the 'create resources' task on the planner<br/>
> **I want** to be able to make this off on my planner <br/>
> **So that** I can keep track of my tasks for the day 

### **Acceptance Criteria:**

**Scenario 1:** teacher completing taks on their to do list 
>	**Given**  That I have completed the task <br/>
>	**When** I select the tick box next to the task to select that it has been completed <br/>
>	**Then** The item should show as being completed on the list

## 5. Delete a task

**Narrative:**
> **As a** secretary for a team <br/>
> **I want** to delete a task out of the team diary<br/>
> **So that** the team is aware the meeting is cancelled 

### **Acceptance Criteria:**

**Scenario 1:** Someone checks their calendar to check the details of the meeting 
>	**Given** that the meeting has been cancelled  <br/>
>	**When** when I go into the planner and confirm the cancellation<br/>
>	**Then** the meeting should no longer be in the planner 

## 6. Reorder a task

**Narrative:**
> **As a** Driving instructor using the planner to plan in lessons <br/>
> **I want** move some lessons around <br/>
> **So that** I can re-order my lessons for the day 

### **Acceptance Criteria:**

**Scenario 1:** The driving instructor needs to check that his lessons are in the right order
>	**Given** The instructor has changed his appointments around <br/>
>	**When** he looks at his day in the planner <br/>
>	**Then** he should see the lessons he ordered them in

[1]: https://www.javascript.com/
[2]: https://nodejs.org/en/
[3]: https://jestjs.io/

[4]: #display-tasks
[5]: #create-a-task
[6]: #edit-a-task
[7]: #complete-a-task
[8]: #delete-a-task
[9]: #reorder-a-task
[10]: doc/START.md
[11]: https://app.netlify.com/