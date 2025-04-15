# 🕵️‍♂️ Watcher Web App

Watcher is a web application that lets users track changes to specific parts of a webpage. Unlike existing page monitoring tools, Watcher allows users to select exact DOM elements to watch, highlight detected changes, and receive real-time notifications when updates occur.

## 🚀 MVP Features

- [ ] Input URL + CSS selector
- [ ] Scrape and store content from the selected element
- [ ] Content verification
- [ ] Compare new content to previous snapshots
- [ ] Notify user of any changes (via browser or email)
- [ ] Dashboard for managing tracked pages and contents

## 🧰 Tech Stack (Planned)

- **Frontend:** Next.js (React + TypeScript), Tailwind CSS
- **Backend:** Next.js API Routes → eventually move to Node.js/Express or serverless
- **Database:** PostgreSQL (Supabase for now or Docker-based local later)
- **ORM:** Prisma
- **Auth:** NextAuth.js (or Supabase Auth)
- **Notifications:** Resend/Postmark/email-js (TBD)
- **Deployment:** Vercel

## 📁 Project Structure (WIP)

| Path/Filename          | Description                                  |
|------------------------|----------------------------------------------|
| watcher-web-app/       | Root directory                               |
| ├ └─ dev/                | For testing new and/or unfamiliar things     |
| ├ `README.md`            | Project overview and documentation           |

<!-- 
Other files and directories to consider
| ├ `app/` or `pages/` | App Router (Next.js 13+) or Pages Router (legacy) structure                 |
| ├└─ `api/`          | API endpoints (e.g., `/api/scrape`)                                         |
| ├ `components/`       | Reusable UI components                                                      |
| ├ `lib/`              | Server-side utilities (e.g., scraping, diffing, notifications)              |
| ├ `prisma/`           | Prisma schema and database migration files                                 |
| ├ `services/`         | Application logic (e.g., tracking, change detection)                        |
| ├ `hooks/`            | Custom React hooks (e.g., `useScrape`)                                     |
| ├ `context/`          | React Context Providers (e.g., auth, settings)                              |
| ├ `styles/`           | Tailwind CSS files and other stylesheets                                   |
| ├ `public/`           | Static assets (e.g., favicon, images)                                      |
| ├ `.env.local`        | Local environment variable configuration                                    | -->
