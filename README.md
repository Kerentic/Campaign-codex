# Campaign Codex

Campaign Codex is a full-stack web application designed to centralize tabletop RPG campaigns (D&D-style) into a single collaborative platform.

It provides campaign management, character sheets, and multi-perspective narrative logs, allowing players and Dungeon Masters to document, experience, and preserve their stories as a living system.

> This project is developed as part of **Kerentic Labs**, serving both as an internal R&D initiative and as a professional portfolio case study.

---

## 🎯 Goals

- Centralize campaign data (characters, sessions, logs)
- Support multiple perspectives of the same story
- Apply production-grade full-stack architecture
- Serve as a demonstrable portfolio project

---

## 🧱 Architecture Overview

- **Frontend**: Next.js (App Router) + TypeScript
- **Backend**: NestJS + TypeScript
- **Database**: PostgreSQL
- **ORM**: Prisma
- **Authentication**: OAuth / Magic Link (TBD)
- **Infrastructure**: Docker (local), Azure (cloud)

The project follows a **monorepo** structure to encourage shared contracts, consistent types, and scalable development.

---

## 🗂 Monorepo Structure

