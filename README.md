# Fly Box

A mobile-friendly fly fishing pattern database and fly box inventory tracker. Built as a single self-contained HTML file that runs anywhere with no server required.

## What It Does

**Pattern Database** -- 50+ fly patterns organized by hatch (BWO, PMD, Midge, Stonefly), with full recipes including hook, sizes, materials, colors, tying notes, and YouTube reference links.

**Fly Box Tracker** -- Mark which patterns you actually have tied, track quantities and specific sizes in your box, and quickly see what you're missing.

**On-the-Water Reference** -- Filter by hatch, fly style, season, and water conditions to narrow down what to tie on. Search by material or hook type to find patterns fast.

## Features

- Filter by hatch type, fly style (dry, emerger, nymph, jig, perdigon, wet fly), season, and water conditions
- "In My Box" / "Need to Tie" filtering to see inventory gaps
- Full material lists and tying video links for every pattern
- Add, edit, and delete patterns
- Grid and list view modes
- All data saved locally in your browser (nothing sent to a server)
- Works offline once loaded
- Installable as a home screen app on iPhone and Android

## Getting Started

### Option 1: Run Locally

Open `flybox.html` in any modern browser. That's it.

### Option 2: Host with GitHub Pages (free)

1. Fork or clone this repo
2. Go to **Settings > Pages**
3. Set source to your main branch, root folder
4. Rename `flybox.html` to `index.html`
5. Your app will be live at `https://yourusername.github.io/flybox`

### Option 3: Host with Netlify (free)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Drag and drop the `flybox.html` file
3. You get a live URL instantly

## Install on Your Phone

Once the page is hosted at a URL:

**iPhone:** Open in Safari > tap the Share button > "Add to Home Screen"

**Android:** Open in Chrome > tap the three-dot menu > "Add to Home Screen" or "Install App"

The app launches full-screen and behaves like a native app. Your data stays on your device.

## Data

All pattern and inventory data is stored in your browser's localStorage. Nothing is transmitted anywhere. If you clear your browser data, your customizations will be lost, but you can always reset to the default 50 patterns using the Reset button in the app.

The default patterns cover four hatch categories with season and water condition tags:

| Hatch | Patterns | Peak Season |
|-------|----------|-------------|
| BWO (Baetis) | 15 | Spring, Fall |
| PMD | 14 | Summer |
| Midge | 12 | Winter, Spring |
| Stonefly | 12 | Year-round |

## Customizing

**Add your own patterns** using the "+ Add Fly" button. Every field is editable: name, hatch, style, hook, sizes, materials, tying references, seasons, and conditions.

**Edit existing patterns** by expanding any card and clicking Edit.

**Track your inventory** by toggling patterns into your box and setting quantities and sizes tied.

## Tech

Single HTML file. No build step, no dependencies to install, no framework to configure.

- React 18 (loaded from CDN)
- Babel standalone for JSX (loaded from CDN)
- localStorage for persistence
- Responsive CSS for mobile/desktop

## License

Do whatever you want with it. Tie flies, catch fish.
