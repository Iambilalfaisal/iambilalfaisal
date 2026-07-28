<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg" />
  <img alt="Bilal Faisal — AI Architect & Data Scientist hero banner" src="assets/hero-dark.svg" width="100%" />
</picture>

<div align="center">

![Location](https://img.shields.io/badge/Location-Lahore%2C%20Pakistan-0D1117?style=flat-square&labelColor=2F81F7&color=0D1117)
![Role](https://img.shields.io/badge/Role-Associate%20Software%20Engineer%20%40%20Acme%20One-0D1117?style=flat-square&labelColor=2F81F7&color=0D1117)
![Education](https://img.shields.io/badge/B.S.%20Data%20Science-UMT%20Lahore%20%E2%80%A2%206th%20Sem-0D1117?style=flat-square&labelColor=2F81F7&color=0D1117)
![Certification](https://img.shields.io/badge/Certifying-AI--103%20(Azure%20AI%20Foundry)-0D1117?style=flat-square&labelColor=2F81F7&color=0D1117)
![Open to Work](https://img.shields.io/badge/Open%20to-Remote%20%2F%20Full--Time%20Roles-0D1117?style=flat-square&labelColor=2F81F7&color=0D1117)

</div>

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 👋 About

I'm a Data Scientist and Associate Software Engineer focused on architecting intelligent, production-grade systems — I care more about pipelines that ship than ones that only work in a notebook. At **Acme One**, I contribute individually to **Nucleus One**, the company's core multi-module enterprise platform, after building my foundation by shadowing senior engineers across other internal systems. Independently, I'm designing a Retrieval-Augmented Generation platform aimed at solving document-heavy bottlenecks for professional services and local firms. I'm currently deepening that expertise toward the Microsoft **AI-103** (Azure AI Apps & Agents) certification.

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 📡 Core Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET%20%2F%20C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Laragon](https://img.shields.io/badge/Laragon-3C873A?style=flat-square&logo=windows&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 🚀 Projects

> ⭐ **If any of these save you time or teach you something, a star helps more than you'd think** — it's what makes them discoverable to the next person who needs them.

**MFA Authentication Server** — Information Security capstone
[![Stars](https://img.shields.io/github/stars/Iambilalfaisal/Multi-Factor-Authentication-Protocols?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Multi-Factor-Authentication-Protocols/stargazers)
[![Forks](https://img.shields.io/github/forks/Iambilalfaisal/Multi-Factor-Authentication-Protocols?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Multi-Factor-Authentication-Protocols/network/members)

Want to actually understand how TOTP/HOTP work instead of just importing a library that does it for you? Every OTP algorithm here is implemented straight from the RFC spec, by hand.

- **HOTP (RFC 4226) and TOTP (RFC 6238) implemented from the spec** — validated against `pyotp` as an independent test oracle, never used in production code
- AES-256-GCM encrypted secret vault, Argon2id password hashing, real WebAuthn/FIDO2 attestation and assertion verification
- **AI anomaly-detection layer** — IsolationForest scoring over login features (geo distance, impossible travel, new device, unusual hour) with Claude-generated plain-language alerts
- Streamlit admin dashboard for users, auth logs, and anomaly alerts

**Repo:** [Multi-Factor-Authentication-Protocols](https://github.com/Iambilalfaisal/Multi-Factor-Authentication-Protocols)

<br/>

**Document Intelligence Platform for Professional Services** *(In Development)*
[![Stars](https://img.shields.io/github/stars/Iambilalfaisal/Project-Ease?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Project-Ease/stargazers)
[![Forks](https://img.shields.io/github/forks/Iambilalfaisal/Project-Ease?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Project-Ease/network/members)

Ask your firm's own documents a question in plain English and get a cited answer back — instead of digging through folders. Built for law firms and accounting practices buried in paperwork.

- **Retrieval** — Azure AI Search over indexed firm documents
- **Generation** — Azure OpenAI Service, grounded strictly in retrieved context
- **Ingestion** — Azure AI Document Intelligence + Blob Storage for multi-format document processing
- **Trust layer** — inline citations back to source paragraphs on every answer
- **Access control** — Microsoft Entra identity integration

Built on top of Microsoft's production RAG reference architecture, which I forked and am extending toward this vertical use case.
**Repo:** [Project-Ease](https://github.com/Iambilalfaisal/Project-Ease)

<br/>

**Automated Information Security Risk Assessment Platform** — UMT InfoSec semester project, Spring 2026
[![Stars](https://img.shields.io/github/stars/Iambilalfaisal/Automated-Information-Security-Risk-Assessment-Platform?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Automated-Information-Security-Risk-Assessment-Platform/stargazers)
[![Forks](https://img.shields.io/github/forks/Iambilalfaisal/Automated-Information-Security-Risk-Assessment-Platform?style=flat-square&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal/Automated-Information-Security-Risk-Assessment-Platform/network/members)

Turns a NIST SP 800-30 risk assessment from a spreadsheet exercise into a working app — asset inventory, live CVE matching, and auto-generated reports. Handy if you're studying for a security certification or building your first GRC tool.

- Risk engine covering asset, threat, and vulnerability management with live **CVE lookups via the NVD API**
- **LLM-generated control recommendations** (Claude, with a rule-based fallback when no API key is configured)
- Automated PDF reporting — risk register, cost-benefit analysis, and compliance checklists
- Flask REST API backing a Streamlit UI, with a React frontend also included

**Repo:** [Automated-Information-Security-Risk-Assessment-Platform](https://github.com/Iambilalfaisal/Automated-Information-Security-Risk-Assessment-Platform)

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 💼 Experience

**Acme One** · Lahore, Pakistan · 1 yr+

**Associate Software Engineer** · Full-time · Mar 2026 – Present
Contributing independently on **Nucleus One** — a production enterprise platform built on a React 18/TypeScript frontend and ASP.NET Core 8 / SQL Server backend — as one of the most active engineers on a 7-person team, #2 by commit volume across both repositories.

- **End-to-end delivery:** built **Project-One** entirely — database schema, backend logic, and frontend, including core workflow components like the work item management drawer
- **Service architecture:** authored core **HR module** services — employee onboarding, offboarding, and evaluation workflows — plus its database schema deployment
- **Platform security:** built the **authentication controller** for the Nucleus One core platform
- **Production deployment:** took **TimeTrace** to production, including its backend reporting engine

**Artificial Intelligence Intern** · Jul 2025 – Mar 2026
Engineered and deployed a Retrieval-Augmented Generation (RAG) chatbot directly into Nucleus One, enabling natural-language interaction with internal company data — the internship converted into the full-time Associate Software Engineer role above.

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 📜 Certifications

- **AI-103** — Designing and Implementing a Microsoft Azure AI Solution *(in progress)*
- **Claude Code in Action** — Anthropic, 2026
- **Claude Code 101** — Anthropic, 2026
- **AI Fluency Framework & Foundations** — Anthropic, 2026
- **AI Capabilities and Limitations** — Anthropic, 2026
- **Claude 101** — Anthropic, 2026

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 📊 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Iambilalfaisal&show_icons=true&hide_border=true&bg_color=00000000&title_color=2F81F7&icon_color=2F81F7&text_color=C9D1D9&hide_title=false" width="49%" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Iambilalfaisal&layout=compact&hide_border=true&bg_color=00000000&title_color=2F81F7&text_color=C9D1D9" width="42%" alt="Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=Iambilalfaisal&hide_border=true&background=00000000&ring=2F81F7&fire=2F81F7&currStreakLabel=2F81F7" width="60%" alt="GitHub Streak" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Iambilalfaisal&hide_border=true&bg_color=00000000&color=2F81F7&line=2F81F7&point=06B6D4&area=true&area_color=2F81F7" width="90%" alt="Activity Graph" />

</div>

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

<div align="center">

<img alt="3D contribution cityscape" src="profile-3d-contrib/profile-night-view.svg" width="90%" />
<sub>3D isometric render of my commit history</sub>

<br/><br/>

<img alt="Jet flying over GitHub contribution heatmap" src="dist/github-jet.svg" width="90%" />
<sub>A jet flying over my real contribution grid, firing on the busiest days</sub>

</div>

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 🧬 Life & Code

Discipline outside the IDE is the same discipline that ships code on time.

| 🏋️ Training | 📚 Currently Reading | 🌍 Beyond the Desk |
| :--- | :--- | :--- |
| A two-muscle-group split, every session, chasing real strength and physique — currently in training for a marathon, with an actual finish position in mind, not just finishing. | *The Psychology of Money*, *Rich Dad Poor Dad*, *Genius Makers*, *The Subtle Art of Not Giving a F*ck*, plus books on dark psychology and persuasion. | Cricket, futsal, football, badminton, table tennis. Speak English, Punjabi, and Urdu, and read Arabic. Big on travel, cars, and multitasking by default. |

> "Sab bikta hai, sab khareedoon ga." — everything is for sale, and I'll buy it all.

<div align="center"><img src="assets/divider.svg" width="100%" height="4" alt="" /></div>

## 📫 Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-pi-peach-78.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/m-bilal-faisal-7274b927b/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/ibiilal)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Bilalfaisal100@gmail.com)

[![Follow](https://img.shields.io/github/followers/Iambilalfaisal?style=for-the-badge&logo=github&color=2F81F7&labelColor=0D1117)](https://github.com/Iambilalfaisal?tab=followers)

</div>
