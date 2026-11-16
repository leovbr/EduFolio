# EduFolio

Premium navy digital workspace for students and university students to build digital portfolios and (later) presentations.

## Current demo scope
- Responsive landing page
- Local browser demo registration and login
- Dashboard overview
- Portfolio builder with live preview
- LocalStorage persistence per browser
- Custom services information page

## Run
Open `index.html` in a browser, or enable GitHub Pages from **Settings → Pages → Deploy from a branch → main / root**.

## Demo limitations
- Data stays in the current browser/device. It does not sync between devices.
- Demo authentication is not secure. Passwords are stored in LocalStorage in plain text. Do not use real credentials.
- No backend, Supabase, payment gateway, file uploads, or public portfolio publishing yet.
- Presentation builder and admin panel are planned for later phases.

## Roadmap
1. [x] Landing and navigation
2. [x] Demo auth and LocalStorage foundation
3. [x] Dashboard and portfolio builder MVP
4. [ ] Portfolio themes and public share page
5. [ ] Presentation builder
6. [ ] Supabase Auth + database + RLS
7. [ ] Orders, payment integration, and admin workspace

## Structure
```
index.html
login.html
register.html
services.html
dashboard/
  index.html
  portfolio.html
css/style.css
js/app.js
js/dashboard.js
```
