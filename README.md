# Rehearsal Scheduler

Web application for music industry professionals to schedule band rehearsals, automatically send reminders, track attendance, and suggest optimal rehearsal times.

## Features
- Easy web scheduling for bands and individuals
- Book and manage rooms, equipment, and staff
- Online payments and invoices
- Automated reminders (email/SMS) and Google/iCal sync
- Recurring bookings, attendance tracking, analytics
- Role-based access (admin, band leader, member, guest)
- Mobile-responsive UI
- Secure account management

## Tech Stack
- Front-end: ReactJS, HTML5, CSS3
- Back-end: Node.js/Express
- Database: PostgreSQL
- Calendar + Notification APIs
- Deploy: Docker, GitHub Actions, Render.com or Heroku

## Setup
1. Clone this repo
2. Install dependencies with `npm install`
3. Set up `.env` for DB and API keys
4. Run migrations and start local server: `npm run migrate && npm start`

## Deployment
Configure Docker and CI/CD via GitHub Actions. See project plan for details.

## Documentation
Project plan: https://docs.google.com/document/d/1qPEa6zsIBHuU_-WIcpp0On0JuhqnYgr_rH3PlI7Pl8A

Tracking sheet: https://docs.google.com/spreadsheets/d/12EOrUAqwfbmXmExR7tyt5v47hdE3myUgxdHRsaRJ5YM

## Notes
Prioritize security for user data and financial operations.