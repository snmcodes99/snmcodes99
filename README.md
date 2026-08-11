<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0d1117&height=2" />

<br/>

<h1>
  <code>Sahil Negi</code>
</h1>

<h3>Backend & Full-Stack Developer</h3>

<p>
  <img src="https://img.shields.io/badge/-B.Tech%20CSE-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
  <img src="https://img.shields.io/badge/-Backend%20Focused-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
  <img src="https://img.shields.io/badge/-Open%20to%20Internships-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
</p>

<br/>

<a href="https://github.com/snmcodes99">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=520&lines=building+systems+that+don't+fall+over+under+load_;designing+for+concurrency%2C+not+just+the+happy+path_;currently+shipping%3A+MarketHub_" alt="typing animation" />
</a>

</div>

<br/>

    $ whoami

I'm Sahil — a backend-leaning full-stack developer focused on designing systems that
are correct under concurrency, not just correct on the happy path. I care about
clean API design, data modeling that survives real usage, and code that a teammate
can read without a walkthrough. Currently building toward backend engineering roles
at startups and product-based companies.

<br/>

<table width="100%">
<tr>
<td width="50%" valign="top">

**Currently building**
MarketHub — a multi-vendor e-commerce backend

</td>
<td width="50%" valign="top">

**Currently sharpening**
System design, PostgreSQL depth, DSA

</td>
</tr>
</table>

<br/>

## `tech_stack`

<table width="100%">
<tr>
<td width="20%"><strong>Languages</strong></td>
<td width="80%">
<img src="https://img.shields.io/badge/-C++-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-JavaScript-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-TypeScript-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
</td>
</tr>
<tr>
<td valign="top"><strong>Backend</strong></td>
<td>
<img src="https://img.shields.io/badge/-Node.js-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
<img src="https://img.shields.io/badge/-Express-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
<img src="https://img.shields.io/badge/-REST%20APIs-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
</td>
</tr>
<tr>
<td valign="top"><strong>Data</strong></td>
<td>
<img src="https://img.shields.io/badge/-MongoDB-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-PostgreSQL-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-Redis-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
</td>
</tr>
<tr>
<td valign="top"><strong>Frontend</strong></td>
<td>
<img src="https://img.shields.io/badge/-React-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
<img src="https://img.shields.io/badge/-HTML/CSS-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
</td>
</tr>
<tr>
<td valign="top"><strong>Infra & Tools</strong></td>
<td>
<img src="https://img.shields.io/badge/-Docker-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-AWS-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-Git-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
<img src="https://img.shields.io/badge/-GitHub%20Actions-0d1117?style=flat-square&labelColor=0d1117&color=22d3ee" />
</td>
</tr>
<tr>
<td valign="top"><strong>Core</strong></td>
<td>
<img src="https://img.shields.io/badge/-System%20Design-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
<img src="https://img.shields.io/badge/-Data%20Structures%20%26%20Algorithms-0d1117?style=flat-square&labelColor=0d1117&color=34d399" />
</td>
</tr>
</table>

<br/>

## `featured_projects`

<table width="100%">
<tr>
<td width="50%" valign="top">

### MarketHub

Multi-vendor e-commerce backend built for real-world traffic patterns — vendor
onboarding, catalog management, order orchestration, and payments in one system.

`Node.js` `Express` `MongoDB` `Redis` `Razorpay` `Docker` `AWS`

<sub>Flagship project · deployment in progress</sub>

</td>
<td width="50%" valign="top">

### EventFlow

Event management platform handling scheduling, registration, and real-time
capacity/status tracking for multi-session events.

`Node.js` `Express` `MongoDB` `REST APIs`

<sub>Backend-first architecture</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### EV Charging Optimizer

System for modeling and optimizing EV charging station allocation — balancing
load distribution, availability, and scheduling logic.

`Node.js` `PostgreSQL` `System Design`

<sub>Optimization-focused backend</sub>

</td>
<td width="50%" valign="top">

### Decentralized Voting System

Voting system exploring tamper-resistant, verifiable vote recording without a
central point of trust.

`Node.js` `Blockchain Concepts` `Express`

<sub>Integrity & verifiability focus</sub>

</td>
</tr>
</table>

<br/>

<details>
<summary><strong>Architecture notes & design decisions</strong></summary>
<br/>

Each project above is built with a deliberate focus on the backend fundamentals
that tend to get skipped in portfolio projects:

- **Data modeling first** — schemas designed around actual query patterns, not just CRUD convenience
- **Concurrency-aware** — considering race conditions and locking where money or state consistency is involved
- **Deployability** — containerized with Docker, CI via GitHub Actions, deployed on AWS rather than left running locally
- **Documented decisions** — architectural tradeoffs recorded, not just code

</details>

<br/>

## `current_focus`

    [x] Multi-vendor backend architecture (MarketHub)
    [x] Payment gateway integration
    [ ] PostgreSQL — deeper relational modeling & query optimization
    [ ] Load testing & concurrency validation under real traffic
    [ ] DSA — consistent problem-solving practice
    [ ] System design — case studies & tradeoff analysis

<br/>

<details>
<summary><strong>What I'm optimizing for right now</strong></summary>
<br/>

Right now the focus is depth over breadth — fewer projects, each one taken to a
state where it's actually deployed, load-tested, and defensible in a technical
interview. Backend engineering roles at startups and product-based companies are
the target, with system design and SQL depth as the current gaps being closed.

</details>

<br/>

## `stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=snmcodes99&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=34d399&text_color=c9d1d9&hide_rank=true" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=snmcodes99&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=c9d1d9&langs_count=6" height="165" />

</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=snmcodes99&theme=dark&hide_border=true&background=0d1117&ring=22D3EE&fire=34D399&currStreakLabel=22D3EE" height="165" />
</div>

<sub><i>These cards render as live SVGs from an external stats service — they refresh on their own each time your profile is viewed, no action needed from you.</i></sub>

<br/>

<details>
<summary><strong>Contribution activity (animated)</strong></summary>
<br/>

<div align="center">
<img src="https://raw.githubusercontent.com/snmcodes99/snmcodes99/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation" width="100%" />
</div>

<sub>Requires a one-time GitHub Actions workflow (`Platane/snk`) on your profile repo to generate this file — see setup note below.</sub>

</details>

<br/>

## `connect`

<table width="100%">
<tr>
<td width="33%" align="center">

**GitHub**
[@snmcodes99](https://github.com/snmcodes99)

</td>
<td width="33%" align="center">

**LinkedIn**
`add your link`

</td>
<td width="33%" align="center">

**Email**
`add your email`

</td>
</tr>
</table>

<br/>

<div align="center">
<sub><code>build_status: shipping</code></sub>
</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0d1117&height=2" />

<br/>

<details>
<summary><sub>Setup notes (remove before publishing)</sub></summary>
<br/>

- **Typing header / stat cards** — these are `<img>` tags pointing to free public services (`readme-typing-svg`, `github-readme-stats`, `github-readme-streak-stats`). They already work with your `snmcodes99` username, no setup required, but response time can be slow on first load since the images render on-demand.
- **Contribution snake animation** — this one needs a tiny one-time setup: add the `Platane/snk` GitHub Action to a repo named exactly `snmcodes99` (a special "profile README" repo). It runs on a schedule and generates the SVG this README points to. Instructions: `github.com/Platane/snk`. Until that's set up, that image will show broken.
- All `<details>` blocks above are native GitHub Markdown — they genuinely expand/collapse on click, no service required.

</details>
