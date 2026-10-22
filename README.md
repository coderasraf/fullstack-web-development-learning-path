# Full Stack Dev Learning Path

An interactive, single-page learning path that takes you from internet fundamentals to a job-ready full-stack JavaScript developer, organized into 25 modules with week-by-week plans and progress tracking.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?logo=githubpages&logoColor=white)

## Overview

A self-contained `index.html` study planner. The curriculum is defined as data inside the page and rendered into phases, modules and weekly topics, each with estimated hours, difficulty, skills and practical tips, plus links to resources such as The Odin Project and freeCodeCamp.

## Curriculum

| Phase | Modules |
| --- | --- |
| Foundations | Internet Fundamentals, HTML & CSS, Chrome DevTools, HTML5/CSS3 Projects, JavaScript, Package Managers, Git & GitHub |
| Frontend Development | React.js, React.js Ecosystem, Tailwind CSS, React.js Projects, Testing |
| Backend & Databases | Linux Fundamentals, Node.js Basics, TypeScript, JavaScript Under The Hood, API Development, PostgreSQL, Next.js 14, Backend Projects |
| Advanced Systems | Redis, WebSockets, Web Security, CI/CD |
| Career Readiness | Interview Preparation |

## Features

- 25 modules across 5 phases, broken down into weekly topics with hours and difficulty ratings
- Skills list and a practical tip for every module
- Mark topics as completed, with an overall progress percentage
- Search/filter across the curriculum
- Light/dark theme (follows system preference, with a toggle)
- Progress and theme saved in the browser with `localStorage`

## Tech Stack

- HTML5, CSS3 and vanilla JavaScript (single file)
- Google Fonts (Outfit, Inter, JetBrains Mono)
- GitHub Pages (static deploy workflow) for hosting

## Getting Started

No build step is needed.

```bash
git clone https://github.com/coderasraf/fullstack-web-development-learning-path.git
cd fullstack-web-development-learning-path
# open index.html in your browser, or serve it locally:
npx serve .
```

## Project Structure

```text
fullstack-web-development-learning-path/
├── index.html                      # Curriculum data, UI and logic
└── .github/workflows/static.yml    # Deploys to GitHub Pages on push to main
```

## Live Demo

[coderasraf.github.io/fullstack-web-development-learning-path](https://coderasraf.github.io/fullstack-web-development-learning-path/)

## Author

Built by **Ashraf Siddik**, Shopify developer & CRO specialist.

- Website: [ashraf-siddik.com](https://ashraf-siddik.com)
- GitHub: [@coderasraf](https://github.com/coderasraf)
