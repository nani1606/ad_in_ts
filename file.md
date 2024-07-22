# Software Team Procedure

## Inputs
- **Funding:** Secured budget for the project.
- **High-level milestones:** Defined project milestones.
- **Staffing:** Assigned team members.

## Procedure

### 1. Planning the Project Backlog
1.1. **Gather Requirements:**
   - Engage stakeholders to collect detailed project requirements.
   - Document requirements in a shared repository (e.g., Confluence, Google Drive).

1.2. **Define User Stories:**
   - Break down requirements into user stories.
   - Ensure each user story follows the INVEST criteria (Independent, Negotiable, Valuable, Estimable, Small, Testable).

1.3. **Prioritize Backlog:**
   - Prioritize user stories based on stakeholder input and project milestones.
   - Use a tool like Jira or Trello to organize and manage the backlog.

### 2. Executing the Project Backlog Using Agile Methodology
2.1. **Sprint Planning:**
   - Hold a sprint planning meeting at the start of each sprint (bi-weekly).
   - Select user stories for the sprint based on team capacity and priority.
   - Assign tasks to team members.

2.2. **Daily Stand-ups:**
   - Conduct daily stand-up meetings (15 minutes).
   - Each team member answers three questions: What did I do yesterday? What will I do today? Are there any blockers?

2.3. **Sprint Review and Retrospective:**
   - At the end of each sprint, hold a sprint review to demo completed work.
   - Conduct a retrospective to discuss what went well, what didn't, and how to improve.

### 3. Archiving Design Documentation
3.1. **Documentation Creation:**
   - Document design decisions, architecture, and significant changes.
   - Use tools like Confluence, Google Docs, or Markdown files stored in a version control system.

3.2. **Archiving:**
   - Store documents in a centralized, accessible repository (e.g., Confluence, SharePoint).
   - Archive documents immediately after they are finalized.
   - Maintain archives for a minimum of 5 years.

### 4. Performing Design Reviews Before Implementation of Stories
4.1. **Review Team:**
   - Design reviews must involve at least 3 team members, including one senior developer or architect.
   - Review should ensure that designs align with project requirements and standards.

4.2. **Review Process:**
   - Schedule review meetings as needed before starting implementation.
   - Use a checklist to ensure all design aspects are covered.

### 5. Performing Code Reviews Before Code is Merged to the Mainline
5.1. **Review Team:**
   - Code reviews must be conducted by at least 2 peers, excluding the author.
   - At least one reviewer should be familiar with the part of the codebase being modified.

5.2. **Review Process:**
   - Use a pull request system (e.g., GitHub, GitLab).
   - Review for code quality, adherence to coding standards, and correctness.
   - Ensure all comments and concerns are addressed before merging.

### 6. Archiving and Performing a Test Plan to Ensure High Code Quality
6.1. **Test Plan Development:**
   - Develop a comprehensive test plan covering unit tests, integration tests, and system tests.
   - Use tools like TestRail, JIRA, or Google Sheets to document the test plan.

6.2. **Executing Tests:**
   - Execute tests as part of the CI/CD pipeline using tools like Jenkins, GitLab CI, or GitHub Actions.
   - Log test results and address any failures immediately.

6.3. **Archiving Test Results:**
   - Store test results in a centralized, accessible repository.
   - Archive test plans and results immediately after tests are completed.
   - Maintain archives for a minimum of 5 years.

## Outputs
- **Finished Software:** Delivered and deployed according to project milestones.
- **Test Plan:** Documented and archived for future reference.
- **Design Documentation:** Archived and accessible for reference and future projects.
