# Pago Factories — AI Sync, Episode I (July 2026)

Interactive HTML deck. Serve the folder and open `index.html`:

```bash
python3 -m http.server 8899
# → http://127.0.0.1:8899/index.html
```

| File | What |
|------|------|
| `index.html` | The 14-fold deck (scroll-snap, keyboard nav) |
| `mindmap-d3.html` | "How it was woven" commit map — D3 build (active, embedded in fold 5) |
| `mindmap.html` | Same map — Three.js build (backup; swap the iframe src in index.html to use) |
| `mindmap-data.js` | Shared per-day commit data (shared-config · pago-prds · pago-Stargate) |
| `vendor/` | Local d3 + three.js (offline-safe; CDN fallback wired) |
| `previews/` | Screenshot history from the build/QA sessions |
| `*-activity.txt` | Raw git-activity extracts the map is drawn from |
