# MOMstrong Workout app

**Version 1.0 — completed 2026-07-27**

A single-file, offline-first workout tracker built for fitting real strength training into short bursts of free time.

**How it works:** each day a random workout list is generated from a built-in library of exercise and stretching modules--one module per muscle group. Each module has a rep and weight/time tracker as well as a difficulty tracker, with auto generated suggestions  built on the previous time it was done and suggested increases/decreases based on recorded difficulty. 

**Muscle groups**
13 total: chest, back, shoulders, biceps, triceps, core, glutes, quads, hamstrings, calves, neck & upper back, hip flexors, and pelvic floor/deep core

**Features**
- Adaptive progression: rate a set "way too easy" → "way too hard" which adjusts the suggested weight/rep/time for the next time the module is listed
- Band-aware suggestions once you rank your resistance bands easiest → hardest in Settings
- Quick-log top strip for stairs completed, steps walked, and minutes of yoga completed
- Built-in stretch timers and one-tap YouTube how-to links for every module
- Calendar tab (history by day) and Stats tab (per-muscle graphs)
- Editable Library tab — hide/rename exercises, adjust cues, add youtube search terms
- JSON export/import for backups (iOS can clear in-browser storage, so history isn't stored in the HTML file itself)
- randomized order enables broad muscle targetting over time by ensuring the first excercise/stretch seen (and thus the one that might be the easiest to do given very short amount of time) will vary. 
- automated adaptation of list to move completed exercises to the bottom, reducing clutter when trying to decide on the next move. 

**Tech:** HTML, no dependencies or build step. Data lives in `localStorage` on-device — no syncing or internet connection required. Designed to run inside Readdle Documents app.

**Setup:** see `SETUP.md` 
