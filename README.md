# ⚠️ Project Archived - Fresh Start Ahead! 🚀

> **Note:** This repository has been archived and is no longer actively maintained.

## 🔄 Why We're Starting Fresh

After careful consideration and reflection, our team has decided to rebuild this project from the ground up. While this version served as a valuable learning experience, we identified several areas that needed improvement:

- Better project structure and file management
- Clearer vision and goals
- Improved organization and planning
- More robust foundation for scalability

## 🎯 New Repository

We're excited to announce that development continues with renewed energy and better planning in our new repository:

**➡️ [NoteHub-studyspace (New)](https://github.com/ggauravky/NoteHub-studyspace)**

## 👥 Team Members

This project is a collaborative effort by:

- **Lead:** [@ggauravky](https://github.com/ggauravky)
- **Core Members:**
  - [@the-nikhilcodes](https://github.com/the-nikhilcodes)
  - [@ydevansh](https://github.com/ydevansh)

## 💡 Lessons Learned

Every setback is a setup for a comeback! This restart represents our commitment to:
- Learning from our experiences
- Building better systems
- Creating something we're truly proud of
- Growing as developers together

**"The best time to plant a tree was 20 years ago. The second best time is now."**

Let's build something amazing! 🌟

---

# Notes Hub

A small, responsive static website that organizes and provides study notes in a simple, user-friendly layout.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Repository structure](#repository-structure)
- [How to view locally](#how-to-view-locally)
- [Recommended next improvements](#recommended-next-improvements)
- [Contributing](#contributing)
- [License](#license)

## Overview

Notes Hub is a lightweight HTML/CSS site intended to host and link to categorized notes (school subjects, semesters, etc.). It's styled with a small set of CSS files and built to be easy to extend and maintain.

The goal is to provide a simple, distraction-free place to browse and read study notes offline or served from a small static host.

## Features

- Minimal, clean UI using plain HTML/CSS
- Responsive navigation and notes container
- Re-usable note cards with "Read More" links
- Google Fonts (Poppins) included for a modern look

## Repository structure

Top-level summary (not exhaustive):

```text
notehub-studyspace/
├─ index.html               # Home page / landing
├─ style.css                # Main stylesheet
├─ about/                   # About page(s)
│  ├─ about.html
│  └─ about.css
├─ contact/                 # Contact page(s)
├─ notes/                   # Notes grouped by level and subject
├─ lib/                     # Library / grouped resources
├─ services/                # Services page
├─ assets/                  # Images and static assets
└─ README.md
```

For a full listing see the project tree in your editor or run a directory listing from the project root.

## How to view locally

You have two quick options to view the site locally:

1) Open `index.html` directly in your browser (double-click the file or right-click -> Open with -> your browser). This works well for simple previewing but some browsers restrict features for local files.

2) Serve the folder using a simple static HTTP server (recommended). Example commands for Windows PowerShell from the project root:

```powershell
# If you have Python 3 installed
python -m http.server 8000
# then open http://localhost:8000 in your browser

# If you have Node.js installed, install and use http-server (one-time install):
npx http-server -p 8000
# then open http://localhost:8000
```

Serving over HTTP more closely matches how the site will behave when deployed and avoids local-file restrictions.

## Recommended next improvements

- Move any remaining inline styles into `style.css` and adopt semantic classes.
- Add more pages and organize notes into subject/semester folders for discoverability.
- Improve accessibility: add descriptive alt text for images, keyboard navigation, and ARIA where helpful.
- Add a small CI check or linting step if the project grows (optional).

## Contributing

Contributions are welcome. A simple workflow:

1. Fork the repository.
2. Create a branch for your feature: `git checkout -b feature/name`.
3. Make changes and commit: `git add . && git commit -m "Describe change"`.
4. Push and open a pull request against `main`.

If you'd like, I can also create a minimal GitHub Actions workflow to validate HTML/CSS on push—ask and I will add it.

## License

This repository is available under the MIT License. See `LICENSE` for details.

---

If you'd like additional changes to the README (screenshots, badges, or a live-deploy guide), tell me what you'd like and I will update it.
