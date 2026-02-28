# Personal Work OS – Student Edition  
Personal Work OS – Student Edition is a web platform designed specifically for **student life**.  
It centralizes **classes, assignments, study sessions, habits and personal projects** into one calm, aesthetic and highly personalized workspace.

This is not a generic to-do app.  
It’s a personal study + life operating system that helps you:
- stay on top of your subjects
- visualize your schedule in a cute way
- know exactly what to study and when
- reduce mental overload

The platform is built incrementally using a three-phase methodology defined for the course.

---

## Project Concept

The platform allows a student to:

- manage academic subjects (assignatures)
- organize assignments, exams and personal tasks by subject
- visually manage their weekly class schedule
- plan study sessions per subject
- track personal habits
- maintain personal or side projects (not only academic)
- see a soft and friendly “Today” dashboard that combines:
  - today’s classes
  - tasks and assignments due
  - planned study blocks
  - habits for the day

The core idea is:
**everything related to your student life lives in one calm, visual system.**

---

## Student-Centered Design Principles

- calm and distraction-free interface  
- cute and soft visual style (pastel, rounded cards, friendly typography)
- low cognitive load
- visual schedule instead of tables
- subject-first organization (not project-first)

---

## Core Modules

### Student Profile & Preferences
Personal settings that affect the whole system:
- career / program
- semester
- preferred study hours
- daily energy level (morning / afternoon / night)
- color theme and visual style

---

### Subjects (Assignatures)
Each subject represents a real class.

A subject contains:
- subject name
- professor (optional)
- color / icon
- weekly class schedule
- assignments
- exams
- study plan

---

### Schedule (Weekly Planner)
A visual weekly calendar used only for:
- class blocks
- planned study sessions
- exams or important academic events

The schedule is shown as:
- a soft grid with colored blocks per subject
- no productivity clutter
- only time-based activities

---

### Assignments & Academic Tasks
All academic tasks belong to a subject.

Each task includes:
- subject
- type (homework, project, exam, reading, quiz)
- due date
- estimated study time
- status

---

### Study Planner
A lightweight study planning system.

Allows the student to:
- create study sessions for a subject
- split large topics into small study blocks
- plan what to study today or this week

Study sessions are different from tasks:
they represent **learning time**, not deliverables.

---

### Personal Projects
Non-academic projects such as:
- portfolio projects
- side apps
- learning goals

Each project contains:
- description
- tasks
- next action

---

### Habits
Simple personal habits related to:
- health
- learning consistency
- routines

---

### Inbox
Quick capture for:
- ideas
- reminders
- random tasks
- things to later assign to a subject or project

---

### Today View (Student Dashboard)
A single daily view that shows:

- today’s classes
- assignments and tasks due or overdue
- today’s planned study sessions
- habits scheduled for today
- next action from one active personal project

This is the main focus screen of the app.

---

### Weekly Review
A reflective and academic-oriented review:

- completed assignments
- study sessions completed
- subjects that were neglected
- unfinished tasks
- preparation for next week

---

## Incremental Development Methodology

The project is developed in three structured phases.

---

## Phase 1 – Structure, Layout and Requirements

Focus:
- no logic
- no database
- no real interactivity

Main objective:
Build the complete visual structure of the student platform and define functional and AI requirements.

Deliverables:

- project folder structure
- static HTML pages for:
  - Today
  - Subjects
  - Schedule
  - Study Planner
  - Projects
  - Habits
  - Inbox
  - Weekly Review
- common layout with:
  - sidebar navigation
  - top header with quick add and search
- reusable UI components:
  - subject cards
  - assignment cards
  - study session cards
  - habit cards
  - project cards
  - schedule blocks
- base styling (cute and calm visual system)
- documentation:
  - system scope
  - user stories
  - business rules
  - future AI behavior

All data is static.

---

## Phase 2 – JavaScript Logic and Interactivity

Focus:
- client-side logic
- state handling
- dynamic rendering

Main objective:
Turn the static student interface into a real interactive system.

Main features:

- create and edit subjects
- add class schedule blocks
- create academic tasks linked to subjects
- create study sessions linked to subjects
- mark tasks, study sessions and habits as completed
- filter Today view by:
  - due tasks
  - planned study
  - classes
- move inbox items into subjects or projects
- store data in memory or localStorage
- UI updates without reload

No frameworks and no database.

---

## Phase 3 – React, Firebase and Deployment

Focus:
- component architecture
- cloud persistence
- authentication

Main objective:
Rebuild the system as a real production-ready student platform.

Planned technologies:

- React
- Firebase:
  - authentication
  - real-time database
  - hosting

Main features:

- user accounts
- persistent data:
  - subjects
  - schedules
  - assignments
  - study sessions
  - habits
  - projects
- real-time synchronization
- modular components
- responsive design

---

## Functional Scope (MVP – Student Version)

The MVP includes:

### Subjects
- create and edit subjects
- assign color and icon
- manage class schedule per subject

### Academic Tasks
- create, edit and delete assignments
- link tasks to subjects
- due date and task type
- mark as completed

### Study Sessions
- create study sessions for a subject
- estimate study time
- mark session as completed

### Schedule
- visual weekly calendar
- class blocks
- study blocks
- exam blocks

### Habits
- simple daily or weekday habits

### Today Dashboard
- today’s classes
- due or overdue assignments
- planned study sessions
- habits
- one active personal project action

---

## Out of Scope (First Version)

- notifications
- calendar sync with Google or Apple
- offline mode
- advanced analytics
- AI automation
- recommendation engine

---

## Future AI Support – Functional Definition

The system is prepared for an AI assistant focused on student productivity.

The AI will answer:

- What should I study today?
- Which subject am I falling behind in?
- How balanced is my study time this week?
- What is the next best study block for this subject?
- Summarize my progress in a subject or project

The AI will use:

- subjects
- assignments and deadlines
- study sessions and completion history
- habits
- schedule data
- activity logs

Only the specification is defined at this stage.

---

## Educational Objectives

This project strengthens:

- UI and layout design for real users
- JavaScript state and rendering
- data modeling (subjects, tasks, schedules, sessions)
- React architecture
- Firebase integration
- product design for real student needs

---

## Summary

Personal Work OS – Student Edition is a personalized academic productivity platform that merges:

subjects, assignments, schedules, study sessions, habits and personal projects into one calm and cute workspace.

It evolves step-by-step from static design to a full-stack real application and is fully aligned with a computer engineering student’s real daily workflow.
