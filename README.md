# Socio — Event Management & Discovery Platform (Portfolio Demo)

This is a **sanitized portfolio demo** of my solo internship project at **Socio**.  
All proprietary code has been removed for confidentiality. This repository contains only a project structure and documentation of the system I developed.

---

## Project Overview
**Socio** is a full-stack web application designed as a **college campus event management and discovery platform**.  
It allows students to discover upcoming events, register individually, and view their profiles.  
Admins can securely manage events with full **CRUD functionality** and participant management.

---

## Tech Stack
### Frontend
- **Next.js 15** with **React 19**
- **TypeScript**
- **TailwindCSS** (modern utility-first styling)
- **react-hook-form + zod** (form handling + validation)
- **GSAP** (smooth animations)
- **Sonner** (toast notifications)

### Backend
- **Express.js 5** (Node.js framework)
- **Supabase** (Postgres DB + Auth)
- **multer** (file uploads)
- **exceljs** (Excel export/import)
- **node-cron** (scheduled jobs)
- **dotenv, cors, nodemon** (security + dev tools)

---

## Core Features

### User-Facing
- Secure **authentication** (Supabase Auth + JWT)  
- **Event discovery page** with filters & search  
- **Event detail view** with description, time, location  
- **Individual registration** (with validation + confirmation)  
- **Profile page** showing registered events  

### Admin-Facing
- Role-based **admin dashboard**  
- Full **CRUD operations** for events & fests  
- **View participants** list per event  
- **Export participants to Excel**  
- **Bulk upload events via Excel**  

---

## My Solo Contributions
I independently designed and developed the complete system:  
- **Frontend (Next.js + TypeScript)**: Built responsive UI, event discovery, detail pages, and admin dashboards.  
- **Authentication**: Implemented Supabase authentication with route protection and role-based access control.  
- **Backend APIs (Express.js)**: Designed REST APIs for events, registrations, and participants.  
- **Database Schema**: Structured relational data in Supabase (events, users, registrations).  
- **Admin Tools**: Added Excel import/export (exceljs) and file upload (multer).  
- **Automation**: Implemented scheduled tasks with node-cron.  
- **UI/UX**: Added GSAP animations and Tailwind styling for modern look & feel.  
