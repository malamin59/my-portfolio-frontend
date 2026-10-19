My Portfolio Frontend

A modern, responsive developer portfolio built with Next.js 16, React, TypeScript, and Tailwind CSS v4. Designed with reusable components, clean code, and a scalable architecture.

✨ Features

Responsive portfolio website

Home, About, Projects, Achievements, Certificates, Services, and Contact pages

Dynamic project detail routes

Reusable UI and layout components

Shared configuration, utilities, hooks, services, and types

Dashboard foundation for future expansion

Scalable, feature-based architecture

🛠️ Tech Stack

Technology

Purpose

Next.js

React framework and App Router

React

UI development

TypeScript

Type safety

Tailwind CSS v4

Styling

pnpm

Package management

Redux Toolkit

Planned state management

📁 Project Structure

my-portfolio/
├── app/
│   ├── (pages)/
│   │   ├── about/page.tsx
│   │   ├── achievements/page.tsx
│   │   ├── certificates/page.tsx
│   │   ├── contact/page.tsx
│   │   ├── projects/
│   │   │   ├── page.tsx
│   │   │   └── [slug]/page.tsx
│   │   └── services/page.tsx
│   ├── dashboard/
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   ├── loading.tsx
│   ├── not-found.tsx
│   ├── page.tsx
│   └── providers.tsx
├── components/
│   ├── ui/
│   ├── shared/
│   ├── layout/
│   └── sections/
├── core/
│   ├── config/
│   ├── hooks/
│   ├── lib/
│   ├── services/
│   └── types/
├── features/
├── store/
├── data/
├── public/
│   ├── images/
│   └── icons/
├── .gitignore
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── pnpm-lock.yaml
├── postcss.config.mjs
├── README.md
└── tsconfig.json

🚀 Getting Started

Prerequisites

Node.js

pnpm

Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/my-portfolio-frontend.git

Navigate to the project directory:

cd my-portfolio-frontend

Install dependencies:

pnpm install

Start the development server:

pnpm dev

Open http://localhost:3000.

🧱 Architecture Principles

Reusable components: Build consistent UI without unnecessary duplication.

DRY: Keep shared logic and styles maintainable.

Feature-based organization: Group feature-specific components and logic together.

Type safety: Use TypeScript to improve code reliability.

Scalability: Keep the frontend organized as new features are added.

🗺️ Roadmap

Build responsive portfolio UI

Implement reusable components

Add project data and detail pages

Add dark mode

Integrate Redux Toolkit if shared client state requires it

Implement authentication and dashboard features

Add notifications, real-time chat, and AI assistant

Connect backend APIs

📌 Project Status

In Development — Features and architecture are being implemented progressively.

## 👨‍💻 Author

**Al Amin Patwary**  
Full Stack Developer

- **GitHub:** [@malamin59](https://github.com/malamin59)
- **Portfolio:** [alamin-15553.web.app](https://alamin-15553.web.app/)
- **LinkedIn:** [alamin-epb](https://www.linkedin.com/in/alamin-epb/)
- **Email:** [alamindev.epb@gmail.com](mailto:alamindev.epb@gmail.com)
- **WhatsApp:** [+880 1622-018102](https://wa.me/8801622018102)

---

Built with ❤️ using Next.js and TypeScript.