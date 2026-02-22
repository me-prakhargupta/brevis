# Brevis

> A minimalist, privacy-first platform designed for emotional expression and quiet release.

**Live Demo:** https://brevis-five.vercel.app/

---

## Table of Contents

- [Philosophy](#philosophy)
- [System Architecture](#system-architecture)
- [Repositories](#repositories)
  - [Frontend — brevis-client](#frontend--brevis-client)
  - [Backend — brevis-server](#backend--brevis-server)
- [Design Principles](#design-principles)
- [Key Highlights](#key-highlights)
- [Future Scope](#future-scope)
- [Why Brevis?](#why-brevis)
- [Author](#author)
- [Note](#note)

---

## Philosophy

Brevis is not a social platform.

It is a quiet digital space built for moments when thoughts don't need validation, structure, or an audience — just release.

- Express freely, without pressure
- No identity, no performance
- Let thoughts exist, and let them go

---

## System Architecture

```
Client (Next.js - TypeScript)
         ↓
REST API (Node.js - TypeScript)
         ↓
    Database
```

Brevis is built as a **decoupled full-stack system**, where the frontend and backend operate as independent services.

---

## Repositories

### Frontend — brevis-client

https://github.com/me-prakhargupta/brevis-client

- Next.js (App Router)
- TypeScript
- Tailwind CSS
- Minimal, distraction-free UI

---

### Backend — brevis-server

https://github.com/me-prakhargupta/brevis-server

- Node.js (TypeScript)
- REST API architecture
- Handles core data flow and business logic

---

## Design Principles

- **Privacy-first**  
  No identity binding or user profiling

- **Low-friction interaction**  
  Users can express instantly without onboarding barriers

- **Non-performative experience**  
  No likes, comments, or engagement loops

- **Minimal interface**  
  Designed to reduce cognitive load and distractions

---

## Key Highlights

- Full-stack architecture with clear separation of concerns
- Built using modern technologies (Next.js + Node.js + TypeScript)
- Designed with strong product thinking, not just feature implementation
- Deployed and accessible as a live system

---

## Future Scope

- Ephemeral content (auto-expiry of fragments)
- Enhanced privacy mechanisms
- Improved emotional UX design patterns
- Scalable backend infrastructure

---

## Why Brevis?

Most platforms optimize for attention and engagement.

Brevis explores a different direction:

> Expression without pressure, and presence without performance.

---

## Author

**Prakhar Gupta**  
Full-Stack Developer (Next.js, Node.js, TypeScript)  
Focused on building backend-driven, production-grade web applications.

---

## Note

This repository serves as the **central entry point** for the Brevis system, linking all services and providing architectural context.
