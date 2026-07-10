# SYSTEM_ARCHITECTURE.md

# TaskMatrix – Frontend System Architecture

## Redux State Tree

```text
store
│
├── auth
│   ├── user
│   ├── token
│   ├── role
│   ├── isAuthenticated
│   ├── loading
│   └── error
│
├── projects
│   ├── projectList
│   ├── selectedProject
│   ├── loading
│   └── error
│
├── tasks
│   ├── taskList
│   ├── selectedTask
│   ├── filters
│   ├── loading
│   └── error
│
├── notifications
│   ├── list
│   ├── unreadCount
│   └── loading
│
├── users
│   ├── members
│   ├── profile
│   └── loading
│
├── ui
│   ├── sidebarOpen
│   ├── theme
│   ├── modal
│   └── toast
│
└── settings
    ├── language
    ├── appearance
    └── preferences
```

---

# Application Flow

```text
Login
   │
   ▼
Authentication
   │
   ▼
Dashboard
   │
   ▼
Projects
   │
   ▼
Project Details
   │
   ▼
Kanban Board
   │
   ▼
Task Details
   │
   ▼
Update Task
   │
   ▼
Activity Feed
```

---

# Next.js Routing

```
/

/login

/register

/dashboard

/projects

/projects/[id]

/projects/[id]/board

/tasks/[id]

/profile

/settings

/notifications

/404
```

---

# Mock REST API

## Authentication

POST /api/login

POST /api/register

POST /api/logout

GET /api/profile

---

## Projects

GET /api/projects

GET /api/projects/:id

POST /api/projects

PATCH /api/projects/:id

DELETE /api/projects/:id

---

## Tasks

GET /api/tasks

GET /api/tasks/:id

POST /api/tasks

PATCH /api/tasks/:id

DELETE /api/tasks/:id

---

## Users

GET /api/users

GET /api/users/:id

PATCH /api/users/:id

---

## Notifications

GET /api/notifications

PATCH /api/notifications/read

---

# Component Architecture

App

├── Navbar

├── Sidebar

├── Footer

├── Dashboard

│   ├── StatsCard

│   ├── ProjectCard

│   ├── RecentActivity

│   └── NotificationPanel

├── Project

│   ├── ProjectHeader

│   ├── MemberList

│   └── ProjectInfo

├── Kanban

│   ├── Board

│   ├── Column

│   ├── TaskCard

│   └── DragLayer

├── Task

│   ├── TaskDetails

│   ├── Comments

│   ├── Attachments

│   └── ActivityTimeline

├── Profile

├── Settings

└── Common Components

```
├── Button

├── Modal

├── Loader

├── Badge

├── Avatar

├── Input

├── SearchBar

├── Pagination

└── Toast
```

---

# Data Flow

User Action

↓

Redux Action

↓

Redux Slice

↓

Redux Store

↓

React Component

↓

Updated UI

---

# Planned API Integration

Current Sprint

Mock JSON Data

↓

Redux

↓

UI

Future Sprint

Backend API

↓

Redux Toolkit

↓

UI

---

# Folder Architecture

src

├── app

├── components

├── features

├── hooks

├── services

├── store

├── lib

├── types

├── utils

└── styles

---

# Architecture Summary

Frontend Framework

* Next.js

State Management

* Redux Toolkit

Styling

* Tailwind CSS

UI Library

* Shadcn UI

Mock Data

* JSON

Persistence

* LocalStorage

Deployment

* Vercel

Version Control

* GitHub
