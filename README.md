# Episodes Folder

Place your episode infographic HTML files here.

## Naming Convention

```
s[series]-ep[number]-[slug].html
```

### Examples:
- `s1-ep03-mississippi-bubble.html`
- `s1-ep07-newtons-gold-standard.html`
- `s2-ep15-swift-dollar-system.html`

## Adding a New Episode

1. Add your HTML file to this `/episodes/` folder
2. Add one line to `episodes.json`:

```json
"s1-ep03": { "url": "episodes/s1-ep03-mississippi-bubble.html" }
```

That's it! The index page will automatically show the 📊 indicator and make it clickable.
