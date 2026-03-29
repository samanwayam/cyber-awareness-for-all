# Contributing to Cyber Awareness for All 🌐🔐

Thank you for your interest in contributing! This project exists to make cybersecurity education accessible to everyone — and every contribution, big or small, helps achieve that mission.

Please take a few minutes to read this guide before getting started.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Ways to Contribute](#ways-to-contribute)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Contribution Guidelines](#contribution-guidelines)
- [Content Standards](#content-standards)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Reporting Issues](#reporting-issues)
- [Translation Guide](#translation-guide)
- [Recognition](#recognition)

---

## 🤝 Code of Conduct

This is a community-driven project focused on child safety and digital education. All contributors are expected to:

- Be respectful and inclusive in all interactions
- Keep all content appropriate for children (ages 8 and above)
- Never submit content that could endanger, exploit, or harm minors
- Provide constructive feedback — critique ideas, not people

Violations may result in removal from the project.

---

## 🛠️ Ways to Contribute

You don't need to be a developer to contribute. Here are the many ways you can help:

| Contribution Type | Examples |
|-------------------|----------|
| 📝 **Content** | New awareness modules, updated threat info, real-world scenarios |
| 🌍 **Translation** | Malayalam, Hindi, Tamil, Telugu, and other regional languages |
| 🎨 **Design** | Improving HTML/CSS, creating posters, infographics, or slide themes |
| 🐛 **Bug Reports** | Broken links, display issues, incorrect information |
| 💡 **Ideas** | Suggest new topics, formats, or features via Issues |
| 🔍 **Review** | Fact-check existing content for accuracy and age-appropriateness |
| 📚 **Documentation** | Improve README, add usage guides, or write a wiki page |

---

## 🚀 Getting Started

### 1. Fork the repository

Click the **Fork** button at the top right of the repo page to create your own copy.

### 2. Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/cyber-awareness-for-all.git
cd cyber-awareness-for-all
```

### 3. Create a branch

Use a descriptive branch name:

```bash
# For a new module
git checkout -b add-phishing-module

# For a translation
git checkout -b translate-checklist-hindi

# For a bug fix
git checkout -b fix-broken-screenshot-links
```

### 4. Make your changes

Follow the [Content Standards](#content-standards) and [Contribution Guidelines](#contribution-guidelines) below.

### 5. Commit with clear messages

```bash
git add .
git commit -m "Add: Interactive phishing awareness scenario module"
git push origin your-branch-name
```

**Good commit message examples:**
```
Add: Tamil translation of kids checklist
Fix: Broken screenshot paths in README
Update: Password safety module with 2FA guidance
Docs: Improve CONTRIBUTING translation guide
```

### 6. Open a Pull Request

Go to the original repo and open a Pull Request from your branch. Use the PR template provided and describe clearly what you've added or changed.

---

## 📁 Repository Structure

Please place your files in the correct folder:

```
cyber-awareness-for-all/
├── presentations/        ← .pptx slide decks
├── modules/              ← HTML interactive learning modules
├── checklists/           ← HTML/PDF printable checklists
├── screenshots/          ← Screenshots for README display only
├── translations/         ← Translated versions
│   ├── hi/               ← Hindi
│   ├── ml/               ← Malayalam
│   └── ta/               ← Tamil
├── .github/
│   ├── ISSUE_TEMPLATE/   ← Bug & feature request templates
│   └── PULL_REQUEST_TEMPLATE.md
├── README.md
├── CONTRIBUTING.md
└── LICENSE
```

---

## 📐 Contribution Guidelines

### Naming Conventions

Use clear, descriptive, hyphen-separated file names:

```
✅ phishing-awareness-module.html
✅ checklist-hindi.html
✅ social-media-safety-poster.png

❌ module1.html
❌ new file (2).html
❌ FINALv3_FINAL.pptx
```

### Screenshots

- Add screenshots to `screenshots/` only if they are for README display
- Name them clearly: `checklist.png`, `module.png`, `presentation.png`
- Use committed files, never pasted GitHub CDN URLs (they expire)

---

## ✍️ Content Standards

Because this project is designed for children and families, all content **must** meet these standards:

### Age-Appropriateness
- Language should be clear and simple — aim for reading level ages 8–16
- Avoid jargon; if technical terms are necessary, explain them plainly
- Use relatable scenarios (gaming, social media, messaging apps)

### Accuracy
- All cybersecurity information must be factually correct and up to date
- Cite credible sources where possible (NCMEC, Childnet, ENISA, CERT-In, etc.)
- Do not include statistics without a credible source

### Safety
- Never include content that could itself be used harmfully (e.g., actual phishing templates, exploit code)
- Scenarios should educate about dangers without recreating them in detail
- Always include a "what to do" resolution in every threat scenario

### Tone
- Empowering, not fear-mongering
- Encouraging and positive — the goal is confidence, not anxiety
- Neutral and inclusive across cultures, genders, and backgrounds

---

## 🔁 Submitting a Pull Request

When opening a PR, please include:

- **What** you've added or changed (a short summary)
- **Why** it's useful or what problem it solves
- **Screenshots** if your change affects anything visual
- **Testing note** — confirm you've opened the HTML file in a browser and it works correctly

**Before submitting, please check:**

- [ ] Content is appropriate for children ages 8 and above
- [ ] No real personal information (names, addresses, phone numbers) is included
- [ ] HTML files open correctly in Chrome, Firefox, and Safari
- [ ] File is placed in the correct folder
- [ ] File name follows the naming convention
- [ ] No broken links or missing images

For large or structural changes, please **open an Issue first** to discuss the direction before building — this saves everyone time.

---

## 🐛 Reporting Issues

Found a bug, broken link, outdated information, or inappropriate content? Please [open an Issue](https://github.com/samanwayam/cyber-awareness-for-all/issues/new/choose) using the appropriate template and include:

- A clear title describing the problem
- Which file or section is affected
- What you expected vs. what you saw
- Screenshots if relevant

---

## 🌍 Translation Guide

We especially welcome translations into regional Indian languages. To add a translation:

1. Create a folder under `translations/` using the [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
   - `translations/ml/` for Malayalam
   - `translations/hi/` for Hindi
   - `translations/ta/` for Tamil
2. Copy the original HTML file into the folder and translate all visible text
3. Keep emoji, layout, structure, and interactive functionality intact
4. Name the file with the language suffix: `checklist-ml.html`
5. Open a PR with the title: `Translation: [Language] – [File Name]`

---

## 🏅 Recognition

All contributors are valued and will be:

- Listed in the repository's contributors graph
- Acknowledged in release notes for significant contributions
- Credited in translated files where applicable

---

## 💬 Questions?

If you're unsure about anything, [open an Issue](https://github.com/samanwayam/cyber-awareness-for-all/issues) with the label `question`. We're happy to help.

Thank you for helping make the internet safer for kids. 🛡️

---

<p align="center">
  <a href="README.md">← Back to README</a>
</p>
