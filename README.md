# DevFlow | Q&A Platform for Developers (Work in Progress)

![Next.js](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)

A Stack Overflow–style question and answer platform for developers, built with Next.js 15 and the App Router.

> **Status:** early stage. The project foundation is in place; product features are next.

## Done

- Next.js 15 (App Router) with React 19 and TypeScript.
- Code quality setup: ESLint (Standard, import order, Tailwind CSS plugin) and Prettier.
- Tailwind CSS v4 with custom design tokens and the Space Grotesk font.
- shadcn/ui components (Button, Dropdown Menu) on top of Radix UI.
- Light / dark / system theme with `next-themes` and a theme switcher in the navbar.
- Fixed, responsive navbar.

## Roadmap

- Authentication.
- Ask, answer and vote on questions.
- Tags, global search and user profiles.

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).
