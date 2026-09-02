<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a3a,100:58E1C1&height=180&section=header&text=ERDENE.K&fontSize=64&fontColor=58E1C1&fontAlignY=38&desc=backend%20systems%20%C2%B7%20fintech%20%C2%B7%20zero%20drama&descAlignY=60&descSize=18&animation=fadeIn&fontAlign=50">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffffff,50:d9f7ef,100:58E1C1&height=180&section=header&text=ERDENE.K&fontSize=64&fontColor=0d1117&fontAlignY=38&desc=backend%20systems%20%C2%B7%20fintech%20%C2%B7%20zero%20drama&descAlignY=60&descSize=18&animation=fadeIn&fontAlign=50" width="100%" alt="ERDENE.K — backend systems · fintech · zero drama">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=24&duration=2600&pause=900&color=58E1C1&center=true&vCenter=true&width=640&lines=%3E+booting+erdene.k+v4.0...;%3E+Senior+Backend+Developer+%40+Tavan+Bogd+NBFI;%3E+500%2C000%2B+users.+All+systems+operational.;%3E+Building+the+systems+behind+the+money_">
  <img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=24&duration=2600&pause=900&color=0F8F7A&center=true&vCenter=true&width=640&lines=%3E+booting+erdene.k+v4.0...;%3E+Senior+Backend+Developer+%40+Tavan+Bogd+NBFI;%3E+500%2C000%2B+users.+All+systems+operational.;%3E+Building+the+systems+behind+the+money_" alt="Senior Backend Developer at Tavan Bogd NBFI. 500,000+ users. Building the systems behind the money.">
</picture>

<br/><br/>

<img src="https://img.shields.io/badge/%F0%9F%93%8D-Ulaanbaatar%2C_MN-0d1117?style=flat-square&labelColor=0d1117&color=1f2937" alt="Ulaanbaatar, Mongolia" />
<img src="https://img.shields.io/badge/%F0%9F%95%97-UTC%2B8-0d1117?style=flat-square&labelColor=0d1117&color=1f2937" alt="UTC+8" />
<img src="https://img.shields.io/badge/status-open_to_senior_backend_%26_fintech_roles-58E1C1?style=flat-square&labelColor=0d1117" alt="Open to senior backend and fintech roles" />
<img src="https://komarev.com/ghpvc/?username=erdene-k&style=flat-square&color=58E1C1&label=visitors&labelColor=0d1117" alt="Profile visitors" />

</div>

<br/>

```console
┌──────────────────────────────────────────────────────────────────┐
│  SYS.00 — BOOT SEQUENCE                                          │
├──────────────────────────────────────────────────────────────────┤
│  [ OK ] payments ........................ clearing               │
│  [ OK ] loans ........................... disbursing             │
│  [ OK ] documents ....................... generating             │
│  [ OK ] pdf-extraction middleware ....... parsing                │
│  [ OK ] code review ..................... nitpicking (lovingly)  │
├──────────────────────────────────────────────────────────────────┤
│  uptime: 4+ yrs in prod · users: 500,000+ · incidents: handled   │
└──────────────────────────────────────────────────────────────────┘
```

> [!TIP]
> **2026 focus:** payment infrastructure that fails loudly, retries safely, and never charges anyone twice.

<br/>

## `SYS.01 — whoami`

<table>
<tr>
<td width="55%" valign="top">

```console
$ whoami
erdene.k — backend engineer in fintech

$ cat mission.txt
Most of my work is invisible — and that's
the point. Good backend engineering means
payments clear, loans disburse, and documents
generate without anyone thinking about how.

$ history | tail -3
  frontend  → shipped a mobile loan app to 500K users
  deeper    → payment gateways, doc generation
  deepest   → PDF data-extraction for SME credit scoring
```

</td>
<td width="45%" valign="top">

```jsonc
{
  "name":      "Erdenechuluun Kh",
  "role":      "Senior Backend Developer",
  "at":        "Tavan Bogd NBFI",
  "domain":    ["fintech", "payments", "lending"],
  "does":      [
    "leads code reviews",
    "sets system standards",
    "keeps the money moving"
  ],
  "superpower": "turning manual back-office pain
                 into a service call",
  "fun_fact":  "led the winning team at Mongolia's
                 largest corporate hackathon 🥇"
}
```

</td>
</tr>
</table>

> I started in frontend, then moved down the stack. That path means I design APIs the way the people consuming them *wish* they were designed.

<br/>

## `SYS.02 — stack`

<div align="center">

**`// backend — where I live`**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java,spring,nodejs,ts,express&theme=dark">
  <img src="https://skillicons.dev/icons?i=java,spring,nodejs,ts,express&theme=light" alt="Java, Spring Boot, Node.js, TypeScript, Express" height="48">
</picture>

**`// frontend & mobile — where I came from`**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react,angular,flutter,sass&theme=dark">
  <img src="https://skillicons.dev/icons?i=react,angular,flutter,sass&theme=light" alt="React, React Native, Angular, Flutter, Sass" height="48">
</picture>

**`// infra & data — where it runs`**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=aws,docker,postgres,mongodb,git,linux&theme=dark">
  <img src="https://skillicons.dev/icons?i=aws,docker,postgres,mongodb,git,linux&theme=light" alt="AWS, Docker, PostgreSQL, MongoDB, Git, Linux" height="48">
</picture>

<br/>

<sub>Plus the unglamorous stuff: payment gateways · banking APIs · loan origination · document generation · PDF processing · microservices · CI/CD</sub>

</div>

<br/>

## `SYS.03 — how a payment moves`

The thing I think about most. One payment, one bank that stops answering, and the idempotency key that makes sure the customer pays exactly once.

```mermaid
sequenceDiagram
    autonumber
    participant App as 📱 Customer app
    participant GW as 🔀 Payment gateway
    participant Bank as 🏦 Bank
    participant Ledger as 📒 Ledger

    App->>GW: POST /pay  (Idempotency-Key: 7f3a…)
    GW->>Bank: authorize
    Note over Bank: … silence …
    Bank--xGW: timeout
    GW->>Bank: authorize  (same key, retry #1)
    Bank-->>GW: 200 approved
    GW->>Ledger: record once
    GW-->>App: 201 Created
    App->>GW: POST /pay  (same key — customer double-tapped)
    GW-->>App: 201 Created  (echoed, bank never called)
```

> [!NOTE]
> The [full interactive version](https://erdene-k.github.io/portofolio/) lets you switch between *the bank goes quiet*, *the customer double-taps*, and *nothing goes wrong*.

<br/>

## `SYS.04 — selected work`

| ID | Project | The story | Impact | Stack |
|:--:|---------|-----------|:------:|-------|
| `001` | **PayOn v2** | Mobile loan app — loyalty, integrations, full lending flow end to end | 👥 **500K+ users** | `React Native` `Payment gateway` |
| `002` | **Bank-statement intelligence** | Middleware that reads tabular data out of bank-statement PDFs and turns manual SME underwriting into a single API call | ⚡ manual → API | `Java` `PDF extraction` |
| `003` | **FC Parcel** | Travelers meet parcel senders — payments, tracking, matching. Built end-to-end as a BSc thesis in Paris | 🎓 thesis | `Angular` |
| `004` | **CyberGame** | Teaches people to spot phishing before phishing spots them | 🛡️ security edu | `Flutter` |

<details>
<summary><b>🧪 side experiments</b> — <i>click to expand</i></summary>
<br/>

| | | |
|--|--|--|
| 🌐 | **[Portfolio](https://erdene-k.github.io/portofolio/)** | Hand-built with vanilla HTML/CSS/JS. A payment sequence diagram you can break, and a box of tool chips with real physics. No frameworks were harmed. |
| 🔮 | **[Three.js with HDR](https://erdene-k.github.io/realism)** | Chasing photorealism in the browser, one render pass at a time. |

</details>

<br/>

## `SYS.05 — telemetry`

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=erdene-k&theme=tokyonight">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=erdene-k&theme=default" alt="GitHub profile details" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=erdene-k&theme=tokyonight">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=erdene-k&theme=default" alt="Repos per language" width="49%">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=erdene-k&theme=tokyonight">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=erdene-k&theme=default" alt="Most committed language" width="49%">
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=erdene-k&theme=tokyonight&hide_border=true&background=0d1117&ring=58E1C1&fire=58E1C1&currStreakLabel=58E1C1">
  <img src="https://streak-stats.demolab.com/?user=erdene-k&hide_border=true&background=ffffff&ring=0F8F7A&fire=0F8F7A&currStreakLabel=0F8F7A&currStreakNum=0d1117&sideNums=0d1117&sideLabels=0F8F7A&dates=6b7280" alt="Contribution streak">
</picture>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/erdene-k/erdene-k/output/github-contribution-grid-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/erdene-k/erdene-k/output/github-contribution-grid-snake.svg" alt="Contribution snake" width="100%">
</picture>

</div>

<br/>

## `SYS.06 — initiate contact`

<div align="center">

```console
$ ./contact --with erdene.k
> Have a system that needs building — or fixing?
> Establishing secure channel...
```

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erdenechuluun-khuderchuluun-3926b2117/)
[![Gmail](https://img.shields.io/badge/Gmail-e63946?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tesoro.ec@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-58E1C1?style=for-the-badge&logo=githubpages&logoColor=black)](https://erdene-k.github.io/portofolio/)

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:58E1C1,50:1a3a3a,100:0d1117&height=110&section=footer&text=%C2%A9%202026%20ERDENE.K%20%E2%80%94%20all%20systems%20operational%20%E2%9C%85&fontSize=14&fontColor=58E1C1&fontAlignY=70">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:58E1C1,50:d9f7ef,100:ffffff&height=110&section=footer&text=%C2%A9%202026%20ERDENE.K%20%E2%80%94%20all%20systems%20operational%20%E2%9C%85&fontSize=14&fontColor=0d1117&fontAlignY=70" width="100%" alt="© 2026 ERDENE.K — all systems operational">
</picture>

</div>
