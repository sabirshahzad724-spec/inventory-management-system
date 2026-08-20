# INVENTRA — Inventory Management System

Premium showcase-ready inventory management project for the MUIT Diploma Computer Science 5th Semester minor project.

## Team
- Sabir Shahzad
- Syed Ammar
- MD Mujahid Ul Islam
- Adnan Ul Haque

## Important: No database
This edition intentionally uses **no MySQL, SQLite, Flask, Node, npm, or backend server**. All application data is stored in the browser with `localStorage`. This makes it ideal for a zero-setup classroom showcase.

## Run
### Easiest
Double-click `index.html` and open it in Chrome/Edge.

### Recommended in VS Code
Install the VS Code **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.

No installation, terminal, database, or environment variables are required.

## Demo accounts
- Admin: `admin@inventra.local` / `Admin@123`
- Manager: `manager@inventra.local` / `Manager@123`
- Staff: `staff@inventra.local` / `Staff@123`
- Viewer: `viewer@inventra.local` / `Viewer@123`

## Role behavior
- **ADMIN:** full access + user management
- **MANAGER:** inventory CRUD + removals + log controls
- **STAFF:** operational write actions
- **VIEWER:** read-only showcase access

## Included
Dashboard, products, categories, suppliers, customers, receive stock, sales, inventory audit log, multi-user login, role-based UI controls, responsive mobile navigation, local persistence, toast feedback, search/filtering, and a six-slide web presentation.

## Reset demo data
Open browser DevTools Console and run:
```js
localStorage.removeItem('inventra_showcase_v1'); location.reload();
```
