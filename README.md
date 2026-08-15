***<img width="100" height="100" alt="Logo" src="https://github.com/user-attachments/assets/7051e8a5-81da-4470-a6ea-d19902bbf6d2" />***


**Silence** is a modern productivity and self-growth web application built for people who want to improve their lives quietly and consistently. It combines personal task management, habit tracking, journaling, reminders, analytics, and collaborative workspaces into a single platform.

> **Less noise. More progress.**

---

## Vision

Most productivity apps help you manage tasks. **Silence** is designed to help you manage **yourself**.

The goal is to create a digital environment where users can stay focused, build better habits, reflect on their progress, and grow together with people they trust.

---

## Features

### Personal Productivity

* Create, edit, and organize tasks
* Set priorities and due dates
* Create recurring (daily) tasks
* Track completed and pending tasks
* View daily and weekly productivity summaries

### Daily Journal

* Write a daily reflection at the end of each day
* Record achievements, lessons, and challenges
* Maintain a journal history through a calendar view
* Build a consistent writing habit over time

### Smart Reminders

* Schedule reminders for important tasks
* Create reminders directly from journal entries
* Receive morning notifications for planned activities
* Never forget important commitments again

### Shared Tasks

* Assign tasks to other users
* Receive tasks assigned by friends or teammates
* Track task ownership and progress
* Collaborate without losing personal organization

### Groups & Collaboration

* Create private groups
* Invite selected members
* Assign tasks to the entire group or specific members
* Manage collaborative projects, study groups, startup teams, or accountability circles

### Real-Time Chat

* Group messaging
* Direct conversations between users
* Task-related discussion threads
* Instant updates powered by Firebase

### Analytics & Progress Tracking

* Task completion charts
* Productivity trends
* Consistency tracking
---

## Planned Features

* Habit streaks
* Goal management
* Shared calendars
* Focus sessions (Pomodoro)
* AI-powered weekly insights
* Mood tracking
* Accountability partner mode

---

## Tech Stack

### Frontend

* React.js
* React Router
* Context API / Zustand
* Recharts
* Tailwind CSS

### Backend

* Firebase Authentication
* Cloud Firestore
* Firebase Cloud Messaging
* Firebase Storage
* Firebase Hosting

---

## Project Structure

```text
src/
  components/
  pages/
  hooks/
  context/
  services/
  utils/
  assets/

firebase/
```

---

## Core Modules

### Task System

Handles personal tasks, recurring tasks, priorities, deadlines, reminders, and completion tracking.

### Journal System

Stores daily reflections, journal history, reminder extraction, and writing streaks.

### Collaboration System

Manages shared tasks, user assignment, group workspaces, member roles, and real-time updates.

### Analytics System

Generates charts, productivity summaries, completion rates, and consistency metrics.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/silence.git
```

Install dependencies:

```bash
npm install
```

Create a Firebase project and add your Firebase configuration.

Start the development server:

```bash
npm run dev
```

---

## Environment Variables

Create a `.env` file:

```env
VITE_FIREBASE_API_KEY=
VITE_FIREBASE_AUTH_DOMAIN=
VITE_FIREBASE_PROJECT_ID=
VITE_FIREBASE_STORAGE_BUCKET=
VITE_FIREBASE_MESSAGING_SENDER_ID=
VITE_FIREBASE_APP_ID=
```

---

## Design Philosophy

Silence follows a **minimal, distraction-free design**.

The interface is intentionally simple, allowing users to focus on meaningful work instead of unnecessary visual noise.

Dark mode is treated as the primary experience.

---

## Why "Silence"?

Growth does not need to be loud.

The name represents the idea that meaningful progress often happens quietly, through consistent daily actions rather than public attention.

---

## Status

**Currently in active development.**

This project is being built as a portfolio-quality application and a real product focused on productivity, accountability, and personal growth.

---

## Author

**Tharusha Gihan**

If you are interested in productivity tools, React development, Firebase architecture, or building meaningful software products, feel free to connect and contribute.

---

## License

This project is licensed under the **MIT License**.
