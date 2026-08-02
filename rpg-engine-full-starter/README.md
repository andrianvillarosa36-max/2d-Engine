# 2D RPG Engine Studio Starter

This is the first milestone build for the app. It runs as a single HTML file and works well as a GitHub Pages / static site starter.

## What is included
- Home, Projects, Create Project, Settings
- Project creation wizard
- Drag-and-drop project reordering
- Rename, duplicate, delete, favorite, export
- Tilemap editor with multiple connected terrains
- +Terrain button that creates a new connected terrain
- Working sprite image upload preview
- Theme, text size, accent color, and cache settings

## How to run in Termux
```bash
cd ~/rpg-engine-full-starter
python -m http.server 8000
```
Then open the shown address in your browser.

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial engine starter"
```
Create a GitHub repo, add it as origin, and push.

## Notes
This starter is the foundation. Next milestones can add dialogue, quests, combat, inventory, layer editing, and export packaging.
