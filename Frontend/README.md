# ⚡ rPrep — Frontend Client

The frontend client for **rPrep** is built with **React 19**, **Vite 7**, and **Sass (SCSS)**, utilizing a domain-driven **Feature-Sliced Architecture** with dark/light theme support and responsive glassmorphic UI.

---

## 🚀 Key Highlights

* **React 19 & Vite 7**: Blazing-fast development server with instant HMR and optimized production bundles.
* **Feature-Sliced Architecture**: Code structured by business domain (`features/auth`, `features/interview`, `features/skills`).
* **Design System**: Tailored SCSS tokens, glassmorphic cards, fluid status badges, and interactive dark/light theme toggle.
* **Context & Custom Hooks**: `useInterview`, `useSkills`, and `useAuth` encapsulate API requests and reactive state.
* **Real-Time Skill Tracker**: Interactive drawer for managing skill gaps, generating AI learning pathways, and syncing career profile data.

---

## 🛠️ Quick Start

```bash
# Install dependencies
npm install

# Setup environment variables
cp .env.example .env

# Run development server
npm run dev
```

For the complete full-stack documentation, architecture diagrams, and API guides, see the [Main Project README](../README.md).
