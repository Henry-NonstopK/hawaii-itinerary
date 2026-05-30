# Hawaii Family Trip App

Mobile-first Hawaii family trip app for GitHub Pages.

## Features

- React single-page app delivered from static GitHub Pages.
- Trip itinerary tab.
- Packing checklist tab.
- Google Maps shortcut tab.
- Family bulletin board tab.
- Family chat tab.
- Notes/checkpoints tab.

## Data Storage

- Bulletin board and chat currently use browser `localStorage`.
- This means posts/messages are saved only on the same device/browser.
- For family-wide sync and realtime chat, connect Supabase or another backend later.

## Files

- `index.html` - GitHub Pages entry point.
- `hawaii-itinerary.html` - Same React app kept under the original working name.
- `hawaii-trip.md` - Current saved itinerary source.
- `CHANGELOG.md` - Project change history.
- `AGENT_ROLES.md` - Agent role names and reporting rules.

## Live Page

https://henry-nonstopk.github.io/hawaii-itinerary/

## Publish With GitHub Pages

After a GitHub remote is connected:

```sh
git add index.html hawaii-itinerary.html hawaii-trip.md README.md .nojekyll
git commit -m "Publish Hawaii family trip itinerary"
git push -u origin main
```

Then enable GitHub Pages for the repository:

- Source: deploy from branch
- Branch: `main`
- Folder: `/`
