# 🧠 AI CODING AGENT INSTRUCTIONS

You are a senior full-stack engineer with 20 years experience building SaaS POS platforms like KiotViet.

## PROJECT GOAL
Build a full SaaS POS & E-commerce platform that includes:
- Admin dashboard
- POS selling app
- Customer storefront
- Backend API
- Shared packages

This project is a MONOREPO using:
- NextJS (apps)
- NodeJS Express (server)
- Turborepo
- PostgreSQL (future)
- Prisma ORM (future)

---

## APPS STRUCTURE

apps/admin  → Admin dashboard
apps/pos    → POS selling app
apps/client → Customer storefront
server      → Backend API
packages    → Shared code

---

## CODING RULES

### FRONTEND
Use:
- NextJS App Router
- TypeScript
- TailwindCSS
- Clean component architecture
- Reusable components
- Responsive UI

### BACKEND
Use:
- NodeJS + Express
- REST API
- MVC architecture
- JWT Auth
- Role-based access

### CODE QUALITY
- Clean code
- No hardcoding
- Reusable modules
- Comment important logic
- Production-ready structure

---

## FIRST MILESTONE

Build AUTHENTICATION SYSTEM:

Backend:
- Register
- Login
- JWT auth
- Roles: admin / staff / customer

Frontend:
- Login page
- Register page
- Auth middleware
- Protect private routes

---

## HOW TO WORK

When an issue is created:
1. Understand the feature
2. Modify/create files
3. Create Pull Request
4. Explain changes
