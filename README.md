# Tuition Scheduler

A single-file offline web app for private tutors to manage weekly student schedules, track attendance, and calculate revenue.

## Features

- **Student management** — add students with subject, hourly rate, session duration, and weekly schedule
- **Weekly calendar** — view all sessions in a 7-day grid, navigate between weeks
- **Attendance tracking** — click any session to mark as Attended / Cancelled / Pending
- **Analytics** — attendance rate per student with visual progress bar
- **Revenue overview** — weekly and monthly earnings per student and totals
- **Excel export** — download current week's sessions as `.xlsx` (student name, date, day, hours, cost)
- **JSON backup/restore** — export and import all data including attendance records

## Usage

Open `index.html` in any browser. No server, no install required. All data is stored in the browser's `localStorage`.

## Works on iPhone

Add to iPhone home screen via Safari → Share → Add to Home Screen for a native-like experience.
