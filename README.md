
# 🚀 TeamSync — Scalable Multi-Tenant Project Management System

**TeamSync** is a modern and scalable multi-tenancy project management system tailored for real-world B2B needs. Built using the **MERN Stack** with **TypeScript**, it delivers robust functionality like workspace management, task collaboration, Google OAuth, role-based access, and more — all within a clean, responsive UI.

---

## 📌 Overview

TeamSync empowers businesses and teams to seamlessly manage projects, tasks, and workspaces with advanced collaboration and permission control mechanisms.

---

## 🌟 Key Features

* 🔐 **Authentication**

  * Google Sign-In
  * Email & Password-based login

* 🏢 **Workspace Management**

  * Create & manage multiple workspaces
  * Invite team members via email

* 📊 **Project & Epic Management**

  * Organize projects into epics
  * Track progress and hierarchy

* ✅ **Tasks Management (CRUD)**

  * Set status, priority, assignee
  * Inline edits and updates

* 👥 **Roles & Permissions**

  * Owner, Admin, Member roles
  * Scoped access controls

* 🔍 **Search & Filtering**

  * Filter by status, priority, assignee
  * Quick task discovery

* 📈 **Analytics Dashboard**

  * Visual representation of project progress

* 📅 **Pagination & Load More**

  * Optimized data fetching for scalability

* 🔒 **Secure Session Management**

  * Cookie-based session handling
  * Safe logout and session termination

* 🌱 **Data Seeding**

  * Preload dummy data for testing

* 💾 **Mongoose Transactions**

  * Ensure robust data consistency

---

## 🛠️ Tech Stack & Tools

| Category           | Tools & Frameworks                                                   |
| ------------------ | -------------------------------------------------------------------- |
| **Frontend**       | React.js, TypeScript, Vite.js, TailwindCSS, Shadcn UI                |
| **Backend**        | Node.js, Express.js, Mongoose, MongoDB, Cookie-Session, Google OAuth |
| **Database**       | MongoDB (with Mongoose for schema management)                        |
| **Authentication** | Google Sign-In (OAuth 2.0), Secure cookie sessions                   |
| **Dev Tools**      | Postman, VS Code, ESLint, Prettier, Git, GitHub                      |

---

## 🔄 Getting Started

### 1. 📺 Watch the Video Guide

Start by watching the full walkthrough on YouTube.

### 2. ⚙️ Set Up Environment Variables

Create a `.env` file at the root level and configure the following:

```env
PORT=8000
NODE_ENV=development
MONGO_URI="mongodb+srv://<username>:<password>@cluster.mongodb.net/teamsync_db"

SESSION_SECRET="session_secret_key"

GOOGLE_CLIENT_ID=<your-google-client-id>
GOOGLE_CLIENT_SECRET=<your-google-client-secret>
GOOGLE_CALLBACK_URL=http://localhost:8000/api/auth/google/callback

FRONTEND_ORIGIN=http://localhost:3000
FRONTEND_GOOGLE_CALLBACK_URL=http://localhost:3000/google/callback
```

### 3. 🚀 Run the Application

```bash
# Install dependencies
npm install

# Start the backend server
npm run dev
```

* Backend running at: [http://localhost:8000](http://localhost:8000)
* Frontend running at: [http://localhost:3000](http://localhost:3000)

---

## 🌍 Deployment Guide

### Step 1: Configure Environment Variables

Add your `.env` variables to your deployment platform (e.g., Vercel, Heroku).

### Step 2: Deploy

Deploy the app using your preferred cloud platform. Make sure both backend and frontend URLs are correctly configured.

---

## 📚 Deep Dive Documentation

### 🧠 What You'll Learn:

* System architecture & design principles
* Feature-by-feature implementation breakdown
* Role-based access control for multi-tenant systems
* Mongoose transactions & test data seeding
* Scalable SaaS patterns for real-world B2B apps
* Performance optimizations and best practices

This guide ensures a comprehensive understanding of how TeamSync works — empowering you to contribute, extend, or build your own production-grade systems with confidence.


