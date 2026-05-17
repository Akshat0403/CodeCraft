# 🛠️ Code Craft

> **An Interactive Online Code Editor & Snippet Sharing Platform — Built for Developers, by Developers**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-code--craft--mew6.vercel.app-blue?style=for-the-badge&logo=vercel)](https://code-craft-mew6.vercel.app/)
[![Next.js](https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/)

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Project Structure](#-project-structure)
- [Pages & Routes](#-pages--routes)
- [Pro Plan](#-pro-plan)
- [Environment Variables](#-environment-variables)
- [Deployment](#-deployment)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 Overview

**Code Craft** is a full-featured, browser-based code editor that allows developers to write, run, and share code snippets seamlessly. Whether you're experimenting with a quick idea, preparing a demo, or collaborating with teammates — Code Craft has you covered.

The platform supports multi-language code execution, snippet management, and offers a Pro tier with advanced tools like AI assistance, real-time pair programming, and one-click deployment.

---

## ✨ Features

### 🆓 Free Tier
- **Interactive Code Editor** — Write and execute code directly in the browser
- **Multi-language Support** — Run code in multiple programming languages
- **Live Output Panel** — See your code's output in real time
- **Snippets Library** — Browse and explore shared code snippets
- **Responsive UI** — Works seamlessly across all devices

### 💎 Pro Tier (Lifetime Access — $39 one-time)
| Category | Features |
|---|---|
| **Development** | Advanced AI, Custom theme builder, Integrated debugging tools, Multi-language support |
| **Collaboration** | Real-time pair programming, Team workspaces, Version control integration, Code review tools |
| **Deployment** | One-click deployment, CI/CD integration, Container support, Custom domain mapping |

### 🏗️ Infrastructure
- ⚡ **Global Infrastructure** — Lightning-fast execution across worldwide edge nodes
- 🔒 **Enterprise Security** — Bank-grade encryption and security protocols
- 🔄 **Real-time Sync** — Instant synchronization across all devices
- 💾 **Unlimited Storage** — Store unlimited snippets and projects (Pro)

---

## 🧰 Tech Stack

| Layer | Technology |
|---|---|
| **Framework** | [Next.js](https://nextjs.org/) (App Router) |
| **Language** | TypeScript / JavaScript |
| **Styling** | Tailwind CSS |
| **Deployment** | [Vercel](https://vercel.com/) |
| **Authentication** | Clerk / NextAuth (Sign-in for Pro features) |
| **Code Execution** | Sandboxed runtime environment |

---

## 🚀 Getting Started

### Prerequisites
- Node.js `v18+`
- npm / yarn / pnpm

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/code-craft.git
cd code-craft

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env.local
# Fill in the required values (see Environment Variables section)

# 4. Start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
code-craft/
├── app/
│   ├── (root)/           # Main editor page
│   ├── snippets/         # Snippets listing & detail pages
│   ├── pricing/          # Pro plan page
│   ├── support/          # Support page
│   ├── privacy/          # Privacy policy
│   └── terms/            # Terms of service
├── components/           # Reusable UI components
│   ├── Editor/           # Code editor component
│   ├── OutputPanel/      # Code output display
│   └── Navbar/           # Navigation bar
├── lib/                  # Utility functions & helpers
├── public/               # Static assets
└── styles/               # Global styles
```

---

## 🗺️ Pages & Routes

| Route | Description |
|---|---|
| `/` | Main interactive code editor with output panel |
| `/snippets` | Browse publicly shared code snippets |
| `/pricing` | Pro plan details and upgrade page |
| `/support` | Help & support page |
| `/privacy` | Privacy policy |
| `/terms` | Terms of service |

---

## 💰 Pro Plan

Code Craft offers a **lifetime Pro access** for a one-time payment of **$39**.

To upgrade:
1. Visit [/pricing](https://code-craft-mew6.vercel.app/pricing)
2. Click **Sign In** to authenticate
3. Complete the one-time payment
4. Instantly unlock all Pro features

---

## 🔐 Environment Variables

Create a `.env.local` file at the root of the project and add:

```env
# Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Code Execution API
CODE_EXECUTION_API_URL=
CODE_EXECUTION_API_KEY=

# Database (if applicable)
DATABASE_URL=

# Payments
STRIPE_SECRET_KEY=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_WEBHOOK_SECRET=
```

> ⚠️ Never commit your `.env.local` file. It is already included in `.gitignore`.

---

## 🌐 Deployment

This project is deployed on **Vercel**. To deploy your own instance:

1. Push your code to GitHub
2. Import the repository on [Vercel](https://vercel.com/new)
3. Add all environment variables in the Vercel dashboard
4. Click **Deploy**

```bash
# Or deploy via Vercel CLI
npm i -g vercel
vercel --prod
```

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

```bash
# Fork the repo, then:
git checkout -b feature/your-feature-name
git commit -m "feat: add your feature"
git push origin feature/your-feature-name
# Open a Pull Request
```

Please make sure your code follows the existing style and passes all checks before submitting a PR.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

<div align="center">

**Built with ❤️ for developers**

[Live Demo](https://code-craft-mew6.vercel.app/) · [Report Bug](https://code-craft-mew6.vercel.app/support) · [Request Feature](https://code-craft-mew6.vercel.app/support)

</div>
