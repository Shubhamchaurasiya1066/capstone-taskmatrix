# capstone-taskmatrix

Folder Structure:-

capstone-taskmatrix
│
├── README.md
├── PROMPTS.md
├── LICENSE
├── .gitignore
├── package.json
│
├── docs
│   ├── architecture
│   │      state-tree.png
│   │      app-flow.png
│   │
│   ├── wireframes
│   │      login.png
│   │      dashboard.png
│   │      task-details.png
│   │
│   └── screenshots
│
├── public
│
└── src
    ├── app
    ├── components
    ├── features
    ├── hooks
    ├── layouts
    ├── lib
    ├── services
    ├── store
    ├── types
    ├── utils
    └── styles

# 🚀 TaskMatrix

## Enterprise Agile Project Management Platform

TaskMatrix is a modern project management application inspired by Jira and Asana. It helps software teams efficiently plan projects, organize tasks, collaborate with team members, and monitor project progress using a Kanban workflow.

This project is being developed as the Sprint 13 Capstone Blueprint for the Prodesk IT Internship Program.

---

# Project Information

| Property | Value |
|----------|--------|
| Project Name | TaskMatrix |
| Sprint | Sprint 13 Capstone |
| Track | Frontend Specialist |
| Repository | prodesk-capstone-taskmatrix |
| Status | Product Planning Phase |

---

# Problem Statement

Managing software projects using spreadsheets or manual tracking leads to poor collaboration, missed deadlines, and lack of visibility.

TaskMatrix solves these problems by providing a centralized dashboard where teams can create projects, assign work, manage deadlines, and monitor progress in real time.

---

# Objectives

The primary objective of TaskMatrix is to build a scalable project management platform that provides:

- Team collaboration
- Project organization
- Task management
- Real-time project visibility
- Modern user experience
- Mobile responsive interface

---

# Target Users

- Software Developers
- Project Managers
- Team Leads
- Freelancers
- Startups
- Agencies

---

# Tech Stack

Frontend

- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- Shadcn UI

State Management

- Redux Toolkit

Data

- Mock JSON API
- Local Storage

Development

- ESLint
- Prettier
- Storybook

Deployment

- Vercel

Version Control

- Git
- GitHub

---

# Core Features

## Authentication

- Login
- Register
- Forgot Password
- Logout

---

## Dashboard

- Project Overview
- Team Statistics
- Task Summary
- Activity Feed
- Deadlines
- Notifications

---

## Project Management

- Create Project
- Edit Project
- Delete Project
- Archive Project
- Project Members

---

## Task Management

- Create Task
- Edit Task
- Delete Task
- Assign Task
- Due Date
- Labels
- Priority
- Status

---

## Kanban Board

- To Do
- In Progress
- Review
- Done

Drag and Drop support

---

## User Profile

- Edit Profile
- Upload Avatar
- Change Password
- User Settings

---

## Notifications

- Assignment Updates
- Deadline Alerts
- Activity Notifications

---

## Search

- Global Search
- Filter by Status
- Filter by Priority
- Filter by Member

---

## UI Features

- Dark Mode
- Responsive Design
- Modern Dashboard
- Loading Skeletons
- Toast Messages

---

# User Roles

## Admin

- Manage Users
- Manage Projects
- Assign Tasks
- Delete Tasks

---

## Manager

- Create Projects
- Manage Team
- Assign Tasks

---

## Member

- View Assigned Tasks
- Update Status
- Comment

---

# Pages

Home

Login

Register

Dashboard

Projects

Project Details

Kanban Board

Task Details

Notifications

Profile

Settings

404

---

# Planned Routing

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

---

# Redux Store Planning

store

auth

projects

tasks

notifications

users

ui

settings

---

# Mock API Endpoints

POST /login

POST /register

GET /projects

POST /projects

PATCH /projects/:id

DELETE /projects/:id

GET /tasks

POST /tasks

PATCH /tasks/:id

DELETE /tasks/:id

GET /users

GET /notifications

---

# Folder Architecture

src

app

components

features

hooks

layouts

services

store

styles

types

utils

---

# Performance Goals

Fast page rendering

Lazy Loading

Optimized Images

Code Splitting

Reusable Components

---

# Accessibility

Keyboard Navigation

ARIA Labels

Proper Color Contrast

Responsive Typography

---

# Responsive Strategy

Desktop

Tablet

Mobile

---

# Future Scope

Calendar View

Time Tracking

Chat System

File Upload

Email Notifications

AI Task Suggestions

Analytics Dashboard

---

# Figma Wireframes

Public Link

(Add Your Figma Link Here)

---

# State Architecture

(Add state-tree.png here)

---

# Application Flow

(Add app-flow.png here)

---

# Demo

Duration

3 Minutes

Presentation Flow

Introduction

Project Problem

Solution

Wireframes

Redux Architecture

Mock API

Future Scope

---

# Timeline

Sprint 13

Planning

Sprint 14

MVP Development

Sprint 15

Feature Completion

Sprint 16

AI Integration

Sprint 17

Deployment

---

# Author

Shubham Chaurasiya


Prodesk IT Internship Program
