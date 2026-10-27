# Web Technology Laboratory (5th Sem CSE) 🌐

Welcome to the **Web Technology Lab Portfolio** by **Jagadish S** ([@Jagadish-03S](https://github.com/Jagadish-03S)), Jain Institute of Technology, Davangere.

This repository organizes all lab experiments into modular, standalone web pages accompanied by an interactive **Multi-Module Dashboard (`index.html`)** deployable to GitHub Pages.

---

## 🚀 Live Demo & Modules

| Module | Program File | Description | Topics Covered |
| :--- | :--- | :--- | :--- |
| **Portal Hub** | [`index.html`](index.html) | Central Lab Dashboard (Runs all files simultaneously) | Iframes, Multi-grid preview, responsive device switcher |
| **Module 1** | [`P1.html`](P1.html) | Basic HTML Tags & Student Profile | `<h1>`-`<h6>`, `<marquee>`, `<blockquote>`, `<pre>`, formatting tags (`<mark>`, `<del>`, `<ins>`, `<code>`) |
| **Module 2** | [`P2.html`](P2.html) | College Timetable | Complex HTML `<table>`, `<thead>`, `<tbody>`, `rowspan`, `colspan`, CSS styling |
| **Module 3** | [`P3.html`](P3.html) & [`P3.CSS`](P3.CSS) | CSS Selectors Showcase | Element, class, ID, adjacent sibling (`+`), child (`>`), attribute (`[lang]`, `[datetime]`), `:hover`, `::first-letter` |
| **Module 4** | [`P4.html`](P4.html) | Student Registration Form | HTML5 Form controls (`text`, `email`, `password`, `radio`, `checkbox`, `select`, `textarea`), validation |

---

## 🛠️ How to Run Locally

You can preview the entire lab portal locally with any lightweight static server:

### Option A: Using Python (Built-in)
```bash
# In this directory:
python -m http.server 3000
```
Then open `http://localhost:3000` in your web browser.

### Option B: Using Node / npx
```bash
npx serve .
```

---

## 📦 How to Deploy to GitHub & GitHub Pages

Follow these simple steps to publish this repository live on the internet via GitHub Pages:

### Step 1: Initialize Git and Commit
```bash
git init
git add .
git commit -m "feat: complete web technology lab modules and central portal"
```

### Step 2: Push to GitHub
1. Create a new public repository on [GitHub](https://github.com/new) named `Web-Technology-Lab` (or any name you prefer).
2. Link your local repo to GitHub and push:
```bash
git branch -M main
git remote add origin https://github.com/Jagadish-03S/Web-Technology-Lab.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub.
2. Click **Settings** (top tab) ➔ **Pages** (in the left sidebar under "Code and automation").
3. Under **Branch**, select `main` branch and `/ (root)` folder.
4. Click **Save**.
5. Within 1–2 minutes, your site will be live at:
   ```
   https://Jagadish-03S.github.io/Web-Technology-Lab/
   ```

---

## 👨‍💻 Author
- **Jagadish S**
- Jain Institute of Technology, Davangere
- GitHub: [@Jagadish-03S](https://github.com/Jagadish-03S)
