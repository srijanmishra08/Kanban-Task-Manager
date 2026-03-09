# Kanban Task Manager — Reshuffle

A freelancer-centric Kanban task manager built as part of the [Reshuffle](https://reshuffle.app) tools ecosystem.

## Features

- **Client Projects** — Organize work by client with budget tracking, deadlines, and project descriptions
- **Kanban Board** — Drag-and-drop task management across 7 freelancer-specific columns:
  - Backlog → To Do → In Progress → Client Review → Revision → Completed → Invoiced
- **Budget Tracking** — Track total project budget and per-task budget allocation
- **Priority Management** — Assign urgency levels (Low, Medium, High, Urgent) to tasks
- **Deadline Monitoring** — Visual indicators for upcoming and overdue deadlines
- **Dashboard** — Overview of all projects, completion rates, and upcoming deadlines
- **Project Export** — Export project summaries as text files for client communication
- **Search** — Quickly find tasks across your board
- **Keyboard Shortcuts** — `Ctrl/Cmd + N` for new project/task

## Tech Stack

- 100% client-side (HTML, CSS, JavaScript)
- No backend required — data stored in localStorage
- Dark theme matching the Reshuffle design system
- Responsive design for desktop and mobile

## Deployment

Deployed on [Vercel](https://vercel.com) as a static site. The `vercel.json` config handles routing.

## Development

Simply open `index.html` in a browser. No build step or dependencies required.

## Part of Reshuffle

This tool is one of the freelancer productivity tools offered by Reshuffle:

1. **Network** — Connect with fellow freelancers
2. **Portfolio Engine** — Build your professional portfolio
3. **Onboarding Questionnaire** — Streamline client onboarding
4. **Service Agreement Generator** — Create professional contracts
5. **Kanban Task Manager** — Manage project tasks (this tool)

---

Built by [Srijan Mishra](https://github.com/srijanmishra08)
