---
name: User Story
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

---
name: User Story
about: Create a user story for the IBM Full-Stack Developer Final Project
title: "[USER STORY]"
labels: ["user-story"]
assignees: []
---

**As a** learner enrolled in the IBM Full-Stack Developer Professional Certificate  
**I need** to build and integrate full-stack features using modern technologies  
**So that** I can demonstrate my end-to-end development skills in the final project  

---

### Details and Assumptions
* The learner has completed all prerequisite courses in the IBM Full-Stack Developer Professional Certificate
* The project follows Agile principles and uses GitHub for version control
* The application uses:
  * HTML, CSS, JavaScript, React for the front end
  * Node.js and Express for backend services
  * MongoDB as the NoSQL database
  * Microservices and REST APIs
  * Docker, Kubernetes, and OpenShift for containerization
  * GitHub Actions for CI/CD
* Development is organized by modules defined in the course syllabus

---

### Acceptance Criteria
```gherkin
Given the project repository is properly set up on GitHub  
When the learner implements features according to the module requirements  
Then the application should function as a complete full-stack system  

Given the backend APIs are implemented using Node.js and Express  
When the frontend consumes these APIs  
Then data should be displayed correctly and securely  

Given CI/CD pipelines are configured using GitHub Actions  
When code is pushed to the repository  
Then automated build, test, and deployment steps should run successfully
