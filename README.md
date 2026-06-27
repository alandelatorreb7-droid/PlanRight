# PlanRight

A single-file construction project timeline planner for contractors. Lay out
sequential build phases, see a live horizontal Gantt chart with the projected
finish date, and export a clean, professional PDF to share with clients.

## Features

- **Sequential scheduling** — each phase starts the day after the previous ends;
  dates recompute live as you edit.
- **Editable phases** — pre-filled with a standard residential build sequence;
  rename, re-time, add, or remove any phase.
- **Dashboard UI** — sidebar navigation (Overview / Schedule / Reports), stat
  tiles, and a prominent projected-finish badge.
- **Visual Gantt chart** — pastel color-coded bars on a dated timeline with
  gridlines and full, never-truncated phase labels.
- **Professional PDF export** — branded header (project name, type, start date,
  crew size, finish date), the visual Gantt, a phase summary table, and a footer.
  Tables are never split mid-row across pages.

## Usage

Open `index.html` in any modern browser. No build step, no backend.

## Tech

Plain HTML + CSS + JavaScript in one file. PDF export uses
[html2canvas](https://html2canvas.hertzen.com/) and
[jsPDF](https://github.com/parallax/jsPDF) via CDN. Typography uses Inter.
