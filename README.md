# The Daily Reset — 30-Day Exercise & Diet Journey

A lightweight, responsive habit tracker for building consistent exercise and nutrition routines over 30 days. It runs as a standalone HTML page, with no build step, framework, database, or account required.

## Features

- **30-day progressive journey** with four phases: Foundation, Build the Rhythm, Get Stronger, and Own Your Routine.
- **Daily exercise checklist** with movement, strength, mobility, and recovery guidance.
- **Daily diet checklist** focused on balanced meals, protein sources, fruit and vegetables, whole grains, hydration, and mindful choices.
- **Progress dashboard** with journey progress, habit completion, completed days, streak, and recent average.
- **Interactive 30-day map** for opening previous dates and reviewing or correcting saved check-ins.
- **Short daily reflection** to record energy and a meaningful observation.
- **Weekly reviews** to reflect on what worked and what to improve.
- **Automatic local saving** in the browser using `localStorage`.
- **JSON backup export/import** for backing up or restoring tracker data.
- **Dark and light themes**.
- **Responsive layout** for desktop and mobile.
- **Research links** included in the page.

## Getting started

### Option 1: Open the HTML file

1. Download or clone the project files.
2. Open `30-day-exercise-diet-journey.html` in a modern browser.
3. Set or confirm the journey start date if prompted.
4. Complete the daily exercise and diet tasks.
5. Your progress saves automatically in that browser.

There is no dependency installation or build command.

### Option 2: Serve it locally

You can use any static file server. For example, with Python installed:

```bash
python -m http.server 8000
```

Run that command from the directory containing the HTML file, then open:

```text
http://localhost:8000/30-day-exercise-diet-journey.html
```

## How to use the tracker

1. **Start your journey.** Choose the date from which your 30-day plan should run.
2. **Check off daily habits.** Use the exercise and diet lists to track the actions you complete.
3. **Review progress.** Journey progress measures the timeline; habit completion measures the tasks completed.
4. **Review earlier days.** Select a date in the 30-day map to view or correct its saved checklist and reflection. Use the return-to-today control to go back to the current date.
5. **Reflect briefly.** Record your energy and a short note about the day.
6. **Review weekly.** Capture what worked and what you want to improve.
7. **Back up your data.** Export a JSON backup periodically. Import a backup to restore the data in a compatible copy of the tracker.

## Data and privacy

- The tracker stores progress in the browser's `localStorage` on the device and browser where you use it.
- The standalone page does not require an account or application server.
- Browser data may be lost if site data is cleared, the browser profile is removed, or you switch browsers/devices.
- Use the built-in JSON export to keep a backup. Store exported files somewhere private because they may contain personal reflections.
- If you host the page on a website, browser storage is associated with that site's origin. A local file and a hosted website may not share the same saved data.

## Technical details

- **Format:** Single-page HTML application.
- **Frontend:** HTML, CSS, and vanilla JavaScript.
- **Persistence:** Browser `localStorage`.
- **Backup format:** JSON.
- **External runtime dependencies:** None required to run the tracker itself.
- **Hosting:** Any static hosting provider that can serve HTML files.

## Troubleshooting

### My progress disappeared

Check that you are using the same browser and profile, and that browser/site data was not cleared. If you previously exported a backup, use the import feature to restore it.

### I want to move progress to another device

Export a JSON backup from the original browser, transfer the file securely, open the tracker on the other device, and import the backup.

### I changed the journey start date

Changing the start date can affect how dates map to the journey. Export a backup before making substantial changes if you want to preserve a restore point.

### The page does not save progress

Ensure browser storage is enabled and that the browser is not running in a restrictive private session. Try a current version of Chrome, Firefox, Edge, or Safari.

## Health and safety note

This tracker is for general habit-building and is not a personalized exercise prescription or medical advice. Adjust activity to your current fitness, take recovery days, and seek qualified medical guidance if you have health concerns or are unsure which activities are appropriate for you.

## Project structure

```text
.
├── 30-day-exercise-diet-journey.html
└── README.md
```

## License

No license is specified by this README. Add a `LICENSE` file before distributing the project if you want to grant others explicit reuse rights.
