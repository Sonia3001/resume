# Sonia Grover — Resume Website

A clean, interactive single-page resume built with pure HTML/CSS/JS.
No frameworks, no dependencies, no build step required.

## 🚀 Deploy on GitHub Pages (5 minutes)

1. Create a new GitHub repository named `resume` (or any name you like)
2. Upload the `index.html` file to the repo root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch → `/ (root)` → click **Save**
6. Your live URL will be: `https://yourusername.github.io/resume`

## ✏️ How to edit content

Open `index.html` in any text editor (TextEdit on Mac, Notepad on Windows).

| What to change | Where to find it |
|---|---|
| Name, title, contact | Search for `<!-- HERO -->` |
| Summary paragraph | Search for `<!-- ── SUMMARY ── -->` |
| Metric numbers | Search for `<!-- METRICS -->` (the 25%, 20%, etc.) |
| Job details | Search for `<!-- ── EXPERIENCE ── -->` |
| Skills | Search for `<!-- ── SKILLS ── -->` |
| Education | Search for `<!-- ── EDUCATION ── -->` |
| Colours | Change values in `:root { }` at the top of the `<style>` block |

## 📱 Features

- Fully responsive — works on mobile, tablet, and desktop
- 5 interactive tabs: Summary, Experience, Skills, Education, Contact
- Expandable job cards — click to reveal full bullet points
- Hover effects on skill tags
- Clickable contact links (phone, email, LinkedIn)
- No external dependencies — loads instantly
- Works offline

## 🎨 Customising colours

In the `<style>` block, find `:root` and change:
```css
--navy:  #1C3557;   /* dark navy — hero background start */
--blue:  #2A5298;   /* mid blue — buttons, tabs, accents */
--sky:   #3B82C4;   /* sky blue — company names, icons */
--lblue: #EAF1F8;   /* light blue — backgrounds, skill tags */
```
