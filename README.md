# scholarms-interstellar_
# ScholarMS: Student Scholarship Management System

IMS566 Advanced Web Design Development and Content Management, Individual Project.

A front-end web application where students apply for scholarships and track the result, while the scholarship office reviews, approves and analyses applications.

## Features
- **Authentication**: login and student registration, clear error messages, show/hide password, 30-second cool-down after 3 failed logins (simulated with hardcoded users and browser storage).
- **Role-based access**: Student, Scholarship Officer and Administrator each see a different menu and different actions.
- **Dashboard** (staff): animated KPI cards, a plain-language insight, four Chart.js charts (status, monthly trend, per-scholarship demand or funds, faculty), quota progress bars and an activity log. Clicking a status slice opens the matching applicants.
- **Data views**: Scholarships (cards, eligibility checker, apply), Applicants (search, filter, sort, pagination, detail panel, CSV export) and My Applications (student only, withdraw while pending).
- **Quick menu**: press `Ctrl+K` to jump to any page. Press `/` on Applicants to search.
- **"Endurance" design (Interstellar-inspired)**: a rendered black hole with a lensed amber accretion disk, a slow starfield and a tiny ring-shaped spacecraft drifting past. Near-black panels with hairline borders and HUD corner marks, ivory type, amber accents, Jost headings and IBM Plex Mono instrument labels.
- **Orbit gauges**: each scholarship shows its quota as a body travelling round an orbit.
- **Calm sky**: a navbar button (or the quick menu) freezes and dims the sky for comfortable reading.
- **Dark ("Endurance") and light ("Dust", warm paper) themes**, responsive layout, skip link, keyboard focus styles, reduced-motion support.
- **Content management**: titles, meta descriptions, semantic sections and a shared navbar/footer rendered from one script.

## Test the login
| Role | Username | Password | Lands on |
|---|---|---|---|
| Student | `student` | `student123` | Scholarships |
| Officer | `officer` | `officer123` | Dashboard |
| Administrator | `admin` | `admin123` | Dashboard |

Administrators can approve, reject and delete (approving fires confetti). Use "Reset demo data" in the account menu to restore the sample data.

## Frameworks and libraries
Bootstrap 5.3, Bootstrap Icons, Chart.js 4. Plain JavaScript, no build step.

## Run locally / deploy
Open `index.html` in Chrome, or publish the repository root with GitHub Pages.
