🚀 Task Management System

A modern SaaS-style task management platform built with Next.js, TypeScript, Tailwind CSS, and shadcn/ui.
This project helps users and admins manage daily tasks efficiently, track progress, and collaborate in real time — built to simulate a real-world, production-level web application.

✨ Features

🔐 Authentication & Authorization – Secure login and role-based access using NextAuth

👥 Admin & User Roles – Admins can manage users, view stats, and control system data

🧭 Dashboard Overview – View project insights, user stats, and performance analytics

📝 Task Management – Create, assign, update, and delete tasks in real-time

🔍 Search & Filter – Easily find tasks or users with dynamic filtering

🌍 Responsive Design – Works perfectly on desktop, tablet, and mobile

🎨 Modern UI – Built with Tailwind CSS + shadcn/ui components for a sleek professional look

🧠 State Management – Managed via React hooks and Context API for smooth data flow

⚡ API Integration – Connects to an external API for fetching and storing data (practice-ready)

🗂 Reusable Components – Organized component-based structure for scalability

🏗️ Project Structure
task-manager/
├── app/                    # Next.js App Router
│   ├── api/                # API routes for tasks and auth
│   ├── dashboard/          # Protected dashboard pages
│   ├── auth/               # Login, register, forgot password
│   └── page.tsx            # Landing page
├── components/             # UI components (buttons, forms, cards)
├── lib/                    # Utility functions and constants
├── hooks/                  # Custom React hooks
├── public/                 # Static assets (icons, images)
├── styles/                 # Global and Tailwind styles
├── package.json
└── README.md

🧩 Technology Stack
Technology	Purpose
Next.js 14	Framework for full-stack React apps
TypeScript	Type safety and maintainability
Tailwind CSS	Utility-first modern styling
shadcn/ui	Ready-to-use, accessible UI components
Lucide React	Modern icon library
NextAuth	Authentication and session management
MongoDB / External API	Database or data fetching practice
Vercel / Netlify	Deployment platform


🧰 Getting Started
✅ Prerequisites

Node.js 18+

npm 8+ or yarn

A modern browser


⚙️ Installation

1️⃣ Clone the repository:

git clone https://github.com/yourusername/task-management-system.git
cd task-management-system


2️⃣ Install dependencies:

npm install


3️⃣ Run the development server:

npm run dev


4️⃣ Open your browser and visit:

http://localhost:3001


👤 User Roles
🔹 Admin

Manage users (create, delete, assign roles)

Monitor system analytics (task stats, active users)

Access all dashboards and reports

🔹 User

Create, update, and delete personal tasks

View task status and deadlines

Filter and search tasks by category or priority


🧱 Core Modules
Module	Description
Auth Module =	Handles login, registration, and sessions
Task Module =	CRUD for tasks and progress tracking
Dashboard Module =	Analytics and insights for users/admins
User Management Module =	Admin-only user controls

UI Overview

Landing Page

Login / Register / Forgot Password

User Dashboard

Admin Dashboard

Task List & Task Details

User Management Page

🧠 Learning Goals

This project helps developers:

Understand full-stack app structure using Next.js

Practice real-world authentication & authorization

Master API integration, CRUD operations, and UI composition

Build scalable, maintainable SaaS dashboards

Strengthen frontend + backend collaboration logic
