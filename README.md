Nexus

💡 Philosophy
In today's digital world, information exists in fragmented pieces across countless platforms. Nexus was designed to unify these fragments. Our core philosophy is to empower users to build their own "second brain" by treating all information as flexible, interconnected, and easily organizable blocks. We aim for the perfect balance between simplicity and power.

✨ Key Features
✍️ Dynamic Block-Based Editor: Everything is a block. Text, lists, images, and more can be effortlessly rearranged with drag-and-drop. Accelerate your workflow with slash (/) commands.

⚡ Real-Time Synchronization: Powered by Convex, every change you make is instantly synced across all your devices. Collaborate on the same document with teammates without any latency.

🔗 Infinite Hierarchy: Organize your information with infinite depth using pages and nested sub-pages. Navigate through your ideas without ever getting lost.

🌐 One-Click Publishing: Instantly turn your private notes or documents into live web pages and share them with the world.

🎨 Customizable Pages: Personalize your workspace by adding a unique icon and cover image to every page.

🗑️ Smart Trash Can: Never lose your work permanently. Easily restore deleted pages whenever you need them.

🌓 Light & Dark Theme: Work in a light or dark environment for a comfortable viewing experience, based on system preference or user choice.

🚀 Performance-Oriented: Optimized for a fast, fluid, and uninterrupted user experience, built with the most modern technologies.

🛠️ Technology Architecture
Nexus is built upon a scalable, reliable, and modern architecture.

Category Technology Description
Frontend Next.js, React, TypeScript For performant, server-side rendered, and statically generated web applications.
Backend & Database Convex A real-time, serverless backend and database platform.
Authentication Clerk A fast and secure solution for user management and authentication.
File Storage EdgeStore For securely uploading and serving files, such as cover images.
UI/UX Tailwind CSS, Shadcn/ui A modern, customizable, and accessible design system.
State Management Zustand A minimalist and powerful state management library.
Tooling Prettier, ESLint, Husky To ensure code quality and consistency.

🚀 Setting Up Your Local Environment
Follow the steps below to set up and run the project on your local machine.

1. Prerequisites
   Node.js (v18.x or higher)

npm / yarn / pnpm

2. Cloning & Installation
   Bash

# Clone the repository

git clone https://github.com/YigitAlpYildirim/Nexus.git

# Navigate to the project directory

cd nexus

# Install the necessary dependencies

npm install 3. Environment Variable Configuration
You must define the necessary service keys for the project to function. Create a file named .env.local in the project's root directory and populate it with the following content:

Kod snippet'i

# Convex: https://dashboard.convex.dev

# Paste the URL that appears in your terminal after running `npx convex dev`.

NEXT_PUBLIC_CONVEX_URL=

# Clerk: https://dashboard.clerk.com

# Paste the API keys from your Clerk project.

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# EdgeStore: https://dashboard.edgestore.dev

# Paste the keys from your EdgeStore project.

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY= 4. Running the Services
You will need two separate terminal sessions for the application to run with full functionality.

Terminal 1: Convex Backend
Start the Convex development server. This will sync your database schema and run a local backend instance.

Bash

npx convex dev
Terminal 2: Next.js Frontend
Start the Next.js development server.

Bash

npm run dev
You can now navigate to http://localhost:3000 in your browser to start exploring Nexus.
