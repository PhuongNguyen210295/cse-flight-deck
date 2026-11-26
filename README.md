# CSE Flight Deck

A study and career planner for the University of Louisville Computer Science & Engineering BS.

- **Flight plan**: track every course (Planned, In progress, Done), with grades and GPA. Import the real flight plan by pasting it from the UofL catalog.
- **Study**: concept checklists and flashcard drills for 18 core CS, math and physics topics.
- **Career**: career paths, skills, portfolio projects, a year-by-year checklist and interview prep.
- **Focus timer**: a study timer that logs time per course.

## Install on Android

Download **CSE-Flight-Deck.apk** from the [latest release](../../releases/latest) on your phone and open it.
Android asks you to allow installs from your browser or Files app the first time.

## Use on the web

https://phuongnguyen210295.github.io/cse-flight-deck/ works offline after the first visit.
In Chrome, use the menu, then **Add to Home screen** (or **Install app**).

Progress is saved on the device you use (the app and the website each keep their own copy).

## How the Android build works

`app/` is a Capacitor project that wraps `index.html`. Every push to `main` that changes the app runs
`.github/workflows/android.yml`, which builds the APK and publishes it as a new GitHub release.