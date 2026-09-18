<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e293b&height=200&section=header&text=Muhammad%20Rafique&fontSize=48&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%26%20Mobile%20Developer%20%E2%80%94%20Building%20SaaS%20ERP%2FPOS%20for%20Pakistani%20Businesses&descAlignY=58&descSize=16&descColor=94a3b8" width="100%"/>

<br/>

<a href="https://github.com/RafiqueDev"><img src="https://img.shields.io/badge/GitHub-RafiqueDev-1e2327?style=for-the-badge&logo=github&logoColor=e2e8f0&labelColor=0f172a" /></a>
<a href="mailto:mrafique0658@gmail.com"><img src="https://img.shields.io/badge/Email-mrafique0658%40gmail.com-1e2327?style=for-the-badge&logo=gmail&logoColor=e2e8f0&labelColor=0f172a" /></a>
<img src="https://img.shields.io/badge/Based%20in-Karachi%2C%20Pakistan-1e2327?style=for-the-badge&logo=googlemaps&logoColor=e2e8f0&labelColor=0f172a" />

</div>

<br/>

## About

I design and build **multi-tenant SaaS ERP and POS systems for Pakistani businesses** — full-stack MERN applications with real business logic underneath the UI: multi-branch inventory, role-based access control, tenant-isolated data, PKR-native formatting, and audit trails, benchmarked against tools like QuickBooks Desktop for the UX bar. I also build the mobile side of these products in Flutter.

I care less about stacking technologies and more about whether the business logic actually holds up — invoice numbers that can't drift, billing engines with a single source of truth, and authorization checks that are enforced server-side, not just hidden in the UI.

**Currently building:** production-grade ERP/POS platforms for the timber wholesale and retail sector, and a general-purpose multi-tenant POS/ERP for wholesale & retail businesses.

<br/>

## Tech Stack

<div align="center">

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind" />

**Backend**

<img src="https://skillicons.dev/icons?i=nodejs,express,dotnet,php" />

**Mobile**

<img src="https://skillicons.dev/icons?i=flutter,dart" />

**Databases**

<img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,sqlite,redis" />

**Tools & Infra**

<img src="https://skillicons.dev/icons?i=git,github,docker,githubactions,vscode,socketio" />

</div>

<br/>

## Featured Projects

### 🧾 Smart POS ERP
**Enterprise-grade multi-tenant SaaS POS + ERP platform for wholesale and retail businesses**

Production-oriented system with a full offline-capable POS, multi-branch inventory, and a completely separate developer super-admin panel from the company-facing ERP dashboard.

| | |
|---|---|
| **Stack** | React 18 · Vite · Tailwind · Redux Toolkit · Node.js · Express · Socket.IO · MongoDB · Redis · BullMQ · Docker · React Native |
| **Architecture** | Nginx → React/Vite frontend + Express/Socket.IO backend → MongoDB, with Redis/BullMQ for queues and caching; mobile app talks to the same API |
| **Key capabilities** | Barcode-driven POS with offline hold/resume, real-time stock + dashboard via Socket.IO, multi-tenant data isolation enforced at the middleware layer (never trusted from the client), PWA offline sync (IndexedDB) for web and SQLite offline sync for mobile, JWT access + refresh token auth with RBAC and audit logging, license/activation management for the dev-admin panel |

**Repo:** [github.com/RafiqueDev/smart-pos-erp](https://github.com/RafiqueDev/smart-pos-erp)

---

### 🪵 Timber Storage Pro
**Full-stack, mobile-first, multi-branch Timber Warehouse & Storage Management System**

Tracks containers, stock, and storage rent (daily/monthly with an editable override), generates A5 invoices, handles partial payments and party statements, and enforces warehouse-scoped role-based access on every route — not just in the UI.

| | |
|---|---|
| **Stack** | React 18 · Vite · Tailwind · React Router · Node.js · Express · SQLite (better-sqlite3) · JWT · bcrypt |
| **Architecture** | Single central billing engine (`services/billing.js`) is the *only* place rent is ever calculated, so the dashboard, invoices, and reports can never drift apart from each other |
| **Key capabilities** | A self-service party portal with time-boxed magic-link access on a fully separate auth path from the admin app, banked-credit adjustments that auto-apply oldest-first on a party's next invoice, atomic concurrency-safe stock decrements, immutable invoice line-item snapshots, and a security-hardening pass that closed real warehouse-scoping authorization gaps |
| **Verified** | **46 automated tests** (`node --test`) covering billing math, auth/authorization, the party portal end-to-end, and undo/delete safety rules |

**Repo:** [github.com/RafiqueDev/timber-storage-pro](https://github.com/RafiqueDev/timber-storage-pro)

<br/>

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=RafiqueDev&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&count_private=true" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=RafiqueDev&theme=dark&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" height="165"/>

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=RafiqueDev&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="165"/>

</div>

<br/>

<div align="center">

### Contribution Graph

<img src="https://raw.githubusercontent.com/RafiqueDev/RafiqueDev/output/github-contribution-grid-snake-dark.svg" width="100%" />

<sub>Generated automatically on every push via the GitHub Action in <code>.github/workflows/snake.yml</code> — no manual updates needed.</sub>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:0f172a&height=100&section=footer" width="100%"/>
</div>
