Hi 👋, I'm Ammar Bin Yasir

Full Stack Web Developer (Aspiring) | BS Computer Science Student | WordPress Developer | Digital Marketer

I'm a BS Computer Science (4th Semester Completed) student at the University of Central Punjab (UCP), Gujrat Campus, Pakistan. Alongside my studies, I am completing an internship at Nexus Future, where I continue to improve my practical skills.

My goal is to become a professional Full Stack Web Developer after graduation. I enjoy building web applications, solving programming problems, creating WordPress websites, and working on SEO-driven content.

🚀 About Me

- 🎓 BS Computer Science Student at UCP Gujrat Campus
- 💼 Intern at Nexus Future
- 🌐 WordPress Developer
- 📱 Social Media Manager
- 📈 Digital Marketing & SEO Enthusiast
- ✍️ Professional Article Writer using Google Trending Keywords
- 🎯 Goal: Become a Full Stack Web Developer

💻 Technical Skills

- HTML5
- CSS3
- C++
- Python
- SQL (Database)
- WordPress (Customization)
- SEO
- AEO (Answer Engine Optimization)
- Google Trends Research
- Microsoft Word
- Microsoft Excel
- Microsoft PowerPoint
- Meta Digital Marketing
- Data Analytics

📂 Projects

🌍 Smart Online Converter
{CABYG SUITES & INN

Hotel Management & Booking System

Final Project Documentation — Phases 1–10

1. Project Overview

CABYG Suites & Inn is a Laravel-based hotel/guest-house management and booking system designed for a hotel property in Gujrat, Pakistan. The system combines a public-facing hotel website with secure staff management, reservations, room operations, financial records, housekeeping, maintenance, reviews, notifications, audit logging, and role-based access control.

2. Project Objectives

Provide a professional public hotel website for browsing rooms, amenities, reviews, contact information, and booking entry points.

Manage the hotel's 18 physical rooms and their room types, images, amenities, pricing, and operational status.

Provide secure staff authentication and least-privilege role-based access control.

Manage guests, reservations, room availability/locks, cancellations, invoices, payments, and refunds.

Support housekeeping and maintenance workflows with staff assignment and auditability.

Provide review and communication/notification capabilities.

Maintain an auditable, secure, relational MySQL data model using Laravel Eloquent.

3. Technology Stack

Laravel 12.x

PHP 8.2.x

MySQL

Laravel Eloquent ORM

Blade templating

HTML5 / CSS3 / JavaScript

Tailwind CSS

Vite

Git / GitHub

Laravel-native session authentication, Gates/Policies, middleware and rate limiting

4. Major Functional Requirements

Public Website: Home page, rooms catalog, room details, amenities, contact page, reviews and booking entry points.

Room Management: 18 physical rooms, room types, room images, amenities, room status and operational room overview.

Rate & Pricing: Rate plans, prices, cancellation policies and pricing-related configuration.

Guest Management: Guest records and CRM-oriented guest information used by reservation workflows.

Booking Management: Reservation creation/update/cancellation, room assignment and room-night locking to protect availability.

Financial Management: Invoices, invoice items, payments, refunds and financial summaries.

Housekeeping: Cleaning task creation, assignment, status progression, room turnover and operational visibility.

Maintenance: Maintenance tickets, technician assignment, status progression and append-only event/work history.

Reviews: Guest review submission and moderation-oriented review workflow.

Notifications: Internal operational notifications and notification records.

Authentication & RBAC: Secure staff login/logout, password hashing, rate limiting, session security and role/permission authorization.

Auditability: Structured audit log records for important staff and operational actions.

5. Hotel Inventory

Total physical rooms: 18

Standard Executive — 4 rooms (101–104)

Deluxe King Room — 7 rooms (201–207)

Executive Twin Room — 4 rooms (301–304)

CABYG Family Suite — 3 rooms (401–403)

6. Staff Roles & Access Control

Super Admin / Owner: Full administration, staff, roles, permissions, settings, operational, financial and audit access.

Manager: Operational management including rooms, bookings, housekeeping/maintenance visibility, invoices and reports; no unrestricted security/permission administration.

Receptionist: Front-desk booking and room-view permissions; no system/security administration or financial administration.

Housekeeping: Housekeeping operations and room viewing only; no financial, maintenance or system administration.

Maintenance: Maintenance operations and room viewing only; no financial, housekeeping or system administration.

7. Permission Design

users.view / users.create / users.update / users.delete

roles.view / roles.create / roles.update / roles.delete

permissions.view / permissions.assign

hotel_settings.view / hotel_settings.update

rooms.view / rooms.manage

housekeeping.view / housekeeping.manage

maintenance.view / maintenance.manage

bookings.view / bookings.create / bookings.update / bookings.cancel

payments.view / payments.manage

invoices.view / invoices.manage

reports.view

audit_logs.view

8. Security Requirements Implemented

Passwords are stored using Laravel's secure password hashing; plaintext passwords are not stored.

CSRF protection remains enabled for state-changing web requests.

Login attempts are rate limited.

Sessions are regenerated on successful login to reduce session-fixation risk.

Logout invalidates the session and regenerates the CSRF token.

Authentication middleware protects staff routes.

Role and permission middleware/Gates enforce authorization server-side.

Direct URL access by unauthorized roles is blocked with proper authorization responses.

Least-privilege access is applied across staff roles.

.env and other secrets are excluded from Git.

9. UI / Theme Requirements

Modern, professional luxury-hotel visual identity.

Dark slate/charcoal foundation with amber/gold accent styling.

Clean Inter-style typography and strong visual hierarchy.

Responsive layouts for desktop, tablet and mobile devices.

Professional hotel room cards and image galleries.

Clear room availability/status indicators.

Clean booking and reservation interfaces.

Role-specific dashboards for administration and operations.

Consistent forms, tables, filters, status badges and action controls.

Tailwind CSS-based styling without introducing React, Next.js or another frontend framework.

10. Database Architecture

The project uses a relational MySQL architecture with Laravel migrations, foreign keys, indexes and Eloquent relationships. The approved architecture includes hotel-domain tables for users, roles, permissions, guests, room types, rooms, images, amenities, cancellation policies, rate plans/prices, taxes/charges, coupons, bookings, room assignments/locks, services/add-ons, invoices, payments, refunds, housekeeping, maintenance, reviews, notifications, enquiries, audit logs and hotel settings, together with standard Laravel infrastructure tables.

11. Phase 1–10 Development Scope

Phase 1: Laravel/PHP/MySQL foundation, project configuration, Git foundation, Tailwind/Vite and environment verification.

Phase 2A: Approved hotel database architecture, migrations, relationships and 18-room seed inventory.

Phase 2B: Staff authentication and native RBAC using existing roles, permissions and pivot tables.

Phase 3: Room inventory/catalog, room types, amenities and room image/gallery functionality.

Phase 4: Rate plans, pricing matrix and cancellation policy functionality.

Phase 5: Guest CRM, reservation creation, room locks and cancellation workflows.

Phase 6: Invoices, invoice items, payments, refunds and financial summaries.

Phase 7: Housekeeping and maintenance management, task/ticket workflows, assignments and audit events.

Phase 8: Guest reviews, communication/notification records and operational notification functionality.

Phase 9: Integrated application functionality and supporting management/public-site features completed across the project scope.

Phase 10: Final UI/security audit, production-readiness verification and final application completion.

12. Validation & Quality Assurance

Application functionality was tested across the completed project phases.

Authentication, authorization and direct URL access were tested for role boundaries.

Database integrity and room inventory were repeatedly verified during phase completion.

Git history was preserved without rebase/amend/history rewriting.

The final project was prepared for GitHub source-code submission.

The .env file is excluded from source-code submission; .env.example is provided for environment configuration.

13. Submission Package

Complete Laravel source code ZIP.

README/project documentation.

GitHub repository containing the source code.

.env.example for safe environment setup.

No .env file or production secrets.

14. Developer Setup Notes

To reconstruct the project on another development machine, install the required PHP/Laravel and MySQL environment, copy .env.example to .env, configure the local database credentials, install Composer and Node dependencies, generate the application key where required, run the approved migrations/seeders for a fresh development environment, and build the Vite assets. The actual submission ZIP must not contain the original environment secrets.

15. Final Project Status

CABYG Suites & Inn is documented as a completed Phase 1–10 Laravel hotel management and booking project, with a public-source GitHub repository prepared for academic submission. Further deployment or hosting is a separate infrastructure task and does not change the submitted source code.

16. Source Repository

GitHub: https://github.com/ammaryasir308-cmd/cabyg-suites-inn

Technologies: C++ (OOP)

Developed a smart converter with a team that included:

- Currency Converter
- Temperature Converter
- Unit Converter
- Multiple real-world conversion tools

🗄️ Database Management System

Technologies: SQL

Designed and managed a database system for storing and organizing records using SQL.

🏆 Certifications

- Meta Digital Marketing
- Data Analytics
- IOSH – Health & Safety
- OSHA – Occupational Health & Safety

🎯 Career Objective

I am continuously improving my development skills and currently focusing on frontend technologies while learning backend development to become a professional Full Stack Web Developer.

📫 Contact
phone number:03086093046
📧 Email: ammargujjar0308@gmail.com
LinkedIn: Ammar Bin Yasir 
📍 Gujrat, Punjab, Pakistan

---

⭐ "Learning every day, building every day, and growing into a professional software developer."
