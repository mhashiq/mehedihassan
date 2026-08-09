# Md. Mehedi Hassan — Personal Academic Website

Personal academic portfolio website built with [Jekyll](https://jekyllrb.com/) and the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template, hosted on **GitHub Pages**.

**Owner**: Md. Mehedi Hassan (Ph.D. Researcher in Biomedical AI & Medical Imaging at Texas Tech University)  
**Repository**: `mhashiq/mehedihassan`  
**Live Site URL**: [https://mhashiq.github.io/](https://mhashiq.github.io/) (or `https://mhashiq.github.io/mehedihassan/`)

---

## 🚀 Running Locally

To preview and edit the website locally:

### 1. Install Dependencies
```bash
bundle install
```

### 2. Start Local Development Server
```bash
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```
Open **[http://127.0.0.1:4000/](http://127.0.0.1:4000/)** in your browser. Any edits to Markdown (`*.md`) or HTML files will automatically regenerate and refresh the preview in real-time.

### 3. Build Production Bundle
To compile static production HTML files into `_site/`:
```bash
bundle exec jekyll build
```

---

## 📂 Site Content & Directory Layout

- **`_config.yml`**: Site-wide configuration, author bio, social media profiles, Google Scholar, ORCID, and repository settings.
- **`_data/navigation.yml`**: Header menu navigation configuration (`About`, `Publications`, `Teaching`, `CV`).
- **`_pages/about.md`**: Main homepage featuring biography, news & notification badges, quantitative research impact (109 papers, 2,253+ citations, h-index 25, i10-index 48), 2 granted patents, research focus areas, and contact details.
- **`_pages/cv.md`**: Interactive Curriculum Vitae covering Education, Academic Positions, Awards, Patents, Technical Skills, and Publication loops.
- **`_publications/`**: Markdown entries for peer-reviewed papers (*The Lancet Infectious Diseases*, *Engineering Applications of AI*, *IEEE JBHI*, *Scientific Reports*, etc.).
- **`_teaching/`**: Markdown entries for courses taught (Adelaide University, Vcourse Platform).
- **`images/`**: Profile photos (`images/myprofile.jpg`), icons, and media assets.

---

## 🌐 Deploying to GitHub Pages

1. Stage, commit, and push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Update academic portfolio content and publications"
   git push origin main
   ```
2. On GitHub, navigate to **Settings -> Pages**:
   - Set **Source** to `Deploy from a branch` (Branch: `main` / `root`).
3. GitHub Pages will automatically build and publish the live site.
