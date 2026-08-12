<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d0d,50:1a0500,100:F77F00&height=220&section=header&text=Bhanuprakash%20Reddy%20K&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Co-Founder%20%26%20Tech%20Lead%20%40%20NexSyrus%20Pvt.%20Ltd.&descAlignY=56&descSize=18&descColor=F77F00" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3200&pause=1200&color=F77F00&center=true&vCenter=true&width=680&lines=Building+multi-tenant+SaaS+for+Tier+2%2F3+Bharat;React+Native+%C2%B7+Node.js+%C2%B7+Supabase+%C2%B7+PostgreSQL;Shipping+SchoolIMS+%C2%B7+PaperForge+%C2%B7+Medical+POS+%C2%B7+IVF+HMS" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/DPIIT-Startup_India_Recognized-F77F00?style=for-the-badge&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/LOCATION-Telangana,_India-F77F00?style=for-the-badge&labelColor=0d0d0d&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/STATUS-Open_to_Collabs-F77F00?style=for-the-badge&labelColor=0d0d0d"/>

</div>

<br/>

<div align="center">

<table border="0">
<tr>
<td align="center" width="150"><h2>6</h2><sub><b>Products Built</b></sub></td>
<td align="center" width="150"><h2>5</h2><sub><b>Live Domains</b></sub></td>
<td align="center" width="150"><h2>10+</h2><sub><b>Schools Live</b></sub></td>
<td align="center" width="150"><h2>3K+</h2><sub><b>Students Served</b></sub></td>
<td align="center" width="150"><h2>0→1</h2><sub><b>SaaS from Scratch</b></sub></td>
</tr>
</table>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 01 · Identity

<table>
<tr>
<td width="58%" valign="top">

```js
const bhanu = {
  name       : "Bhanuprakash Reddy K",
  role       : "Co-Founder & Tech Lead",
  company    : "NexSyrus Pvt. Ltd.",
  location   : "Telangana, India 🇮🇳",
  recognition: "DPIIT Startup India",

  currentFocus: [
    "SchoolIMS   — scaling multi-tenant RLS + payments",
    "PaperForge  — RAG/LLM question paper engine",
    "IVF HMS     — white-label hospital management",
    "Founder Console — multi-Supabase fleet ops",
  ],

  stack: {
    mobile  : ["React Native", "Expo", "TypeScript"],
    backend : ["Node.js", "Express", "NestJS", "Supabase"],
    database: ["PostgreSQL", "pgvector", "MongoDB"],
    infra   : ["Docker", "GitHub Actions", "Tauri", "Render"],
  },

  philosophy: "Build things that survive contact with a ₹10,000 Android phone.",
  openTo    : ["Collabs", "Consulting", "Contracts"],
};
```

</td>
<td width="42%" align="center" valign="top">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="260" style="border-radius:16px"/>

</td>
</tr>
</table>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 02 · Engineering Arsenal

**Frontend & Mobile**
<p align="left">
<img src="https://skillicons.dev/icons?i=react,ts,js,nextjs,html,css,tailwind,figma&theme=dark"/>
</p>

**Backend & Database**
<p align="left">
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,supabase,postgres,mongodb,prisma,redis&theme=dark"/>
</p>

**DevOps & Tooling**
<p align="left">
<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions,linux,vscode,postman,firebase&theme=dark"/>
</p>

**Languages**
<p align="left">
<img src="https://skillicons.dev/icons?i=js,ts,python,kotlin,cpp,bash&theme=dark"/>
</p>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 03 · Flagship Builds

<details open>
<summary><b>🏫 SchoolIMS — Multi-Tenant School Management SaaS</b> <sub>(flagship)</sub></summary>
<br/>

Production platform digitizing school operations end-to-end — currently live across 10+ schools serving 3,000+ students.

- `schema.sql`-driven multi-tenant RLS isolation; `school_id` always derived server-side from JWT, never trusted from the client
- Cashfree payment gateway per-school merchant accounts, AES-256-GCM encrypted credentials, HMAC-verified webhooks
- Per-school EAS build pipeline (Expo APKs) plus a Tauri-packaged Windows desktop app, both on GitHub Actions CI
- Feature-flag system with server-side enforcement, multi-account "Instagram-style" login, Telugu multilingual push notifications

**Stack:** React Native · Expo · Node.js · Supabase · PostgreSQL

</details>

<details>
<summary><b>📝 PaperForge — RAG/LLM Question Paper Engine</b></summary>
<br/>

Generates exam question papers on a retrieval-augmented generation stack, built for accuracy against a locked academic taxonomy.

- RAG engine on pgvector with a dual-DB split — operational DB and a write-only training corpus
- Bloom's taxonomy vocabulary locked into generation to keep question difficulty consistent
- Claymorphic UI, built out through a phased 5B–11 delivery plan

**Stack:** Node.js · pgvector · PostgreSQL · LLM APIs

</details>

<details>
<summary><b>💊 Medical POS — Pharmacy & Clinic Management</b></summary>
<br/>

Point-of-sale and operations system for pharmacies and clinics.

- Rebuilt from scratch as server-first (online-first with optimistic UI), removing offline-sync complexity entirely
- Unified POS, inventory, and clinic workflow in one system

**Stack:** React Native / Web · Node.js · Supabase

</details>

<details>
<summary><b>🏥 IVF HMS — White-Label Fertility & IVF Hospital Management</b></summary>
<br/>

Premium hospital management system for fertility clinics, built as one shared product with per-hospital branding.

- Universal codebase across Android, iOS, tablet, and web
- Serves doctors, embryologists, nurses, counsellors, front-desk, pharmacists, billing staff, and patients in one workflow
- Clinically professional claymorphism/glassmorphism UI — engineered to hold up on low-end Android and weak networks

**Stack:** React Native Expo · TypeScript · NestJS

</details>

<details>
<summary><b>🖥️ Founder Console — Internal Ops Dashboard</b></summary>
<br/>

Manages NexSyrus's own multi-product SaaS fleet.

- Cluster architecture across six migrated phases to manage multiple Supabase instances
- GST billing engine — tax invoices vs. plain receipts, sequential invoice numbering with row-level locking
- HubSpot CRM integration across 18 API routes with a full financial audit trail

**Stack:** Next.js · Supabase · PostgreSQL · HubSpot CRM

</details>

<details>
<summary><b>⚡ DispatchFlow — Bulk WhatsApp Credential Dispatch</b></summary>
<br/>

Single-file, offline-first tool for handing out student login credentials at scale.

- Zero backend — no server, no data persistence, nothing sent automatically; the operator still taps send
- Imports Excel/CSV/TSV/JSON or pasted rows, auto-maps school credential formats, opens prefilled `wa.me` links one record at a time

**Stack:** Vanilla HTML/JS · SheetJS

</details>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 04 · Engineering Signal

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bhanreddy&show_icons=true&theme=transparent&hide_border=true&title_color=F77F00&icon_color=F77F00&text_color=ffffff&bg_color=0d0d0d&ring_color=F77F00&border_radius=20&include_all_commits=true&count_private=true" height="180"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=bhanreddy&theme=transparent&hide_border=true&background=0d0d0d&ring=F77F00&fire=F77F00&currStreakLabel=F77F00&sideLabels=ffffff&dates=888888&stroke=F77F00&border_radius=20" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bhanreddy&layout=donut&theme=transparent&hide_border=true&title_color=F77F00&text_color=ffffff&bg_color=0d0d0d&border_radius=20&langs_count=8" height="200"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=bhanreddy&bg_color=0d0d0d&color=F77F00&line=F77F00&point=ffffff&area=true&hide_border=true&border_radius=20&area_color=F77F00" width="100%"/>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 05 · Languages

<div align="center">

<img src="https://img.shields.io/badge/English-Fluent-F77F00?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Telugu-Native-F77F00?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Kannada-Fluent-F77F00?style=flat-square&labelColor=0d0d0d"/>
<img src="https://img.shields.io/badge/Hindi-Conversational-F77F00?style=flat-square&labelColor=0d0d0d"/>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 06 · Beyond Code

<div align="center">

<table>
<tr>
<td align="center" width="200">🏋️<br/><b>Fitness First</b><br/><sub>Body recomp · progressive overload</sub></td>
<td align="center" width="200">🍳<br/><b>Professional Chef</b><br/><sub>Cooking, baking, regional recipes</sub></td>
<td align="center" width="200">📺<br/><b>TFI & Films</b><br/><sub>Storytelling · world-building</sub></td>
<td align="center" width="200">📖<br/><b>Deep Reader</b><br/><sub>System design · startup strategy</sub></td>
</tr>
</table>

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0d0d0d&height=2&section=header" width="100%"/>
</div>

## 07 · Connect

<div align="center">

Have a hard product or engineering problem worth solving? Let's build something that deserves to exist.

<a href="https://nexsyrus.com"><img src="https://img.shields.io/badge/Website-nexsyrus.com-F77F00?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d0d0d"/></a>
<a href="https://github.com/bhanreddy"><img src="https://img.shields.io/badge/GitHub-bhanreddy-F77F00?style=for-the-badge&logo=github&logoColor=white&labelColor=0d0d0d"/></a>

<sub>_LinkedIn / email / Twitter badges intentionally left out — drop the handles in and I'll wire them up._</sub>

</div>

<br/>

<div align="center">

> **"Don't just write code. Build systems that outlast you."**
> — Bhanu

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F77F00,50:1a0500,100:0d0d0d&height=150&section=footer"/>
