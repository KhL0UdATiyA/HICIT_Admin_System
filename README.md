HICIT Academic Management System

A front-end prototype of an integrated academic administration dashboard for HICIT. It is a right-to-left (Arabic) interface, designed for desktop, and organized around six areas:

Dashboard: an overview of the institute plus an institute profile.
Academic Setup: academic regulations, scientific departments, and a global course catalog.
System Members: faculty and teaching assistants, and staff with role-based permissions (RBAC).
Students & Cohorts: cohort and student onboarding, academic status tracking and overrides, and promotion and department branching.
Term Operations: course offerings and scheduling, teaching load, and registration and overrides.
Control & Grading: instructor assessment entry (40% year work), a grade processing and rules engine, and verification, control locking and result publishing.

Tech: React 18, Tailwind CSS, Lucide icons, and Babel in the browser. There is no build step, and everything loads from CDNs.

Note: this is a design prototype. All data is demo data held in memory, so nothing is saved after a refresh. There is no backend.

Run locally: open the folder with VS Code and the Live Server extension, or host it on GitHub Pages. Opening index.html by double-click won’t work, so use merge.py if you need a single file. The Arabic guide in README-ar.md explains the file structure.

I only described what’s in the code. If the project has an official name or a purpose I don’t know about (for example a graduation project or a specific college), tell me and I’ll adjust the wording. I can also add this text to the project as a README.md so it appears on the repo’s front page.
