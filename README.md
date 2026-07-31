# Md. Mehedi Hassan — Personal Academic Website

A premium, elegant personal academic website modelled after [jeffsachs.org](https://www.jeffsachs.org), designed for GitHub Pages hosting.

## 🚀 Quick Deploy to GitHub Pages

1. **Create a new GitHub repository** named `<your-username>.github.io`  
   *(or any repo name for `<username>.github.io/<repo-name>/`)*

2. **Upload files:**
   ```
   index.html
   profile.png        ← Replace with your actual photo!
   ```

3. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Source: `main` branch, `/ (root)`
   - Click Save

4. Your site will be live at:  
   `https://<your-username>.github.io`

## 📝 Personalisation Checklist

| Item | Location in `index.html` | What to update |
|---|---|---|
| Email | `href="mailto:mehedi@example.com"` | Your real email |
| ORCID | `href="https://orcid.org"` | Your ORCID URL |
| LinkedIn | `href="https://linkedin.com/in/..."` | Your profile URL |
| Google Scholar | `href="https://scholar.google.com/..."` | Your Scholar URL |
| ResearchGate | `href="https://researchgate.net/..."` | Your RG profile |
| Affiliations | About section info cards | Your current institutions |
| Publications | `<ul class="pub-list">` | Your actual papers + DOIs |
| CV/Timeline | `#timeline` section | Your real positions + dates |
| Profile photo | `<img src="profile.png" ...>` | Replace `profile.png` with your photo |

## 🖼 Adding Your Photo

Replace `profile.png` with a professional headshot:
- Recommended size: **800×1000px** (4:5 ratio)
- Format: `.jpg` or `.png`
- Keep the filename `profile.png` or update the `src` in `index.html`

## ✨ Features

- **Sticky navigation** with active-section highlighting
- **Full-screen hero** with animated scroll hint
- **About** section with quote block and contact cards
- **Research areas** — 6-card grid with hover effects
- **Impact statistics** — animated counter section
- **Publications list** — Nature/Lancet style with journal badges
- **Expertise grid** — technical skills with tag pills
- **CV timeline** — dual-column academic history
- **Contact** — links + functional contact form UI
- **Fully responsive** — mobile, tablet, desktop
- **No JavaScript frameworks** — pure vanilla JS, zero dependencies
- **Single HTML file** — GitHub Pages ready out of the box

## 🎨 Design System

Built with a dark-academic palette:
- **Navy** `#0a1628` — primary dark background
- **Gold** `#c9a84c` — accent, highlights, borders
- **Cream** `#faf8f4` — light section background
- **Cormorant Garamond** — elegant serif headings
- **Inter** — clean sans-serif body text
- **JetBrains Mono** — code/data labels
