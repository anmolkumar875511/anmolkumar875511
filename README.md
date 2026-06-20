<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&weight=600&size=30&duration=3200&pause=1200&color=6FB7D6&center=true&vCenter=true&width=720&lines=Backend+Engineer;AI-Integrated+Systems;Full-Stack+MERN+Developer;IIT+Madras+%7C+MNNIT+Allahabad" alt="Typing SVG" />

<br>

# Anmol Kumar Shaharwal

<sub>Backend-leaning full-stack engineer building scalable, AI-integrated, production-grade systems</sub>

<br><br>

<a href="mailto:anmolkumar875511@gmail.com"><img src="https://img.shields.io/badge/Email-anmolkumar875511-FF6B3D?style=flat-square&logo=gmail&logoColor=white&labelColor=11283F"/></a>
<a href="https://linkedin.com/in/anmolkumar8755"><img src="https://img.shields.io/badge/LinkedIn-anmolkumar8755-6FB7D6?style=flat-square&logo=linkedin&logoColor=white&labelColor=11283F"/></a>
<a href="https://github.com/anmolkumar875511"><img src="https://img.shields.io/badge/GitHub-anmolkumar875511-EDE8DC?style=flat-square&logo=github&logoColor=white&labelColor=11283F"/></a>
<a href="https://anmol-kumar-shaharwal.vercel.app"><img src="https://img.shields.io/badge/Portfolio-view_site-9FD68B?style=flat-square&logo=vercel&logoColor=white&labelColor=11283F"/></a>

<br>

<a href="#projects">Projects</a> ·
<a href="#stack">Stack</a> ·
<a href="#writing">Writing</a> ·
<a href="#achievements">Achievements</a> ·
<a href="#contact">Contact</a>

</div>

<br>

## About

I came into engineering through biology — currently reading for a **B.Tech in Biotechnology** at MNNIT Allahabad while simultaneously completing a **B.S. in Data Science & Applications** from IIT Madras. Most of my work lives at the intersection of **API architecture, database design, and applied AI** — wiring LLMs like Gemini and Claude into real products, with auth, schemas, and edge cases handled properly, not demoed around.

<table>
<tr>
<td width="50%" valign="top">

**Motilal Nehru NIT, Allahabad**
B.Tech, Biotechnology
`Aug 2024 – Present` · CGPA 9.09

</td>
<td width="50%" valign="top">

**Indian Institute of Technology, Madras**
B.S., Data Science & Applications
`May 2024 – Present` · CGPA 8.99

</td>
</tr>
</table>

<br>

## Projects
<a name="projects"></a>

<details open>
<summary><strong>Veyu</strong> — civic issue reporting platform <code>🚧 in progress</code></summary>
<br>

A full-stack MERN platform for reporting and tracking civic issues, built solo with a one-month build cycle at zero infrastructure cost. Geospatial complaint mapping, role-based access for citizens and officials, and Gemini Flash for automated triage — with three signature modules: **PulseGrid**, **SilentSignal**, and **FieldMesh**.

- Geospatial complaint handling, routed by location rather than category alone
- Role-based access control separating citizen, field, and admin permissions
- Google Gemini Flash integrated for automated issue classification

`MongoDB` `Express.js` `React.js` `Node.js` `Gemini Flash` `Geospatial Queries`

</details>

<details>
<summary><strong>AgroAI</strong> — field force intelligence platform <code>🏆 Finalist, Syngenta Hackathon · IIT Madras</code></summary>
<br>

Built with team **InfernoX** for the Syngenta Hackathon at IIT Madras' Paradox fest, named a **Finalist (Remarkable Accomplishment)**. An AI-guided platform helping agricultural field reps decide who to visit and why. I owned the backend — APIs, database architecture, and AI integration.

- RandomForest model ranking field visits by priority, trained on real operational data
- Retailer and grower analytics drawn from ~4K retailers and ~235K POS transactions
- Crop risk assessment plus a Claude-powered chat endpoint for field reps
- Shipped as parallel FastAPI/MongoDB and Node/Express/MongoDB backends, both with JWT auth

`FastAPI` `Node.js` `MongoDB` `RandomForest` `Claude API` `JWT`

</details>

<details>
<summary><strong>KaushalSetu AI</strong> — AI career upskilling platform <code>🔗 Live</code></summary>
<br>

An AI-powered full-stack career upskilling platform spanning 8 domains — resume parsing, skill-gap analysis, learning roadmaps, and a scored mock interview simulator.

- Engineered a 10+ module production REST API: resume parsing, skill-gap analysis, AI roadmaps, mock interview simulator with 0–10 automated scoring
- Integrated Google Gemini for prompt-engineered workflows — parsing, per-answer evaluation, holistic feedback
- JWT + Passport.js (OAuth 2.0) auth, Cloudinary media storage, Nodemailer OTP workflows
- Deployed on Vercel with optimized build pipelines

`React.js v19` `Node.js` `Express.js` `MongoDB` `Gemini API` `JWT` `Passport.js` `Cloudinary` `Vercel`

**[Live →](https://kaushal-setu-ai.vercel.app)** · **[GitHub →](https://github.com/anmolkumar875511/KaushalSetuAI)**

</details>

<details>
<summary><strong>SkillBridge</strong> — AI career intelligence platform <code>🔗 Live</code></summary>
<br>

A career intelligence platform built around hybrid resume parsing — rule-based + LLM semantic parsing — and real job matching.

- 5-stage resume pipeline: PDF upload → rule-based parse → LLM semantic parse → merge engine → skill normalization
- Complete auth system: access + refresh token rotation, HTTP-only secure cookies, Google OAuth, email OTP
- RBAC middleware separating user, employer, and admin permissions
- Admin panel with role-protected analytics, user management, blacklisting, cron-based automation

`Node.js` `Express 5` `MongoDB` `React.js` `JWT` `OAuth 2.0` `LLM APIs` `Vercel`

**[Live →](https://skillbridge-chi.vercel.app)** · **[GitHub →](https://github.com/anmolkumar875511/SkillBridge)**

</details>

<details>
<summary><strong>The Caravan Chronicle</strong> — travel grievance platform <code>🔗 Live</code></summary>
<br>

A community-driven platform where travelers report and discuss travel-related issues, built around secure RESTful services and cloud-native storage.

- Secure RESTful endpoints with modular Express.js routing
- Multer-powered multipart uploads with optimized request handling
- MongoDB Atlas workflows for scalable community discussion threads
- Responsive UI built for consistent cross-device access

`HTML5` `CSS3` `JavaScript ES6+` `Node.js` `Express.js` `MongoDB Atlas` `Multer`

**[Live →](https://cranaval-chronicle.vercel.app)** · **[GitHub →](https://github.com/anmol20240007-collab/Cranaval_Chronicle)**

</details>

<details>
<summary><strong>PlacementPortal</strong> — campus placement management system</summary>
<br>

A full-stack system connecting students, companies, and the placement cell, with three distinct role-based experiences.

- Tri-role backend (Student / Company / Admin) with Flask-Security-Too token auth and RBAC middleware across 8 RESTful modules
- Celery + Redis async job pipeline for daily drive reminders, monthly admin reports, on-demand CSV exports
- Redis caching on high-traffic endpoints with targeted cache invalidation on writes

`Flask` `Flask-RESTful` `SQLAlchemy` `SQLite` `Vue.js 3` `Pinia` `Celery` `Redis`

**[GitHub →](https://github.com/anmolkumar875511/PlacementPortal)**

</details>

<details>
<summary><strong>Hospital Management System</strong> — RBAC-based care coordination</summary>
<br>

An RBAC-based system coordinating admins, doctors, and patients around appointments and records.

- Relational schema covering patients, doctors, and appointments
- Appointment conflict prevention logic to stop double-bookings
- Analytics dashboard endpoints for admin oversight
- Automated DB initialization with role-scoped access across three user tiers

`Flask` `SQLite` `Jinja2` `Flask-RESTful` `RBAC`

**[GitHub →](https://github.com/anmolkumar875511/HospitalManagement)**

</details>

<br>

## Stack
<a name="stack"></a>

|  |  |
|---|---|
| **Languages** | ![C++](https://img.shields.io/badge/-C++-11283F?style=flat-square&logo=cplusplus&logoColor=6FB7D6) ![JavaScript](https://img.shields.io/badge/-JavaScript-11283F?style=flat-square&logo=javascript&logoColor=F0DB4F) ![Python](https://img.shields.io/badge/-Python-11283F?style=flat-square&logo=python&logoColor=6FB7D6) ![Java](https://img.shields.io/badge/-Java-11283F?style=flat-square&logo=openjdk&logoColor=FF6B3D) ![SQL](https://img.shields.io/badge/-SQL-11283F?style=flat-square&logo=postgresql&logoColor=6FB7D6) |
| **Frontend** | ![React](https://img.shields.io/badge/-React-11283F?style=flat-square&logo=react&logoColor=6FB7D6) ![Vue](https://img.shields.io/badge/-Vue.js-11283F?style=flat-square&logo=vuedotjs&logoColor=9FD68B) ![Tailwind](https://img.shields.io/badge/-Tailwind-11283F?style=flat-square&logo=tailwindcss&logoColor=6FB7D6) ![Bootstrap](https://img.shields.io/badge/-Bootstrap-11283F?style=flat-square&logo=bootstrap&logoColor=FF6B3D) |
| **Backend** | ![Node.js](https://img.shields.io/badge/-Node.js-11283F?style=flat-square&logo=nodedotjs&logoColor=9FD68B) ![Express](https://img.shields.io/badge/-Express-11283F?style=flat-square&logo=express&logoColor=EDE8DC) ![Flask](https://img.shields.io/badge/-Flask-11283F?style=flat-square&logo=flask&logoColor=EDE8DC) ![FastAPI](https://img.shields.io/badge/-FastAPI-11283F?style=flat-square&logo=fastapi&logoColor=6FB7D6) |
| **Databases** | ![MongoDB](https://img.shields.io/badge/-MongoDB-11283F?style=flat-square&logo=mongodb&logoColor=9FD68B) ![SQLite](https://img.shields.io/badge/-SQLite-11283F?style=flat-square&logo=sqlite&logoColor=6FB7D6) |
| **AI / Integration** | ![Gemini](https://img.shields.io/badge/-Gemini_API-11283F?style=flat-square&logo=google&logoColor=6FB7D6) ![Claude](https://img.shields.io/badge/-Claude_API-11283F?style=flat-square&logo=anthropic&logoColor=FF6B3D) ![JWT](https://img.shields.io/badge/-JWT-11283F?style=flat-square&logo=jsonwebtokens&logoColor=EDE8DC) ![OAuth](https://img.shields.io/badge/-OAuth_2.0-11283F?style=flat-square&logo=auth0&logoColor=9FD68B) |
| **Cloud & Tools** | ![Vercel](https://img.shields.io/badge/-Vercel-11283F?style=flat-square&logo=vercel&logoColor=EDE8DC) ![Cloudinary](https://img.shields.io/badge/-Cloudinary-11283F?style=flat-square&logo=cloudinary&logoColor=6FB7D6) ![Git](https://img.shields.io/badge/-Git-11283F?style=flat-square&logo=git&logoColor=FF6B3D) ![Postman](https://img.shields.io/badge/-Postman-11283F?style=flat-square&logo=postman&logoColor=FF6B3D) ![Linux](https://img.shields.io/badge/-Linux-11283F?style=flat-square&logo=linux&logoColor=EDE8DC) |

<br>

## Writing
<a name="writing"></a>

Notes from building and learning — part documentation, part teaching myself by explaining it.

| Post | Topic |
|---|---|
| [Building a MERN Authentication System That Doesn't Fall Apart](#) | JWT access/refresh tokens, HTTP-only cookies, revocation |
| [Understanding Dijkstra's Algorithm, Properly](#) | Graphs, greedy proofs, C++ implementation |
| [How React's Context API Actually Works](#) | Prop drilling, re-renders, when Context stops scaling |
| [Top Mistakes I Made While Learning DSA](#) | Complexity estimation, recursion depth, memoization (Java) |
| [Binary Search: Beyond the Basics](#) | Search-on-the-answer pattern, C++ & Java side by side |

<sub>Full write-ups live on my <a href="https://anmol-kumar-shaharwal.vercel.app">portfolio site</a>.</sub>

<br>

## Achievements
<a name="achievements"></a>

| | |
|---|---|
| 🏆 **Finalist (Remarkable Accomplishment)** — Syngenta Hackathon, IIT Madras Paradox Fest | `AgroAI` · Jun 2026 |
| 🏆 **Finalist, Top 35 Teams** — Sankalp Hackathon (National Level) | `KaushalSetu AI` · Feb 2026 |
| 🥇 **1st Position** — Dashboarding (Software), Genesis, Avishkar, MNNIT Allahabad | Nov 2025 |
| 🥈 **2nd Position** — Palladin (Software), Genesis, Avishkar, MNNIT Allahabad | Nov 2025 |

<details>
<summary>Positions of Responsibility</summary>
<br>

| Role | Organization | Duration |
|---|---|---|
| Media Team — Video Editing | Jigyasa Club, MNNIT Allahabad | Jul 2025 – Present |
| Media Team — Photography | Green Club, MNNIT Allahabad | Jul 2024 – May 2025 |

</details>

<br>

## Coding Profiles

<a href="https://leetcode.com/u/anmol_1186/"><img src="https://img.shields.io/badge/LeetCode-anmol__1186-FF6B3D?style=flat-square&logo=leetcode&logoColor=white&labelColor=11283F"/></a>
<a href="https://codeforces.com/profile/anmolkumar875511"><img src="https://img.shields.io/badge/Codeforces-anmolkumar875511-6FB7D6?style=flat-square&logo=codeforces&logoColor=white&labelColor=11283F"/></a>
<a href="https://www.codechef.com/users/anmolkumar87"><img src="https://img.shields.io/badge/CodeChef-anmolkumar87-9FD68B?style=flat-square&logo=codechef&logoColor=white&labelColor=11283F"/></a>
<a href="https://www.geeksforgeeks.org/user/anmolkumatmmu/"><img src="https://img.shields.io/badge/GeeksforGeeks-anmolkumatmmu-EDE8DC?style=flat-square&logo=geeksforgeeks&logoColor=white&labelColor=11283F"/></a>

<br><br>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=anmolkumar875511&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0F2236&title_color=6FB7D6&icon_color=FF6B3D&text_color=EDE8DC" height="165"/>
<img src="https://streak-stats.demolab.com?user=anmolkumar875511&theme=tokyonight&hide_border=true&background=0F2236&ring=FF6B3D&fire=FF6B3D&currStreakLabel=6FB7D6" height="165"/>

</div>

<br>

## Contact
<a name="contact"></a>

<div align="center">

<sub>Open to internships, freelance backend work, and anything that involves wiring AI into a real product.</sub>

<br><br>

<a href="mailto:anmolkumar875511@gmail.com"><img src="https://img.shields.io/badge/Say_hello-anmolkumar875511@gmail.com-FF6B3D?style=for-the-badge&logo=gmail&logoColor=white&labelColor=11283F"/></a>

<br><br>

<sub>© 2026 Anmol Kumar Shaharwal</sub>

</div>
