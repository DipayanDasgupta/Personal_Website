# Dipayan Dasgupta — Personal Portfolio

A dark, futuristic personal portfolio website built with HTML, CSS, and vanilla JavaScript.

## ✨ Features
- Animated particle/network canvas background
- Custom cursor with magnetic hover effect
- Typed text animation cycling through specializations
- Scroll-triggered reveals with staggered animations
- Count-up stat animations
- 3D tilt effect on project/achievement cards
- **Clickable image placeholders** — click any placeholder to upload your real photo/screenshot
- Progress bar on scroll
- Fully responsive (mobile, tablet, desktop)
- Contact form with success feedback

## 📁 Structure
```
portfolio/
├── index.html          # Main HTML
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # All JavaScript
├── images/             # Put your images here
└── RESUME_DIPAYAN_DASGUPTA.pdf  # Copy your resume here
```

## 🖼️ Adding Your Images
Every placeholder in the site is **clickable** — click it in the browser to upload the real image instantly (for testing). For the final deployed version, replace them in HTML:

| Placeholder | Recommended Size | Location in HTML |
|---|---|---|
| Profile Photo | 400 × 500 px | `#about` section |
| Turia Labs Dashboard | 1200 × 700 px | Featured project |
| KDSH Screenshot | 600 × 340 px | Project card 1 |
| Portfolio Optimizer | 600 × 340 px | Project card 2 |
| RAG Chatbot | 600 × 340 px | Project card 3 |
| AI Portfolio Agent | 600 × 340 px | Project card 4 |
| Cricket Video Generator | 600 × 340 px | Project card 5 |
| News Analyzer | 600 × 340 px | Project card 6 |
| Company Logos (×4) | 80 × 80 px | Timeline section |

To replace a placeholder in `index.html`, swap the `.img-placeholder` div with:
```html
<img src="images/your-image.jpg" alt="Description" style="width:100%;aspect-ratio:16/9;object-fit:cover;border-radius:12px;" />
```

## 🚀 Deploy to GitHub Pages

### Step 1 — Push to GitHub
```bash
# Navigate to the portfolio folder
cd portfolio

# Initialize git
git init

# Add your remote (replace DipayanDasgupta with your GitHub username)
git remote add origin https://github.com/DipayanDasgupta/DipayanDasgupta.github.io.git

# Stage all files
git add .

# Commit
git commit -m "🚀 Initial portfolio deployment"

# Push to main branch
git push -u origin main
```

### Step 2 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait ~1 minute, then visit: `https://DipayanDasgupta.github.io`

### Option B — Use existing repo (Personal_Website)
```bash
cd portfolio
git init
git remote add origin https://github.com/DipayanDasgupta/Personal_Website.git
git add .
git commit -m "🚀 Portfolio v2 - full redesign"
git push -u origin main
```
Then in Settings → Pages, set source to `main` branch, root folder.

> **Note:** For GitHub Pages from a non-username repo, the URL will be:
> `https://DipayanDasgupta.github.io/Personal_Website/`

### Step 3 — Update Links
In `index.html`, update:
- LinkedIn URL in `#about` section
- GitHub links (should already be correct)
- Make sure `RESUME_DIPAYAN_DASGUPTA.pdf` is in the root folder

## 🛠️ Local Development
Simply open `index.html` in any browser — no build step required.

For live reload, use VS Code's **Live Server** extension.

## 📝 Customization
- Colors: Edit CSS variables in `css/style.css` (`:root` block)
- Content: Edit `index.html` directly
- Animations: Tweak timing in `js/main.js`
