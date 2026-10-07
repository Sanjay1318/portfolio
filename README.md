# Sanjay Kumar – Portfolio

Personal portfolio of **Vadla Sanjay Kumar**, a Computer Science graduate from Hyderabad building backend and full-stack web applications with Python, Flask and MySQL.

**Live site:** https://sanjay1318.github.io/portfolio/

## What's on the site

- **Five pages** (Home, Projects, Skills, Background, Contact) with animated page transitions
- **Role switcher** that reorders projects for Backend, Full-Stack, AI / ML or Data roles
- **Interactive terminal** in the hero. Type `help` to see commands such as `projects`, `role ai` and `resume`
- **Project filters** by technology, and skills that link to the projects using them
- **Architecture walkthroughs** on project cards: click each step of a flow to see what it does
- **Resume download** button
- Responsive layout and reduced-motion support

## Projects featured

| Project | Stack |
|---|---|
| AI Resume Screening System | Python, Flask, MySQL, Groq API (LLaMA 3), Tailwind CSS |
| FlaskCart (e-commerce) | Python, Flask, MySQL, JavaScript |
| Attendance Tracking Management System | Python, MySQL, HTML, CSS, JavaScript |
| Modus ETI Enterprise AI Build (hackathon) | FastAPI, PostgreSQL, SQLAlchemy, React, Cytoscape.js |
| Redrob India Runs Data & AI Challenge (hackathon) | Python, TF-IDF ranking |
| HackerRank Orchestrate (hackathon) | Python, LLM API |

## Tech

Plain HTML, CSS and JavaScript in a single `index.html`. No build step, no frameworks. Fonts load from Google Fonts.

## Run it locally

Open `index.html` in any browser. That's it.

## Deploy with GitHub Pages

1. Create a repository named `portfolio` and upload these files to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://<your-username>.github.io/portfolio/`.

## Updating content

- Project data lives in the `P` array near the top of the `<script>` block.
- Architecture flows are in the `A` object, and role copy is in `ROLES`.
- The resume download is embedded in the page. To update it, replace the `RESUME` base64 string, or swap the button for a plain link to `Vadla_Sanjay_Kumar_Resume.pdf` in this repo.

## Contact

- Email: sanjaychari999@gmail.com
- GitHub: [Sanjay1318](https://github.com/Sanjay1318)
- LinkedIn: [sanjaychari1318](https://www.linkedin.com/in/sanjaychari1318)
