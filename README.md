# Next Ecommerce

High-performance Next.js e-commerce storefront with AI Vector Search, Shopify integration and Turborepo monorepo architecture.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat&logo=storybook&logoColor=white)

## About

Fork of [Blazity Enterprise Commerce](https://github.com/Blazity/enterprise-commerce) — an enterprise-grade Next.js e-commerce starter. Used for learning and exploring advanced patterns: AI-powered vector search, Shopify integration via Meilisearch, A/B testing with Vercel feature flags, and a complete monorepo setup with Turborepo.

## Pages

| Page | Description |
|---|---|
| **Home / [bucket]** | Main storefront with A/B test buckets |
| **Category** | Product category listing |
| **Product / [slug]** | Product detail page |
| **Search** | AI-powered product search |
| **Favorites** | Saved products |
| **Reviews / [slug]** | Product reviews |
| **Pages / [slug]** | Dynamic CMS pages |
| **Settings** | User settings |
| **Access Denied** | Auth restriction page |

## Features

- **AI Vector Search** — intelligent product search powered by Meilisearch
- **Shopify integration** — platform-agnostic with Shopify by default
- **A/B Testing** — Vercel feature flags with bucket-based routing
- **React Server Components** — RSC, Suspense and Streaming
- **Server Actions** — Next.js server-side mutations
- **Turborepo** — monorepo with shared packages (core, reviews, tailwind-config, tsconfig)
- **Storybook** — component documentation and testing
- **Playwright** — end-to-end testing
- **Jest + React Testing Library** — unit testing
- **Radix UI** — accessible component primitives
- **Zustand** — client state management
- **Vercel Analytics + Speed Insights** — performance monitoring
- **Bloom Filters** — scalable SEO redirect handling
- **Dynamic OG Images** — auto-generated social preview images
- **Semantic Release** — automated versioning and changelog

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 14 | React framework |
| TypeScript | Type safety |
| Tailwind CSS | Styling |
| Meilisearch | Vector search and product data |
| Shopify | E-commerce platform |
| Radix UI | UI primitives |
| Zustand | State management |
| Turborepo | Monorepo build system |
| Storybook | Component library |
| Playwright | E2E testing |
| Vercel | Deployment and feature flags |

## Getting Started

```bash
# Install dependencies
yarn install

# Start development server
yarn dev

# Build for production
yarn build

# Run tests
yarn test

# Run E2E tests
yarn e2e
```

## Author

Developed by **Ihor Yanchuk**
[Portfolio](https://github.com/Vergos1) · [GitHub](https://github.com/Vergos1)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
