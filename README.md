# HackTeams

This project was built in collaboration with a college senior and has been an absolutely incredible learning experience! It served as a deep dive into modern full-stack web development and database management.

---

## 📖 About the Project

HackTeams is a comprehensive full-stack web application designed to facilitate hackathon team building and management. Based on the project's structure, it allows users to register, create profiles, form teams, and manage hackathon events seamlessly.

## ✨ Key Features

Based on the application's routing and component structure, the platform includes the following features:

* **User Authentication:** Secure sign-in, registration, and logout flows.
* **User Profiles:** Dedicated public and private profile pages for users to showcase their skills and achievements.
* **Hackathon Dashboard:** Interfaces for exploring, joining, and managing hackathon events.
* **Team Management:** Capabilities to view team members, roles needed, and team posts.
* **Notifications:** A system to keep users updated on applications and team statuses.

---

## 🛠️ Tech Stack

This project leverages a modern, robust technology stack:

* **Framework:** Next.js utilizing the modern App Router (`src/app/`).
* **Language:** TypeScript (`.ts` and `.tsx` files throughout the project).
* **Database ORM:** Prisma (`prisma/schema.prisma` and automated migrations).
* **Styling:** CSS Modules (`*.module.css`) and PostCSS.
* **UI Components:** Modular, reusable UI components (like Buttons, Cards, Dialogs, and Avatars) located in `src/components/ui/`.

---

## 📁 Project Structure Highlights

* **`src/app/`**: Contains the core routing of the application, including API routes (`/api/teams`, `/api/users`, `/api/hackathon`) and front-end pages.
* **`src/components/`**: Houses reusable React components, split into specific domains like `events`, `teams`, and generic `ui` elements.
* **`prisma/`**: Contains the database schema and a detailed history of database migrations.
* **`public/`**: Stores static assets and images used across the platform.

---

## 🚀 Getting Started

To run this project locally on your machine, follow these steps:

1. **Clone the repository** to your local machine.
2. **Install dependencies** by running `npm install` in your terminal.
3. **Set up the database** using Prisma by running `npx prisma db push` or `npx prisma migrate dev`.
4. **Start the development server** with `npm run dev`.
5. **Open your browser** and navigate to `http://localhost:3000` to view the application.
