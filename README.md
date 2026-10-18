# 📝 HTML Blog Assignment

Write **one blog post using only HTML** and submit it through a **Pull Request (PR)**.

## Repository Structure

```
blog-assignment/
├── CSAI/
│   └── lci20260tt/      <- your roll number folder
├── CS/
├── CSB/
└── IT/
```

Create **one folder named exactly as your roll number** inside **your branch folder** (CSAI, CS, CSB or IT).

## Rules

1. Use **only HTML**. No CSS, JavaScript or Markdown.
2. Work **only inside** `<BRANCH>/<ROLL-NO>/`. Do not touch any other file or folder.
3. Your main file must be named `index.html`.
4. Keep images in an `images/` folder inside your roll-number folder (lowercase names, no spaces, under 1 MB).
5. Write the blog yourself. No copying.

## Your Folder

```
CSAI/
└── lci20260tt/
    ├── index.html
    └── images/
        └── cover.jpg
```

## What Your Blog Must Have

- Proper HTML structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`)
- Headings (one `<h1>`, then `<h2>`, `<h3>`) and paragraphs
- One ordered list and one unordered list
- At least **3 links**: one external, one anchor link (`#section`), and one more of your choice
- At least **2 images** with `alt` text
- At least **1 table** (`<thead>`, `<tbody>`, `<th>`, `<td>`)
- Semantic tags: `<header>`, `<main>`, `<section>`, `<footer>`
- Your name, roll number and branch on the page
- Around 400-800 words, with a conclusion



Open `index.html` in your browser and check that all links and images work before submitting.

## How to Submit

Replace `<YOUR-USERNAME>`, `<BRANCH>` and `<ROLL-NO>` with your own values.

**1. Fork** the repository on GitHub (click **Fork**).

**2. Clone** your fork:
```bash
git clone https://github.com/<YOUR-USERNAME>/html-blog-assignment.git
cd html-blog-assignment
```

**3. Create your branch:**
```bash
git checkout -b blog/<ROLL-NO>
```

**4. Create your folder and write your blog:**
```bash
mkdir -p <BRANCH>/<ROLL-NO>/images
```
Add `index.html` and your images inside it.

**5. Add only your folder:**
```bash
git add <BRANCH>/<ROLL-NO>/
```
❌ Never use `git add .`

**6. Commit and push:**
```bash
git commit -m "Add blog by <ROLL-NO>"
git push origin blog/<ROLL-NO>
```

**7. Open a Pull Request** from your branch to the `main` branch of the original repo. Open the **Files changed** tab and confirm only your folder is listed.

## PR Title Format

```
ROLL-NO : Title of the blog
```

| ✅ Correct | ❌ Wrong |
|---|---|
| `lci20260tt : How the Internet Works` | `Add blog` |
| `lci20260tt : My First Week with HTML` | `lci20260tt-How the Internet Works` |

## Checklist Before You Submit

- [ ] Folder is `<BRANCH>/<ROLL-NO>/` and the file is `index.html`
- [ ] Only HTML used; all links and images work
- [ ] Every image has `alt` text
- [ ] Only my folder appears in **Files changed**
- [ ] PR title is `ROLL-NO : Title of the blog`

## Need to Fix Something?

Edit your files, then run:
```bash
git add <BRANCH>/<ROLL-NO>/
git commit -m "Fix review comments"
git push origin blog/<ROLL-NO>
```
The PR updates automatically. No new PR is needed.

**Happy blogging! 🚀**
