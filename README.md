# Day's Ice Cream - Official Web Platform 🍦

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

> **Note:** The source code for this project is hosted in a private repository to protect the client's proprietary assets and secure backend architecture. This repository serves as a portfolio showcase of the tech stack, features, and engineering processes used to deliver the platform.

### 🌐 [Visit the Live Site: daysicecream.com](https://daysicecream.com)

---

## 📖 Project Overview

Day's Ice Cream is a historic, beloved local business in Ocean Grove, NJ, operating since 1876. They needed a modern, highly performant web presence that captured their vintage boutique aesthetic while providing them with robust, easy-to-use tools to manage their content internally.

I engineered a **bespoke, full-stack web application** from the ground up. By deliberately avoiding generic UI frameworks like Tailwind or Bootstrap, I developed a highly customized **Vanilla CSS Design System** to achieve pixel-perfect control over the site's unique typography, rich color palettes, and micro-animations.

To empower the business owners, I built a **custom administrative dashboard** powered by **Supabase**, allowing them to log in securely and dynamically update website content (like hours of operation, menu flavors, and contact details) without needing to write a single line of code.

## ⚡ Key Features

- **Custom Content Management System (CMS):** A fully integrated admin dashboard protected by Supabase Authentication. The client can edit text across the website in real-time.
- **Bespoke Design System:** Engineered a lightweight, scalable Vanilla CSS architecture. Features dynamic marquee animations, responsive typography (`clamp()`), and complex grid layouts.
- **Serverless Form Handling:** Integrated EmailJS for secure, instantaneous delivery of Customer Contact inquiries and Employment Applications directly to the client's inbox.
- **Edge-Network Performance:** Deployed on Vercel leveraging Next.js Server Components and advanced caching strategies for near-instant page loads.

## 🛠️ The Tech Stack

### Frontend Architecture
- **Framework:** Next.js (App Router)
- **Library:** React 18
- **Styling:** Vanilla CSS (Custom Design System, CSS Variables, Flexbox/Grid)
- **Forms:** Controlled React Components with custom regex validation

### Backend & Infrastructure
- **Database:** PostgreSQL (via Supabase)
- **Authentication:** Supabase Auth (Session-based Admin login)
- **Email Routing:** EmailJS Serverless API
- **Hosting & CI/CD:** Vercel

## 📸 Platform Highlights

### The Public Frontend
The user-facing website features a highly responsive layout tailored for mobile and desktop viewing. It utilizes a curated color palette and WebKit masking to seamlessly blend modern web standards with the brand's historic identity.

*(Insert a screenshot of the homepage here)*

### The Admin Dashboard
A secure, hidden route (`/admin`) allows authorized personnel to manage the PostgreSQL database. The dashboard provides a visual interface to update strings, toggle settings, and manage the extensive ice cream menu.

*(Insert a screenshot of the admin dashboard here)*

## 🚀 Engineering Challenges Solved

1. **State Hydration & Dynamic Content:** Ensured that content fetched from the Supabase database perfectly synced with Next.js Server Components without causing hydration mismatch errors on the client side.
2. **TypeScript Integration:** Implemented strict TypeScript interfaces across the entire application, bridging the gap between raw PostgreSQL database rows and heavily structured React UI components.
3. **Cross-Browser Styling:** Utilized advanced CSS techniques (like non-breaking spaces `\u00A0` for marquee timing and `clamp()` for fluid typography) to ensure the highly-stylized layout rendered flawlessly across Safari, Chrome, and Firefox on all device sizes.
