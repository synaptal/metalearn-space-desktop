# MetaLearn Space — Desktop

Learn faster in 3D spaces. Courses, interactive labs, an AI tutor, and community — in one desktop-first learning space built for deep focus.

This repo currently contains the marketing / download landing page for the MetaLearn Space desktop app (macOS · Windows · Linux).

Live page: `index.html` (single file, no build step).

## Features

- **Interactive 3D Spaces** — walk through physics, anatomy, or data structures as living scenes
- **AI Tutor** — hints, explanations, and code reviews grounded in the current lesson
- **Labs & Projects** — real sandboxes with tests and instant feedback
- **Progress Analytics** — streaks, mastery maps, weekly goals
- **Community Spaces** — study rooms, challenges, peer review
- **Offline Desktop Sync** — desktop-first, works offline, syncs when back online

## Repo contents

- `index.html` — full landing page (nav, hero + app mock, features, how-it-works, OS-aware download section, footer)
- No dependencies to install, no bundler. Tailwind via CDN, fonts via Google Fonts.

## Run locally

Just open the file:

```bash
open index.html
```

Or serve it (avoids `file://` quirks):

```bash
npx serve .
# or
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Download the app

Desktop builds are published on [GitHub Releases](../../releases). The download section in `index.html` auto-resolves the latest release asset per OS (macOS `.dmg`, Windows `.exe`/`.msi`, Linux `.AppImage`/`.deb`) via the GitHub Releases API. No build is published yet — watch the repo to get notified.

## Status

In active development. Free during beta, open source, offline-first.
