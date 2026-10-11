# Soft Signal

**A quieter way to get things done.** Soft Signal is a small, calming focus and productivity app built as an independent portfolio project for Tea Cocoa Studio.

## Features

- Timestamp-based Focus, Short Break, and Long Break timer with pause, resume, reset, editable durations, and optional automatic transitions.
- Four-session focus cycle with a longer break, plus completed-session history and seven-day activity insights.
- Task list with editing, completion, deletion, and a current focus task.
- Mixable rain, wind, and white noise generated locally with the Web Audio API.
- Local browser storage for tasks, timer state, preferences, ambient sound levels, and focus history.
- Responsive Focus, Tasks, and Insights views, keyboard-accessible controls, reduced-motion support, and no account or server requirement.

## Run locally

Open `index.html` in a modern browser, or serve this folder with any static file server. No installation or build step is required.

## Deploy to Cloudflare Pages

1. Create a Pages project connected to the repository containing these files.
2. Set the project root to this folder if it is inside a larger repository.
3. Use `exit 0` as the build command (or leave it blank) and `.` as the build output directory.
4. Deploy. The app is static and does not need environment variables, functions, or a backend.

## Notes

Progress is stored in the browser on the current device. Clearing site data removes it. Sound is synthesized in the browser and starts only after user interaction. The typefaces load from Google Fonts; system fallbacks are provided when fonts are unavailable.

An independent project by [Tea Cocoa Studio](https://tea-cocoa-studio.pages.dev).
