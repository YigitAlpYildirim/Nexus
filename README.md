\<div align="center"\>

\<h1 align="center"\>Nexus\</h1\>

\<p align="center"\>
\<i\>The all-in-one workspace where your ideas, knowledge, and projects converge.\</i\>
\<br /\>
\<br /\>
\<a href="[https://github.com/YigitAlpYildirim/Nexus/issues](https://www.google.com/search?q=https://github.com/YigitAlpYildirim/Nexus/issues)"\>Report Bug\</a\>
·
\<a href="[https://github.com/YigitAlpYildirim/Nexus/issues](https://www.google.com/search?q=https://github.com/YigitAlpYildirim/Nexus/issues)"\>Request Feature\</a\>
\</p\>

\<p align="center"\>
\<a href="YOUR_LIVE_DEMO_URL_HERE"\>
\<img src="[https://via.placeholder.com/1200x675/1F2937/FFFFFF?text=Nexus+Application+Screenshot](https://www.google.com/search?q=https://via.placeholder.com/1200x675/1F2937/FFFFFF%3Ftext%3DNexus%2BApplication%2BScreenshot)" alt="Nexus Project Screenshot" style="border-radius: 8px; width: 80%;"\>
\</a\>
\</p\>
\</div\>

---

### 🚀 About The Project

In today's digital world, information exists in fragmented pieces across countless platforms. **Nexus** was designed to unify these fragments.

Our core philosophy is to empower users to build their own "second brain" by treating all information as flexible, interconnected, and easily organizable blocks. We aim for the perfect balance between simplicity and power, creating a distraction-free environment for your thoughts to flourish.

---

### ✨ Key Features

| Feature                           | Description                                                                                                                                   |
| :-------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------- |
| ✍️ **Dynamic Block-Based Editor** | Everything is a block. Effortlessly rearrange text, lists, and images with drag-and-drop. Accelerate your workflow with slash (`/`) commands. |
| ⚡ **Real-Time Synchronization**  | Powered by Convex, every change is instantly synced across all your devices. Collaborate seamlessly with teammates without any latency.       |
| 🔗 **Infinite Hierarchy**         | Organize your information with infinite depth using pages and nested sub-pages. Navigate through your ideas without ever getting lost.        |
| 🌐 **One-Click Publishing**       | Instantly turn your private notes or documents into live web pages and share them with the world.                                             |
| 🎨 **Customizable Pages**         | Personalize your workspace by adding a unique icon and cover image to every page.                                                             |
| 🗑️ **Smart Trash Can**            | Never lose your work permanently. Easily restore deleted pages whenever you need them.                                                        |
| 🌓 **Light & Dark Theme**         | Work in a light or dark environment for a comfortable viewing experience, based on system preference or user choice.                          |
| 🚀 **Performance-Oriented**       | Optimized for a fast, fluid, and uninterrupted user experience, built with the most modern technologies.                                      |

---

### 🛠️ Tech Stack

Nexus is built upon a scalable, reliable, and modern architecture.

**Frontend:**

**Backend & Services:**

**State Management & Tooling:**

---

### ⚙️ Setting Up Your Local Environment

Follow the steps below to set up and run the project on your local machine.

#### 1\. Prerequisites

- Node.js (v18.x or higher)
- npm / yarn / pnpm

#### 2\. Cloning & Installation

```bash
# Clone the repository
git clone https://github.com/YigitAlpYildirim/Nexus.git

# Navigate to the project directory
cd Nexus

# Install the necessary dependencies
npm install
```

#### 3\. Environment Variable Configuration

You must define the necessary service keys for the project to function. Create a file named `.env.local` in the project's root directory and populate it with the following content:

```env
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
EDGE_STORE_SECRET_KEY=
```

#### 4\. Running the Services

You will need two separate terminal sessions for the application to run with full functionality.

**Terminal 1: Convex Backend**
_This will sync your database schema and run a local backend instance._

```bash
npx convex dev
```

**Terminal 2: Next.js Frontend**
_This will start the main application server._

```bash
npm run dev
```

You can now navigate to `http://localhost:3000` in your browser to start exploring Nexus.
