<!-- Used to provide workspace specific instructions to GitHub Copilot. See https://docs.github.com/en/copilot/getting-started-with-github-copilot/about-github-copilot-instructions -->

# Tacit - A Method for maintaining an AI Assisted Notebook

This workspace is a collection of notes, ideas, and thoughts that I maintain with the help of GitHub Copilot. The goal is to use Copilot to help me maintain my notes, and to help me think through problems and ideas.

## General Instructions

- When responding, keep answers concise and succinct, avoiding unnecessary verbosity and pleasantries. Avoid 'corporate speak' and 'AI speak'. Focus on providing clear, actionable information.
- For image insertions, suggest saving images in a local `images/` directory and referencing them with relative paths.
- For documents, suggest saving them in a `documents/` directory and referencing them with relative paths.
- When working on larger scripts or code snippets, suggest saving them in a `scripts/` directory and referencing them with relative paths.
- Help with markdown formatting, including headings, lists, tables, and links.
- Help with creating links between notes, using relative paths.
- When working with agile methodologies, suggest using a `agile/` directory to organize project notes and tasks.
- When working with agile documents, conform to SAFe agile best practices.

## Organization Context

<!-- Provide context about your organization, team, or project here. This helps Copilot understand the environment and provide more relevant suggestions. -->

### Delivery Teams

#### Team Alpha
- Focus: Backend services and API development.
- Key Technologies: Python, Django, PostgreSQL.
- Team Members: Alice (Lead), Bob, Charlie.
- Current Projects: User authentication service, Payment processing API.

#### Team Beta
- Focus: Frontend development and user experience.
- Key Technologies: React, TypeScript, CSS.
- Team Members: Dave (Lead), Eve, Frank.
- Current Projects: Customer dashboard, Mobile app interface.

## Recurring Meetings

<!-- Provide context about recurring meetings, their purpose, and any relevant details here. This helps Copilot understand the environment and provide more relevant suggestions. -->

| Meeting Name       | Frequency | Day       | Time.         | Purpose                                      | Notes
| ------------------ | --------- | --------- | ------------- | -------------------------------------------- | ---------
| Daily Standup      | Daily     | Weekdays  | 11:00 - 11:30 | Quick status updates and blockers            | Keep it brief, focus on what was done yesterday, what will be done today, and any blockers.
| Sprint Planning    | Bi-Weekly | Mondays   | 10:00 - 11:30 | Plan the work for the upcoming sprint        | Review backlog, prioritize tasks, and assign work.
| Sprint Review      | Bi-Weekly | Fridays   | 15:00 - 16:00 | Review completed work and gather feedback    | Demonstrate completed work, gather feedback from stakeholders.
| Retrospective      | Bi-Weekly | Fridays   | 16:00 - 17:00 | Reflect on the sprint and identify improvements | Discuss what went well, what didn't go well, and action items for improvement.
| 1:1 Meetings       | Weekly    | Varies    | Varies        | Individual check-ins with team members       | Focus on personal development, feedback, and any concerns.

## Key Projects

<!-- Provide context about key projects, their goals, and any relevant details here. This helps Copilot understand the environment and provide more relevant suggestions. -->

## Key Systems

<!-- Provide context about key systems, technologies, and tools used in your organization here. This helps Copilot understand the environment and provide more relevant suggestions. -->

### Environments

| Environment Name  | Purpose                                     | Technologies/Tools Used                    | Notes
| ----------------- | ------------------------------------------- | ------------------------------------------ | ----------------------------------------------
| Development (DEV) | For development and testing of new features | Git, Docker, Kubernetes, Jenkins           | Frequent deployments, may be unstable.
| Staging (STG)     | For pre-production testing and validation   | Same as production, plus monitoring tools  | Mirrors production environment, used for final testing. 
| Production (PRD)  | Live environment for end-users              | AWS, Azure, GCP, Databases, Load Balancers | High availability, monitored closely.

## People/Relationships

<!-- Provide context about key people, their roles, and relationships here. This helps Copilot understand the environment and provide more relevant suggestions. -->

| Name              | Role                | Relationship to Me                         | Notes
| ----------------- | ------------------- | ------------------------------------------ | ----------------------------------------------
| Alice Johnson     | Project Manager     | Direct Manager                             | Oversees project timelines and deliverables.
| Bob Smith         | Team Lead           | Direct Report                              | Leads the development team, responsible for technical decisions.
| Carol Martinez    | UX Designer         | Collaborator                               | Works closely on user experience and design aspects.
| David Lee         | QA Engineer         | Direct Report                              | Responsible for testing and quality assurance.
| Eve Thompson      | Product Owner       | Stakeholder                                | Defines product vision and prioritizes features.

## Agile Stuff

<!-- Provide context about your agile processes, ceremonies, and any relevant details here. This helps Copilot understand the environment and provide more relevant suggestions. -->

### PI 2025.1

| Sprint   | Start Date | End Date   | Goals
| -------- | ---------- | ---------- | ----------------------------------------------
| Sprint 1 | 2025-01-06 | 2025-01-19 | Complete initial setup and configuration.
| Sprint 2 | 2025-01-20 | 2025-02-02 | Develop core features and functionalities.
| Sprint 3 | 2025-02-03 | 2025-02-16 | Conduct testing and gather feedback.
| Sprint 4 | 2025-02-17 | 2025-03-01 | Finalize features and prepare for release.

## Form Templates

### Change Request Template
```markdown
# Change Request
**Title:** [Short description of the change]
**Date:** [Date of submission]
**Submitted by:** [Your Name]
**Description:**
[Detailed description of the change, including the reason for the change and any relevant background information.]
**Impact Analysis:**
- **Systems Affected:** [List of systems that will be affected by this change]
- **Users Affected:** [List of user groups that will be affected]
- **Estimated Downtime:** [Estimated downtime, if any]
**Implementation Plan:**
1. [Step 1]
2. [Step 2]
**Rollback Plan:**
1. [Step 1]
2. [Step 2]
```