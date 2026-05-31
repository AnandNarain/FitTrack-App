# 💪 FitTrack

A personal fitness tracking PWA built for serious training.
No ads. No login. No subscription. Fully offline after first load.

## What it does

**Workout Tracking**
- Pre-loaded 6-day PPL split (Legs → Push → Pull × 2)
- Log sets, reps, and weight per exercise
- Previous session numbers shown side-by-side for progressive overload
- Automatic PR detection — alerts when you beat a personal record
- Add or delete sets mid-session
- Full workout history with edit and delete

**Nutrition Logging**
- Daily calorie and macro tracking (protein, carbs, fat)
- 40+ common Indian and international foods built-in
- Custom food builder for home-cooked meals
- Organised by meal sections (Breakfast, Lunch, Dinner, Pre/Post-Workout)
- Edit or delete any logged item
- Drag to reorder meal sections
- Visual calorie ring and macro progress bars

**Body Measurements**
- Log 15 measurements: weight, body fat %, neck, shoulders,
  chest, waist, hips, both arms, forearms, thighs, and calves
- Tracks change vs previous entry with directional indicators
- Full history with edit and delete

**Dashboard**
- Daily macro summary at a glance
- Training streak counter
- Weekly session count
- BMI with health category
- Auto-calculated calorie and macro targets on setup
  (Mifflin-St Jeor equation based on your stats and goal)

## Tech
- Single HTML file — no frameworks, no build tools, no dependencies
- localStorage for persistent data
- Service Worker for full offline support
- PWA installable — add to home screen from Chrome (Android)
  or Safari (iPhone) for a native app experience
- System fonts — zero external requests, loads instantly

## Install on your phone
1. Open the GitHub Pages URL in Chrome (Android) or Safari (iPhone)
2. Android: tap ⋮ menu → Add to Home Screen
3. iPhone: tap Share → Add to Home Screen
4. Opens fullscreen like a native app, works offline

## Versioning
Each update committed to this repo is a new version.
GitHub Pages auto-deploys within ~2 minutes of each commit.
