# Excalidraw System Design Guide

An interactive guide to master Excalidraw for system design interviews.

## Features

- ✅ **Progress tracking** — Checkboxes save to localStorage
- 📖 **Expandable exercises** — Click to reveal steps and challenges  
- ⚡ **Timed challenges** — Practice under interview pressure
- ⌨️ **Keyboard shortcuts reference** — Always visible
- 📱 **Mobile responsive** — Works on any device

## Deploy to GitHub Pages (2 minutes)

### Step 1: Create Repository

1. Go to [github.com/new](https://github.com/new)
2. Name it `eds-tech-public` (or anything you like)
3. Keep it **Public**
4. Click **Create repository**

### Step 2: Upload Files

1. Click **"uploading an existing file"**
2. Drag and drop these files/folders:
   ```
   _config.yml
   _layouts/
   assets/
   index.md
   ```
3. Commit to `main`

### Step 3: Enable GitHub Pages

1. Go to repository **Settings**
2. Click **Pages** (left sidebar)
3. Source: **Deploy from a branch**
4. Branch: **main** / **(root)**
5. Click **Save**

### Step 4: Visit Your Site

Wait ~1 minute, then visit:
```
https://YOUR-USERNAME.github.io/eds-tech-public/
```

Done! 🎉

---

## Project Structure

```
eds-tech-public/
├── _config.yml          # Jekyll site configuration
├── _layouts/
│   └── default.html     # Main template with JavaScript
├── assets/
│   └── css/
│       └── style.css    # All styles
├── index.md             # Main content (Markdown + HTML)
└── README.md            # This file
```

## Customization

### Edit Content

All exercises are in `index.md`. Each exercise follows this structure:

```html
<div class="exercise" data-id="unique-id">
  <div class="exercise-header">
    <!-- Title, icon, time estimate -->
  </div>
  <div class="exercise-content">
    <ol>
      <li>Step 1</li>
      <li>Step 2</li>
    </ol>
    <div class="tip-box">Pro tip here</div>
    <div class="challenge-box">Challenge description</div>
  </div>
</div>
```

### Change Styling

Edit `assets/css/style.css` to customize colors, fonts, spacing, etc.

### Update Progress Tracking

The JavaScript in `_layouts/default.html` handles:
- Saving checkbox state to localStorage
- Updating the progress bar
- Expanding/collapsing exercises

To change the total exercise count, update `TOTAL_EXERCISES` in the script.

---

## Local Development

To test locally before deploying:

```bash
# Install Jekyll (requires Ruby)
gem install bundler jekyll

# Install dependencies
bundle install

# Run local server
./run.sh

# Visit http://localhost:4000
```

---

## License

MIT — Use freely for your own interview prep guides!
