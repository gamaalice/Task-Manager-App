# Task Manager — OutSystems Web Application

A web application developed with OutSystems for task management,
covering the full development lifecycle: data modeling, business logic,
user interface, and role-based access control.

---

## Problem

Teams often struggle to track tasks, priorities, and deadlines
without a centralized system. Manual processes lead to missed
deadlines and lack of visibility over work status.

## Solution

A responsive web application that centralizes task management,
enabling users to create, view, edit, and monitor tasks with
priority and status control — all with role-based access.

---

## Screens

- **Dashboard** — Visual overview with charts (pie and bar)
  displaying task count by status and priority
- **Tasks** — Full task listing with status indicators
  and priority badges
- **Task Detail View** — Complete task information with
  timeline progress and metadata
- **Task Edit Screen** — Form for updating task data
  including priority, status, and due date
- **Import Data** — Screen for bulk data management

---

## Data Model

Entity: `Tasks`

| Field       | Type              |
|-------------|-------------------|
| Title       | Text              |
| Description | Text              |
| Priority    | Integer (Enum)    |
| Status      | Integer (Enum)    |
| User        | User (FK)         |
| Due Date    | Date              |
| Created At  | DateTime          |
| Updated At  | DateTime          |

---

## Roles

| Role  | Access                                      |
|-------|---------------------------------------------|
| Admin | Full access — create, edit, delete, import  |
| User  | View and edit own tasks                     |

---

## Technical Highlights

- Developed entirely in OutSystems (Reactive Web App)
- SQL-based data modeling with relational entities and enums
- Role-based access control (Admin / User)
- Dashboard with data visualization — pie and bar charts
- Business logic implemented via Server Actions and Client Actions
- Manual testing performed across all screens and user flows
- Technical documentation maintained throughout development

---

## Technologies

- OutSystems (Reactive Web)
- SQL (OutSystems relational database)
- OutSystems UI Framework
- Built-in Charts (Dashboard visualization)

---

## Screenshots

Available in the `/screenshots` folder.

---

## Author

Alice Gama — [github.com/gamaalice](https://github.com/gamaalice)
