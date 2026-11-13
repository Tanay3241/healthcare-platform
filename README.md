# healthcare-platform
# PranaCare – Centralized Healthcare Management Platform

A modern, animated, responsive healthcare SaaS front end built for the **AI Animation & Motion Graphics Intern** assignment at Algomindz Solutions Pvt. Ltd.

**Live demo:** https://tanay3241.github.io/healthcare-platform/

No backend, API or database. All data is static dummy data.

## Modules

1. Centralized patient profiles (vitals, contact, care team)
2. Medical history management (timeline)
3. Medical report management (filters and preview popup)
4. Consultation records (expandable notes)
5. Personalized nutrition plans (macro rings and day-wise meals)
6. Yoga and wellness progress tracking (streak, weekly chart, breathing circle)
7. Secure role-based access for Admin, Doctor, Patient, Nutritionist and Yoga Instructor

## Roles

Pick a role on the sign-in screen. Each role sees only the modules it is allowed to use, and the Admin view includes a permission matrix.

| Role | Modules |
|---|---|
| Admin | Dashboard, Profile, Role Access |
| Doctor | Dashboard, Profile, History, Reports, Consultations |
| Patient | Everything except Role Access |
| Nutritionist | Dashboard, Profile, Nutrition |
| Yoga Instructor | Dashboard, Profile, Yoga |

## Animations and UX

- Animated ECG line and heartbeat logo on the sign-in screen
- Count-up statistics on the dashboard
- Animated progress rings and growing bar charts
- Breathing-circle animation in the yoga module
- Smooth view transitions, hover feedback and modal previews
- Back button, light and dark mode toggle
- Responsive layout for desktop, tablet and mobile
- Respects `prefers-reduced-motion`

## Tech

HTML, CSS and vanilla JavaScript in a single `index.html` file. No build step.

## Run locally

Download `index.html` and open it in any modern browser.

## Author

Tanay
