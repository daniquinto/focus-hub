# Personal Work OS – Habits, Tasks and Projects Platform

Personal Work OS is a web platform that centralizes personal productivity in one place by combining **tasks, habits and projects** into a single workflow-oriented system.

The goal is to build a personal “operating system” for work and study that helps users decide what to focus on every day, track consistency, and manage long-term goals.

This project is designed to be developed incrementally following a three-phase methodology defined for the course.

---

## Project Concept

The platform allows a user to:

- Organize projects and their related tasks
- Track personal habits and consistency
- Manage pending items using an inbox-first workflow
- View a unified “Today” dashboard that combines:
  - tasks due today or overdue
  - habits scheduled for today
  - next actions from active projects

The application focuses on simplicity, clarity and real productivity use cases rather than being a basic to-do list.

---

## Core Modules

- Inbox  
  A quick capture space for ideas, tasks or notes before organizing them.

- Tasks  
  Individual actionable items with priority, due date and status.

- Projects  
  High-level goals that group tasks and define next actions.

- Habits  
  Repeating behaviors with frequency and completion tracking.

- Today View  
  A unified daily dashboard that brings together all relevant information.

- Weekly Review  
  A review space for progress and unfinished work.

---

## Incremental Development Methodology

The project will be developed using three structured phases.

---

## Phase 1 – Structure, Base Layout and AI Requirements

Focus:
- No application logic
- No database
- No real interactivity

Main objective:
Create the visual structure of the platform and define the functional and AI-related requirements.

Deliverables:

- Project folder structure
- Static HTML pages for:
  - Inbox
  - Today
  - Projects
  - Habits
  - Review
- Common layout with:
  - sidebar navigation
  - header with search and quick add button
  - main content area
- Reusable UI elements:
  - task cards
  - habit cards
  - project cards
- Base styling using CSS
- Documentation files describing:
  - system scope
  - user stories
  - business rules
  - future AI behavior

At this stage, all data is static and only used for visual representation.

---

## Phase 2 – JavaScript Logic and Interactivity

Focus:
- Client-side logic
- State management
- Dynamic rendering

Main objective:
Transform the static interface into an interactive application using JavaScript.

Main features to implement:

- Create, edit and delete tasks
- Mark tasks and habits as completed
- Filter and visualize tasks in the Today view
- Associate tasks with projects
- Store and manipulate data in memory or local storage
- Basic form validation
- UI state updates without page reloads

No React and no database are used in this phase.

---

## Phase 3 – React, Firebase and Deployment

Focus:
- Component-based architecture
- Cloud database
- Authentication
- Deployment

Main objective:
Rebuild the application using modern frontend and backend tools.

Planned technologies:

- React for UI componentization
- Firebase for:
  - authentication
  - real-time database
  - hosting

Main features:

- User authentication
- Persistent storage of:
  - tasks
  - projects
  - habits
  - completion history
- Real-time synchronization
- Modular React components
- Production-ready deployment

---

## Functional Scope (MVP)

The minimum viable product includes:

- Project management
  - create and update projects
  - assign tasks to projects

- Task management
  - create, edit and delete tasks
  - due date and priority
  - mark tasks as completed

- Habit management
  - create habits
  - define simple frequency (daily or selected weekdays)
  - mark habit completion

- Today dashboard
  - tasks due today or overdue
  - habits scheduled for today
  - next actions for active projects

---

## Out of Scope for the Initial Version

The following features are planned for future iterations:

- advanced habit rules (for example: X times per week)
- notifications and reminders
- offline-first behavior
- calendar synchronization
- advanced analytics
- real AI integration

---

## Future AI Support – Functional Definition

The system is designed to support an AI assistant in later versions.

The AI will be able to answer questions such as:

- What should I prioritize today?
- Which habits are failing this week?
- Summarize my progress on a specific project
- Suggest next actions for a project

The AI will use the following data:

- tasks (status, priority, due dates, project, tags)
- habits (frequency and completion history)
- projects (status, description and next actions)
- activity logs

No AI implementation is required during the current development phases. Only the specification is defined.

---

## Educational Objectives

This project is designed to strengthen skills in:

- web layout and UI structure
- JavaScript application logic
- data modeling and relationships
- frontend architecture with React
- cloud services integration
- real-world product thinking

---

## Summary

Personal Work OS is a productivity platform that centralizes tasks, habits and projects into a single system.  
It follows a clear incremental development strategy that allows the application to grow from static design to a complete full-stack solution.