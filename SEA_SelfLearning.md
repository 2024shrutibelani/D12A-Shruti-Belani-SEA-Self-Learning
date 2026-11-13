# Software Engineering and Architecture – Self Learning Activities

**Name:** Shruti Belani  
**Department:** Computer Engineering  
**Subject:** Software Engineering and Architecture  
**Activity:** Self Learning Activities

---

# 1. Comparison of Agile and DevOps

## Introduction

Agile and DevOps are two important approaches used in software development. Both focus on improving software quality, teamwork, and faster delivery.

**Agile:** Agile is a software development methodology in which a project is divided into small parts called iterations or sprints. It allows teams to make changes based on customer feedback.

**DevOps:** DevOps is a combination of Development and Operations. It focuses on improving collaboration between development and operations teams to build, test, and deliver software efficiently.

## Agile vs DevOps

| Parameter | Agile | DevOps |
|---|---|---|
| Meaning | Software development methodology | Development and operations approach |
| Main Focus | Developing software in small iterations | Continuous development and delivery |
| Goal | Customer satisfaction | Faster and reliable software delivery |
| Team | Developers and testers | Developers and operations teams |
| Approach | Iterative development | Continuous integration and delivery |
| Feedback | Feedback after every sprint | Continuous feedback and monitoring |
| Testing | Testing during development | Automated and continuous testing |
| Deployment | Usually after completing iterations | Frequent and automated deployment |
| Tools | Jira, Trello, Asana | Jenkins, Docker, Kubernetes |
| Communication | Regular team meetings | Continuous collaboration |
| Changes | Changes can be made during sprints | Changes are delivered continuously |
| Example | Developing an application feature by feature | Automatically testing and deploying application updates |

## Advantages of Agile
- Improves customer satisfaction.
- Allows flexibility in development.
- Helps identify problems early.
- Encourages teamwork.

## Advantages of DevOps
- Faster software delivery.
- Reduces manual work through automation.
- Improves software reliability.
- Improves communication between teams.

## How Agile and DevOps Work Together

Agile helps teams plan and develop software in small iterations, while DevOps helps them test, deploy, and monitor the software continuously.

**Example:** A team develops an online shopping application using Agile sprints. DevOps tools are then used to test and deploy its updates.

## Conclusion

Agile and DevOps are different but complementary approaches. Agile focuses on software development, whereas DevOps focuses on the complete delivery process.

**References:**
- https://aws.amazon.com/devops/what-is-devops/
- https://www.atlassian.com/agile

---

# 2. Case Study of JIRA and Asana in Real Projects

## Introduction

Jira and Asana are popular project management tools. They help teams plan tasks, track progress, assign responsibilities, and complete projects on time.

## Case Study 1: JIRA

**JIRA** is a project management tool developed by Atlassian. It is commonly used by software development teams to manage tasks, bugs, and development activities.

### Features of JIRA
- Sprint planning.
- Bug tracking.
- Task assignment.
- Scrum and Kanban boards.
- Progress tracking.
- Reports and dashboards.

### Real Project Example

Consider a team developing an online banking application.

The team uses JIRA to:
1. Create tasks for login, registration, and money transfer.
2. Assign tasks to different developers.
3. Track bugs reported during testing.
4. Organize work into sprints.
5. Monitor project progress.

**Result:** JIRA helps the development team organize work and track software development activities.

## Case Study 2: Asana

**Asana** is a project management tool used to organize and manage team activities. It helps teams assign tasks, set deadlines, and track project progress.

### Features of Asana
- Task management.
- Project timelines.
- Task deadlines.
- Team collaboration.
- Progress tracking.
- Project dashboards.

### Real Project Example

Consider a company launching a new mobile application.

The marketing team uses Asana to:
1. Create tasks for social media promotion.
2. Assign poster and advertisement work to team members.
3. Set deadlines for each activity.
4. Track the progress of promotional campaigns.
5. Coordinate work between different departments.

**Result:** Asana helps the team manage activities and complete the product launch on time.

## JIRA vs Asana

| Parameter | JIRA | Asana |
|---|---|---|
| Main Purpose | Software development management | General project management |
| Best For | Developers and technical teams | Marketing and business teams |
| Task Management | Yes | Yes |
| Bug Tracking | Advanced support | Not its main focus |
| Sprint Planning | Yes | Limited compared to JIRA |
| Collaboration | Yes | Yes |
| Reporting | Development-focused reports | Project progress reports |
| Common Use | Software projects | Business and team projects |

## Conclusion

JIRA is more suitable for software development projects, while Asana is useful for managing general team activities. Both tools improve organization, collaboration, and productivity.

**References:**
- https://www.atlassian.com/software/jira
- https://asana.com/

---

# 3. Writing Effective User Stories and Acceptance Criteria

## Introduction

User stories and acceptance criteria are important parts of Agile software development. They help developers understand what users need from a software application.

## What is a User Story?

A user story is a simple description of a feature from the user's point of view.

It explains:
- Who needs the feature?
- What does the user want?
- Why does the user need it?

### Standard Format

**As a [type of user], I want [some feature], so that [benefit].**

### Example

As a customer, I want to log in using my email and password so that I can access my account securely.

## What are Acceptance Criteria?

Acceptance criteria are conditions that a feature must satisfy to be considered complete.

### Example: Login Feature

- The user should be able to enter an email address.
- The user should be able to enter a password.
- The system should verify the login details.
- If the details are incorrect, an error message should appear.
- If the details are correct, the user should reach the home page.

## Difference Between User Stories and Acceptance Criteria

| Parameter | User Stories | Acceptance Criteria |
|---|---|---|
| Meaning | Describes user requirements | Defines conditions for completion |
| Purpose | Explains what the user wants | Explains how success is checked |
| Focus | User needs | Expected behaviour |
| Format | Simple sentence | List of conditions |
| Example | User wants to log in | System must verify login details |

## INVEST Principle

A good user story should follow the INVEST principle:

- **I – Independent:** Stories should be independent.
- **N – Negotiable:** Details can be discussed.
- **V – Valuable:** It should provide value to users.
- **E – Estimable:** Work should be easy to estimate.
- **S – Small:** It should be small enough to complete.
- **T – Testable:** It should be possible to test it.

## Given-When-Then Format

Acceptance criteria can also be written using the Given-When-Then format.

**Example:**

- Given: The user has a registered account.
- When: The user enters correct login details.
- Then: The system allows the user to access the account.

## Benefits
- Helps developers understand requirements.
- Reduces confusion.
- Improves communication.
- Makes testing easier.
- Ensures customer expectations are met.

## Conclusion

User stories explain what users need, while acceptance criteria define how to verify that the requirements are fulfilled. Both help teams develop software according to user expectations.

**References:**
- https://www.atlassian.com/agile/project-management/user-stories
- https://www.atlassian.com/agile/project-management/acceptance-criteria

---

# 4. Advanced Requirement Elicitation Techniques

## Introduction

Requirement elicitation is the process of collecting information about what users and stakeholders expect from a software system.

It helps developers understand the actual needs of users before starting development.

Two advanced requirement elicitation techniques are interviews and ethnography.

## 1. Interviews

An interview is a technique in which the analyst asks questions directly to stakeholders to understand their requirements.

### Types of Interviews

**Structured Interview:** A fixed set of questions is prepared in advance.

**Unstructured Interview:** Questions are asked freely based on the discussion.

**Semi-Structured Interview:** It includes prepared questions along with additional questions when required.

### Steps in Conducting Interviews
1. Identify the stakeholders.
2. Prepare relevant questions.
3. Conduct the interview.
4. Record the responses.
5. Analyze the collected information.
6. Prepare the requirement document.

### Advantages
- Provides direct information.
- Helps understand user expectations.
- Allows doubts to be clarified.
- Encourages communication.

### Limitations
- Can take a lot of time.
- Responses may be incomplete.
- Different stakeholders may have different opinions.

## 2. Ethnography

Ethnography is a requirement elicitation technique in which the analyst observes users while they perform their normal activities.

It helps understand how users actually work in their environment.

### Steps in Ethnography
1. Select the users to observe.
2. Understand their working environment.
3. Observe their daily activities.
4. Record problems and difficulties.
5. Analyze the observations.
6. Identify software requirements.

### Advantages
- Provides real-world information.
- Helps identify hidden requirements.
- Shows actual user behaviour.
- Helps understand practical problems.

### Limitations
- Requires more time.
- Users may behave differently when observed.
- Not suitable for every situation.

## Interviews vs Ethnography

| Parameter | Interviews | Ethnography |
|---|---|---|
| Meaning | Asking questions to stakeholders | Observing users in their environment |
| Method | Direct conversation | Observation |
| Information | User opinions and expectations | Actual user behaviour |
| Time | Usually less time | Usually more time |
| Interaction | Direct interaction | Mostly observation |
| Example | Asking students about a college app | Observing students using the college system |

## Example: College Management System

Suppose we are developing a college management system.

- Using interviews, we ask students and teachers about attendance, timetable, and result requirements.
- Using ethnography, we observe how teachers currently record attendance and how students check their academic information.

Both techniques help us understand the requirements more accurately.

## Conclusion

Interviews and ethnography are useful techniques for gathering software requirements. Interviews help understand what users say they need, while ethnography helps understand what users actually do.

**References:**
- https://www.geeksforgeeks.org/software-engineering/requirements-elicitation/
- https://www.atlassian.com/agile

---

# 5. Requirement Traceability Matrix (RTM)

## Introduction

A Requirement Traceability Matrix (RTM) is a document used in software engineering to track requirements throughout the software development life cycle.

It connects each requirement with its design, development, and testing activities.

The main purpose of RTM is to ensure that all requirements are implemented and tested properly.

## Objectives of RTM

- Ensures that all requirements are covered.
- Helps track project progress.
- Identifies missing requirements.
- Improves software quality.
- Helps manage changes in requirements.
- Connects requirements with test cases.

## Types of Traceability

**1. Forward Traceability:** Tracks requirements towards design, development, and testing.

**2. Backward Traceability:** Checks whether every developed feature is connected to an original requirement.

**3. Bidirectional Traceability:** Tracks requirements in both forward and backward directions.

## Structure of RTM

An RTM generally contains:

- Requirement ID
- Requirement Description
- Design Reference
- Development Module
- Test Case ID
- Testing Status

## Example: RTM for an Online Shopping Application

| Requirement ID | Requirement | Module | Test Case ID | Status |
|---|---|---|---|---|
| REQ01 | User Registration | Registration | TC01 | Passed |
| REQ02 | User Login | Login | TC02 | Passed |
| REQ03 | Search Products | Product Search | TC03 | Passed |
| REQ04 | Add Products to Cart | Shopping Cart | TC04 | Pending |
| REQ05 | Online Payment | Payment | TC05 | Pending |

*Note: The above is an illustrative example of a Requirement Traceability Matrix.*

## Steps to Prepare RTM

1. Collect all project requirements.
2. Assign a unique ID to each requirement.
3. Prepare a traceability matrix.
4. Connect requirements with design and development modules.
5. Link requirements with test cases.
6. Update the testing status.
7. Review the matrix regularly.

## Advantages
- Ensures complete requirement coverage.
- Helps identify missing test cases.
- Makes project tracking easier.
- Supports requirement changes.
- Improves software quality.

## Limitations
- Requires regular maintenance.
- Can become complex in large projects.
- Needs proper documentation.

## Tools Used for RTM

- Microsoft Excel
- JIRA
- IBM DOORS
- Azure DevOps

## Conclusion

RTM is an important software engineering document that connects requirements with development and testing. It ensures that the final software meets the expected requirements.

**References:**
- https://www.geeksforgeeks.org/software-engineering/requirement-traceability-matrix/
- https://www.ibm.com/products/requirements-management

---

# 6. Tools for Requirement Management

## Introduction

Requirement management is the process of collecting, documenting, organizing, tracking, and managing software requirements throughout a project.

Requirement management tools help teams handle requirements efficiently and maintain communication between stakeholders.

## 1. IBM DOORS

IBM DOORS is a requirement management tool used to manage and track requirements in complex projects.

### Features
- Requirement documentation.
- Requirement traceability.
- Change management.
- Requirement tracking.
- Supports large projects.

**Example:** It can be used in automobile or aerospace projects where requirements need to be carefully tracked.

## 2. JIRA

JIRA is a project management tool developed by Atlassian. It helps teams manage requirements, tasks, bugs, and project activities.

### Features
- Task management.
- Issue tracking.
- Sprint planning.
- Progress monitoring.
- Team collaboration.

**Example:** A software development team uses JIRA to manage features and track bugs in a mobile application.

## 3. Azure DevOps

Azure DevOps is a Microsoft platform that supports software development and project management.

### Features
- Work item tracking.
- Requirement management.
- Version control.
- Continuous integration and delivery.
- Testing support.

**Example:** A development team uses Azure DevOps to manage requirements and track development progress.

## 4. Jama Connect

Jama Connect is a requirement management platform used for managing complex projects and maintaining traceability.

### Features
- Requirement management.
- Requirement traceability.
- Review and approval.
- Collaboration.
- Change tracking.

**Example:** It can be used in medical device development to manage and review product requirements.

## 5. Helix ALM

Helix ALM is a tool used to manage requirements, tests, and issues in software development projects.

### Features
- Requirement tracking.
- Test management.
- Issue tracking.
- Traceability.
- Project collaboration.

**Example:** A software team uses Helix ALM to connect requirements with test cases and track issues.

## Comparison of Requirement Management Tools

| Tool | Main Purpose | Important Features | Suitable For |
|---|---|---|---|
| IBM DOORS | Requirement management | Traceability and change management | Complex projects |
| JIRA | Project and task management | Sprint planning and issue tracking | Software teams |
| Azure DevOps | Development management | Work tracking and testing | Development teams |
| Jama Connect | Requirement management | Reviews and traceability | Complex and regulated projects |
| Helix ALM | Application lifecycle management | Requirements, testing, and issues | Software projects |

## Benefits of Requirement Management Tools

- Organize requirements in one place.
- Improve team collaboration.
- Track requirement changes.
- Reduce communication gaps.
- Maintain requirement traceability.
- Improve project management.

## Challenges
- Some tools require training.
- Advanced tools may be expensive.
- Maintaining requirements requires regular updates.
- Choosing the correct tool can be difficult.

## Conclusion

Requirement management tools help teams organize, track, and maintain software requirements. Tools like IBM DOORS, JIRA, Azure DevOps, Jama Connect, and Helix ALM make requirement management more effective.

**References:**
- https://www.ibm.com/products/requirements-management
- https://www.atlassian.com/software/jira
- https://azure.microsoft.com/en-us/products/devops
- https://www.jamasoftware.com/
- https://www.perforce.com/products/helix-alm

---

# Overall Conclusion

All six activities helped me understand important concepts of Software Engineering and Architecture. I learned about Agile and DevOps, project management tools, user stories, requirement elicitation techniques, requirement traceability, and requirement management tools.

These concepts are useful for understanding how software projects are planned, developed, tested, and maintained successfully.
