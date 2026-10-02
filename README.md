# WB Websites - Admin scaffold

This workspace contains a static site. I added a minimal admin panel under `admin/` which uses `localStorage` for data and a simple static password flow (demo only).

Files added:
- admin/login.html — login page
- admin/index.html — dashboard
- admin/users.html — user CRUD
- admin/content.html — simple content editor
- admin/admin.css, admin/admin.js — styles and logic

Default demo admin password: `admin123` (change by setting `admin_pass` in `localStorage`).

To use locally: open `admin/login.html` in the browser, sign in with the demo password, and use the dashboard.
