<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!--                     NAGA SANTHOSH NIKHIL GUJJURU                         -->
<!--                        GitHub Profile README                             -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->

<div align="center">
  <img src="./assets/header.svg" alt="Naga Santhosh Nikhil Gujjuru — Software Developer, Problem Solver, Systems Thinker" width="100%"/>
</div>

<p align="center">
  <em>3rd Year B.Tech Information Technology · Siddhartha Academy of Higher Education, Vijayawada · CGPA 9.09/10</em>
</p>

<p align="center">
  <a href="mailto:chinni030314@gmail.com"><img src="https://img.shields.io/badge/Email-chinni030314%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/gujjuru-naga-santhosh-nikhil-6575b0311/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
  <a href="https://leetcode.com/u/G_Naga_Santhosh_Nikhil/"><img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/></a>&nbsp;
  <a href="https://codolio.com/profile/g_naga_santhosh_nikhil"><img src="https://img.shields.io/badge/Codolio-Profile-58a6ff?style=flat-square" alt="Codolio"/></a>
</p>

---

## About

I build software systems — not just demos. My work spans full-stack web applications, AI-powered platforms, and distributed data processing. I care about how software works internally: authentication protocols, real-time communication, retrieval pipelines, and the engineering decisions that make systems reliable at scale.

When I'm not building, I'm solving — algorithmic problems on LeetCode that sharpen both my code and my thinking. Currently exploring distributed systems architecture and advanced LLM application patterns.

---

## Algorithms & Problem Solving

Consistent practice is a core part of my engineering discipline.

<div align="center">
  <img src="./assets/dsa-stats.svg" alt="Problem Solving Statistics — 205 problems solved: 134 Easy, 70 Medium, 1 Hard. 46-day max streak, 140 active days, 60.25% acceptance rate." width="480"/>
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://leetcard.jacoblin.cool/G_Naga_Santhosh_Nikhil?theme=dark&font=Source%20Code%20Pro&ext=heatmap&border=0&radius=8"/>
    <source media="(prefers-color-scheme: light)" srcset="https://leetcard.jacoblin.cool/G_Naga_Santhosh_Nikhil?theme=light&font=Source%20Code%20Pro&ext=heatmap&border=0&radius=8"/>
    <img src="https://leetcard.jacoblin.cool/G_Naga_Santhosh_Nikhil?theme=dark&font=Source%20Code%20Pro&ext=heatmap&border=0&radius=8" alt="LeetCode Activity Heatmap and Statistics" width="480"/>
  </picture>
</div>

<br/>

<div align="center">

**Practiced Topics**

`Dynamic Programming` · `Divide and Conquer` · `Backtracking` · `Hash Tables` · `Binary Search` · `Mathematics` · `Arrays` · `Two Pointers` · `Sorting`

**Problem-Solving Languages:** Python · C

</div>

---

## Technical Expertise

| Domain | Technologies |
|:-------|:------------|
| **Languages** | Python · C++ · C · Java · JavaScript · TypeScript |
| **Frontend** | React.js · Next.js · Tailwind CSS · HTML · CSS |
| **Backend** | Node.js · Express.js · FastAPI · REST APIs |
| **Databases** | MongoDB · PostgreSQL · SQLite · Firebase Firestore |
| **AI / GenAI** | Groq LLM APIs · Gemini AI · LLM Integration · RAG · Prompt Engineering |
| **Big Data** | Apache Spark · PySpark · Distributed Data Processing |
| **Developer Tools** | Git · GitHub · VS Code · Postman · Firebase |

---

## Engineering Projects

### [SyncUp](https://github.com/nagasanthoshnikhil040507/SyncUp) — AI-Powered Real-Time Collaboration Platform

> A full-stack collaboration platform integrating project management, real-time messaging, video conferencing, and AI-powered document intelligence into a unified workspace.

**Stack:** `React.js` `Node.js/Express` `MongoDB` `Socket.IO` `WebRTC` `JWT` `Groq LLM` `RAG` `Cloudinary`

<details>
<summary><strong>Architecture &amp; Engineering Decisions</strong></summary>
<br/>

| Layer | Implementation |
|:------|:---------------|
| **Authentication** | JWT with access/refresh token rotation and role-based workspace isolation |
| **Real-Time** | Socket.IO for messaging, typing indicators, presence tracking, and live notifications |
| **Video** | WebRTC peer-to-peer conferencing with SDP/ICE signaling, screen sharing, and host moderation |
| **Session** | Automatic reconnection with session state restoration on network interruption |
| **AI Assistant** | Groq-powered LLaMA integration with context-aware responses using live project data |
| **Document Intelligence** | RAG pipeline — PDF, DOCX, PPTX, Markdown parsing → text chunking → local TF-IDF vectorization → semantic retrieval → context-aware Q&A |
| **Task Management** | Kanban boards with assignments, priorities, due dates, and activity timelines |
| **Infrastructure** | Cloudinary file storage · Nodemailer email notifications |

</details>

<br/>

### [Civic Intelligence Platform](https://github.com/nagasanthoshnikhil040507/Civic-Intelligence-Platform) — AI-Powered Grievance Management

> An intelligent civic complaint system combining a custom CNN image classifier, geospatial analysis, and perceptual duplicate detection to streamline grievance resolution workflows.

**Stack:** `React` `TypeScript` `Node.js` `MongoDB` `FastAPI` `TensorFlow/Keras`

<details>
<summary><strong>Architecture &amp; Engineering Decisions</strong></summary>
<br/>

| Layer | Implementation |
|:------|:---------------|
| **Image Classification** | Custom CNN built with TensorFlow/Keras for complaint image categorization |
| **Duplicate Detection** | Perceptual image hashing + time-window filtering to identify repeat grievances |
| **Geospatial** | MongoDB 2dsphere indexes for location-based complaint clustering and proximity analysis |
| **Officer Routing** | Workload-aware automated assignment with manual transfer workflows |
| **Access Control** | JWT authentication with RBAC across Citizen, Officer, and Admin roles |
| **Visualization** | Leaflet.js interactive complaint mapping with geographic overlays |
| **Reporting** | Automated PDF generation for complaint analytics and status summaries |

</details>

<br/>

### [SALA](https://github.com/nandakishore7054/sala-ai-learning-platform) — Smart Adaptive Learning Assistant

> *Hackathon Team Project*

An AI-powered adaptive learning platform personalizing education through intelligent recommendations, multi-modal learning support, and real-time student analytics.

**Stack:** `React` `TypeScript` `Vite` `Tailwind CSS` `Firebase` `Gemini AI` `Recharts` `Web Speech API`

**My Role:** Contributor & Developer — I contributed to the technical implementation and educational feature development as a team member. I do not own the main repository.

<details>
<summary><strong>Platform Features</strong></summary>
<br/>

- **Multi-modal learning:** Visual learning with infographics and diagrams, auditory support through AI-assisted conversational learning, interactive topic-wise quizzes
- **AI Integration:** Gemini AI-powered educational chatbot with adaptive recommendations and instant evaluation
- **Analytics:** Teacher dashboard with student engagement tracking, learning progress monitoring, and performance insights
- **Infrastructure:** Firebase Authentication and Firestore data management with Student, Teacher, and Admin roles
- **Accessibility:** Customization panel with text-to-speech via Web Speech API and gamified learning experience

</details>

---

## Professional Experience

**Infosys Springboard** — Virtual Intern, Python Full Stack Development  
*November 2025 – January 2026*

Built a distributed log analytics system for processing, analyzing, and visualizing system logs at scale.

- Developed automated log parsing and processing workflows using **PySpark** and **Apache Spark**
- Implemented anomaly detection and error trend reporting with **Spark DataFrames**
- Built a **Streamlit**-based real-time monitoring dashboard for log and anomaly visualization

---

## Achievements & Certifications

**Achievements**

- 🏆 3rd Runner-Up — **TechXcelerate Hackathon** (CSE AI & ML Department, LBRCE)
- 📊 205+ LeetCode problems solved — earned **50 Days** and **100 Days** badges in 2026
- ☁️ **Oracle Cloud Infrastructure Foundations Associate** certified

<br/>

**Certifications**

| Certification | Issuer | Year |
|:-------------|:-------|:----:|
| Oracle Cloud Infrastructure Foundations Associate | Oracle | 2025 |
| Python Essentials Programming | Cisco Networking Academy | 2024 |
| C Programming | Cisco Networking Academy | 2024 |
| Problem Solving Through C Programming | NPTEL | 2025 |
| Foundations of R Software (Elite) | NPTEL | 2025 |

---

## GitHub Analytics

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=nagasanthoshnikhil040507&show_icons=true&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=58a6ff&border_color=30363d&include_all_commits=true&count_private=true"/>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=nagasanthoshnikhil040507&show_icons=true&include_all_commits=true&count_private=true"/>
    <img src="https://github-readme-stats.vercel.app/api?username=nagasanthoshnikhil040507&show_icons=true&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&icon_color=58a6ff&border_color=30363d&include_all_commits=true&count_private=true" alt="GitHub Stats" height="180"/>
  </picture>
  &nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=nagasanthoshnikhil040507&layout=compact&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&border_color=30363d"/>
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=nagasanthoshnikhil040507&layout=compact"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nagasanthoshnikhil040507&layout=compact&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3&border_color=30363d" alt="Top Languages" height="180"/>
  </picture>
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=nagasanthoshnikhil040507&theme=transparent&hide_border=false&border=30363d&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=e6edf3&sideNums=e6edf3"/>
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=nagasanthoshnikhil040507&theme=default"/>
    <img src="https://streak-stats.demolab.com/?user=nagasanthoshnikhil040507&theme=transparent&hide_border=false&border=30363d&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=8b949e&dates=8b949e&currStreakNum=e6edf3&sideNums=e6edf3" alt="GitHub Streak Stats" width="480"/>
  </picture>
</div>

---

<div align="center">
  <sub>Open to internship and collaboration opportunities · 2028 Graduate</sub>
  <br/><br/>
  <img src="https://komarev.com/ghpvc/?username=nagasanthoshnikhil040507&style=flat-square&color=30363d&label=Profile+Views" alt="Profile Views"/>
</div>
