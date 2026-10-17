# Muntasir Academy

**Free, hands-on courses for data, analytics and AI careers, all running in your browser.**

🌐 **Live site:** [muntasir-academy.vercel.app](https://muntasir-academy.vercel.app/)

Muntasir Academy helps beginners become job-ready by **doing**, not just watching. Learners pick a career path, then work through short lessons and real challenges: writing SQL, running Python, building dashboards and answering interview questions, right inside the page. Nothing needs to be installed.

---

## ✨ Features

- **6 career paths:** Data Analyst, Business Analyst, Data Engineer, Data Scientist, Machine Learning Engineer and AI Engineer. Each path shows the skills employers expect and the best order to learn them.
- **81 hands-on levels in 16 topics**, from a 5-minute *Start Here* mission to machine learning, MLOps and large language models (LLMs).
- **Real practice in the browser:**
  - SQL queries on sample tables, checked instantly
  - Python with pandas-, numpy- and scikit-learn-style tools
  - Excel formulas and pivot tables, Power BI and Tableau chart builders
  - A practice terminal for Git and Docker commands
- **Explained simply:** 332 key terms, each with a plain-English definition, an everyday comparison, a real-world use and a quick check. Many include diagrams.
- **Interactive 3D visuals:** rotatable 3D charts, a 3D "map of meaning" for AI embeddings, and a temperature slider that shows how AI picks its next word.
- **Interview practice:** 104 questions in easy, medium and hard rounds for each role, with worked answers.
- **Final exams and certificates:** a timed exam for each career path (questions drawn from a bank of 103, plus hands-on tasks). Passing earns a printable certificate.
- **Job-market info and resources:** typical job titles, a normal working week and portfolio project ideas for each role, plus 29 hand-picked free resources.
- **Friendly experience:**
  - Guest mode, so anyone can try it without signing up
  - XP points and confetti when you finish a level
  - Click sounds and solution pop-ups
  - Dark mode
  - Works on phones
- **Reviews:** visitors can leave a review. It is saved to Google Sheets and shown on the site only after the owner approves it.

## 📚 What you can learn

| Topic | Levels | Topic | Levels |
|---|---|---|---|
| Start Here | 1 | Python Basics | 5 |
| Data Basics | 3 | Python for Data | 6 |
| Excel & Sheets | 6 | Data Engineering | 5 |
| SQL | 7 | Git, Cloud & DevOps | 5 |
| SQL Advanced | 3 | Statistics | 5 |
| Power BI | 7 | Machine Learning | 5 |
| Tableau | 7 | MLOps & Deployment | 5 |
| Business Analysis | 5 | AI Engineering (LLMs) | 6 |

## 🛠️ How it's built

| Part | Technology |
|---|---|
| Page structure, styling and logic | **HTML, CSS and JavaScript** in a single self-contained file (`index.html`) |
| SQL and Python practice | Small SQL and Python engines written in JavaScript that run in the browser |
| 3D charts | HTML **Canvas** with 3D-to-2D projection maths (drag to rotate) |
| Sounds | Browser **Web Audio** |
| Accounts and progress | Saved in the learner's own browser (**localStorage**) |
| Reviews backend | **Google Sheets + Google Apps Script**, with **FormSubmit** for email alerts |
| Hosting | **GitHub**, published automatically by **Vercel** |
| Search engines | `sitemap.xml`, `robots.txt`, page descriptions and structured data |
| Testing | Automated browser tests with **Playwright** that complete all 81 levels, every interview round and all 6 exams, and check the phone layout |

There is no server to run and no database to pay for. The whole academy is one file that works in any modern browser.

## 📁 Files

```
index.html     The complete website (layout, styling, code and course content)
robots.txt     Tells search engines they may index the site
sitemap.xml    Lists the site's pages for Google
og-image.png   Preview image shown when the link is shared
README.md      This file
```

## 🚀 Run it yourself

1. Download `index.html`.
2. Open it in Chrome, Edge, Firefox or Safari.

That's it. No installation is needed.

To publish your own copy, put the files in a GitHub repository and import it into [Vercel](https://vercel.com/) (or GitHub Pages). Every new upload updates the live site automatically.

## 🗺️ Planned improvements

- Sign in with Google
- Progress saved online, so it follows learners across devices
- Learning analytics to find and improve difficult lessons
- More projects and practice datasets

## 👤 Founder

**Muntasir Mamun**, founder of Muntasir Academy
📧 [muntasirmamun446@gmail.com](mailto:muntasirmamun446@gmail.com)

Built with the help of an AI coding assistant. I designed the curriculum and learner experience, and tested, deployed and maintain the site.

---

*Muntasir Academy is independent and not affiliated with Microsoft, Tableau (Salesforce), Google or any cloud provider.*
