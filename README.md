# Mithul Pranav M · AI & ML Portfolio

Personal portfolio website of **Mithul Pranav M**, a B.Tech CSE (AI & ML) student at SRMIST Tiruchirappalli (2025–2029).

**Live site:** https://mithulpranav.site

## About

A single-page portfolio covering my work in LLM applications, recommendation systems and quantum optimisation. It has a dark theme (black, signal red and cyan), a cursor-reveal effect on the home portrait, and interactive demos for the skills I list.

## Pages

| Page | What it shows |
|------|---------------|
| Home | Intro and highlights |
| About | Focus areas, 2026 so far, education |
| Projects | Project write-ups with tech stacks |
| Experience | Internship, hackathons, workshops, organiser role |
| Certificates | Certificates grouped by type, with viewer |
| Skills | Skill groups, each with a small interactive lab |
| CV | Curriculum vitae with download |
| Ask AI | Ask questions about me and get quick answers |
| Contact | Ways to reach me |

## Projects featured

- **AI Learning Platform for MoSPI** — Smart India Hackathon 2026 (internal round, Team TRIBYTES). React (Vite), FastAPI, Groq LLM API, sentence-transformers.
- **Quantum-Enhanced Adaptive Urban Traffic Optimization** — signal timing as a QUBO solved with QAOA. Python, Qiskit, NumPy, NetworkX, Streamlit.
- **AI-Integrated Staff Management Portal** — B.Tech team project at SRMIST.
- **AI-Driven Recruitment and Candidate Recommendation Platform** — built during my CodeBind internship. Python, logistic regression.
- **Public Grievance Redressal Tracker** — React and Java.
- **Smart Street Light Control System** — Java.
- **Algorithm Battle: Employee ID Search** — BST vs AVL tree vs hash table, written in C.

## Skills with interactive labs

Python, Java, C, C++, machine learning, data science, LLM APIs (Groq), embeddings, prompt engineering, Qiskit, QUBO and QAOA, React, FastAPI, Streamlit, Git and GitHub, data structures, IoT basics, aptitude and reasoning, complex analysis.

## Tech used

- Single self-contained `index.html` (no build step)
- React 18 and htm, loaded from CDN
- JetBrains Mono via Google Fonts
- Plain CSS, responsive, with safe-area support for phones

## Run locally

No install needed. Download the repository and open `index.html` in a browser. An internet connection is needed for React and the font to load.

## Deploy on GitHub Pages

1. Keep `index.html` in the root of the repository (named exactly `index.html`).
2. Go to **Settings → Pages**.
3. Set Source to **Deploy from a branch**, Branch to **main**, folder **/ (root)**, then **Save**.
4. Open `https://<username>.github.io/` after a minute or two.

### Custom domain (optional)

This site uses the custom domain `mithulpranav.site`.

1. In the domain registrar's DNS settings, add four `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`.
2. Add a `CNAME` record for `www` pointing to `<username>.github.io`.
3. In **Settings → Pages**, enter the domain under **Custom domain**, click **Save**, then tick **Enforce HTTPS** once the DNS check passes.

GitHub adds a `CNAME` file to the repository for this. Keep it, or the domain will disconnect.

To update the site, upload a new `index.html` (**Add file → Upload files**) and commit.

## Contact

- Email: mithulpranavv@gmail.com
- GitHub: [mithulpranavv-dev](https://github.com/mithulpranavv-dev)
- LinkedIn: [mithul-pranav-m](https://linkedin.com/in/mithul-pranav-m-53979a37a)

---

© 2026 Mithul Pranav M. All rights reserved.
