# Weekly Assistant

## Product README

A Vietnamese-first project planning app that helps small teams turn an idea into a clear weekly plan, share responsibilities, and follow work through to completion—without requiring prior project management experience.

## Product overview

Weekly Assistant (Trợ lý tuần) guides a team from goal setting to weekly execution. Members describe the project, clarify its goal through a structured brainstorm, and use the resulting plan to organize milestones, tasks, deadlines, priorities, and review steps. The product is designed to make practical project management approachable for small Vietnamese teams.

## The problem

Small teams are common in Vietnam, including high school and university groups, startups, workplace teams, and people working on personal projects. Many of these teams need a clear way to set goals, divide responsibilities, track progress, and coordinate meetings, but they may not have a project manager or prior experience with project management frameworks.

Existing tools such as Notion and Trello are flexible, but teams often have to build their own workflows, templates, and task structures. This setup takes time and can feel overwhelming, especially for new users. As a result, teams may spend more time organizing the work than doing it, assign tasks verbally, lose track of deadlines, or struggle to follow up on work that needs review.

The product idea came from Phương, Nhật and Huy’s project management experience. A recurring pain point was the time spent on administrative work, such as setting up a project plan, organizing tasks, and coordinating follow-ups. The team wanted to reduce this overhead and make it easier for people without project management experience to adopt a planning tool. The product aims to reduce repetitive setup and coordination work through guided brainstorming, suggested milestones and task breakdowns, weekly planning, task tracking, and meeting coordination. Its simple, Vietnamese-friendly experience is intended to reduce the anxiety of adopting a new tool, make project management easier to learn, and encourage teams to return to a regular weekly planning and follow-up routine.

## Target users

- High school students working on group assignments or extracurricular projects
- University students, clubs, and student organizations
- Small workplace teams and startups
- Individuals managing a personal project

## Core features

- Guided brainstorming to clarify a project goal using the SMART goal model.
- Suggested milestones and a Work Breakdown Structure (WBS) generated from the goal, project context, and deadline.
- Weekly planning that organizes tasks by timing and priority.
- A team task board with five workflow states: Not Started, In Progress, Waiting for Review, Returned, and Done.
- Task assignment, submission, review, and revision to support a feedback loop.
- Meeting scheduling based on team members’ availability.
- Role-aware views for team leads, members, and observers.

## Launch and growth

The initial launch would focus on online outreach to the intended users. Short product walkthroughs, practical project-planning tips, and demonstrations can be shared through social media and student or startup communities. The team can also invite clubs, classes, and small teams to try the MVP, collect feedback, and encourage referrals between groups.

A possible revenue direction is a free plan for small teams with paid tiers for larger teams or advanced project features. This is a hypothesis to validate with users, not a confirmed business model.

## How to access and use the MVP

The walkthrough video demonstrates the MVP flow. Users sign in with an email verification code, complete the initial setup, create a project with a name and goal description, and start a brainstorm. The app then presents a project plan with milestones, tasks, and deadlines. Teams can manage weekly work on the task board, submit tasks for review, and use the meeting availability flow to coordinate a time.

## AI-native workflow

The team began by using Claude and other AI tools to explore which project management frameworks could support the product. It divided the early work across brainstorming, weekly work tracking, and framework exploration, including SMART goals and milestones. The team documented the proposed workflow in a wiki and used it to build and run the first app version.

MVP testing revealed repeated steps. The team collected feedback and revised the wiki around three user perspectives: team lead, member, and observer. It then used AI to explore ways to suggest milestones and WBS items automatically and to support multiple users logging in and interacting. After selecting an existing system design, the team used AI to rebuild the app for a second MVP iteration.

AI helped the team generate framework options and explore implementation approaches quickly. Testing also showed that AI-generated workflows needed review: the first MVP included duplicated steps, and the proposed planning and collaboration flows still needed validation with real teams.

## Team members and contributions

| Team member | Role and contributions |
|---|---|
| Nhật | Designed the weekly work features, co-authored the wiki, built the app using Claude, and analyzed MVP feedback. |
| Khang | Designed meeting-scheduling features, co-authored the wiki, and built the app using Claude. |
| Phương | Work on the brainstorming process feature, co-authored the product wiki, collect and analyze user feedback. |
| Ngân | Explored project management frameworks, co-authored the product wiki, tested the MVP and provided user feedback. |
| Huy | Co-authored the product wiki, built the app using Claude, tested the MVP and provided user feedback. |

