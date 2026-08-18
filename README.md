<div align="center">

<img
src="./assets/banner.png"
width="100%"
alt="Sahil Negi - Backend & Full-Stack Developer"
/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=780&lines=%3E+building+systems+that+survive+real+traffic;%3E+designing+for+concurrency%2C+not+just+the+happy+path;%3E+backend+%7C+distributed+systems+%7C+system+design;%3E+build+%3E+solve+%3E+iterate+%3E+repeat" />

<br/><br/>

<img src="https://img.shields.io/badge/BACKEND-22D3EE?style=flat-square&labelColor=0D1117&color=0D1117" />
<img src="https://img.shields.io/badge/SYSTEM_DESIGN-22D3EE?style=flat-square&labelColor=0D1117&color=0D1117" />
<img src="https://img.shields.io/badge/DSA-34D399?style=flat-square&labelColor=0D1117&color=0D1117" />
<img src="https://img.shields.io/badge/OPEN_TO_INTERNSHIPS-34D399?style=flat-square&labelColor=0D1117&color=0D1117" />

</div>

---

## `> whoami`

```text
sahil@backend-engineer:~$ cat profile.txt

NAME        : Sahil Negi
ROLE        : Backend & Full-Stack Developer
FOCUS       : Backend Engineering / System Design
INTERESTS   : Concurrency / Distributed Systems / Data Modeling

────────────────────────────────────────────────────────────

I build systems that don't just work on the happy path.

I enjoy working on backend systems where architecture,
data modeling and reliability matter as much as the API itself.

My focus is on building clean APIs, designing systems around
real access patterns, handling concurrency and understanding
the tradeoffs behind production software.

Currently focused on strengthening backend engineering,
system design, PostgreSQL and distributed systems.
```

---

## `> engineering_stack`

<div align="center">

<table>
<tr>
<td align="center" width="180">

**LANGUAGES**

<img src="https://skillicons.dev/icons?i=cpp,js,ts,java" />

</td>

<td align="center" width="180">

**BACKEND**

<img src="https://skillicons.dev/icons?i=nodejs,express" />

</td>

<td align="center" width="180">

**DATABASES**

<img src="https://skillicons.dev/icons?i=mongodb,postgres,redis" />

</td>

<td align="center" width="180">

**INFRA**

<img src="https://skillicons.dev/icons?i=docker,aws" />

</td>
</tr>

<tr>
<td align="center">

**FRONTEND**

<img src="https://skillicons.dev/icons?i=react,html,css" />

</td>

<td align="center">

**TOOLS**

<img src="https://skillicons.dev/icons?i=git,githubactions" />

</td>

<td align="center">

**CORE**

`REST APIs`

`System Design`

</td>

<td align="center">

**PRACTICE**

`DSA`

`SQL`

</td>
</tr>
</table>

</div>

---

## `> featured_projects`

### `01 // MarketHub`

```text
COMPLETED · MULTI-VENDOR E-COMMERCE BACKEND
```

A production-oriented e-commerce backend designed around the
problems that appear once a simple CRUD application becomes
a real system.

MarketHub models the complete marketplace flow — from customer
authentication and seller onboarding to catalog management,
order processing and payment integration.

```text
                         MARKETPLACE
                              │
              ┌───────────────┴───────────────┐
              ▼                               ▼
          CUSTOMER                          SELLER
              │                               │
        Authentication                  Onboarding
              │                               │
              └───────────────┬───────────────┘
                              ▼
                         REST API
                              │
          ┌───────────────────┼───────────────────┐
          ▼                   ▼                   ▼
       Catalog              Orders             Payments
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ▼
                        Service Layer
                              │
                    ┌─────────┼─────────┐
                    ▼         ▼         ▼
                 MongoDB    Redis    Razorpay
```

**What I worked on**

* Role-based customer, seller and admin flows
* Seller onboarding and approval workflow
* Product and category management
* Filtering, searching, sorting and pagination
* Seller-specific product ownership and authorization
* Order processing and seller order aggregation
* Payment gateway integration
* Validation and centralized middleware
* Service-layer architecture for separating business logic
* Data consistency and transaction-aware backend design

**Architecture**

`Layered Architecture` `MVC` `Service Layer` `REST APIs` `RBAC`

**Stack**

`Node.js` `Express` `MongoDB` `Mongoose` `Redis` `Razorpay` `Docker` `AWS`

**Engineering focus**

`Data Modeling` `Concurrency` `Transactions` `Caching` `Payments` `Authorization`

---

### `02 // EventFlow`

```text
COMPLETED · EVENT MANAGEMENT PLATFORM
```

An event management backend built around scheduling, registration
and capacity management for multi-session events.

Instead of treating an event as a simple CRUD resource, the system
models the relationships between events, sessions, registrations
and available capacity.

```text
Event
 │
 ├── Session
 │    ├── Schedule
 │    ├── Capacity
 │    └── Status
 │
 └── Registration
       │
       └── User
```

**What I worked on**

* Event and session management
* Registration workflows
* Capacity and availability tracking
* Backend API design
* State-based event handling
* Structured data modeling around event relationships

**Architecture**

`Backend-First` `REST APIs` `Resource Modeling`

**Stack**

`Node.js` `Express` `MongoDB`

**Engineering focus**

`API Design` `State Management` `Capacity Tracking` `Data Modeling`

---

### `03 // EV Charging Optimizer`

```text
COMPLETED · EV CHARGING OPTIMIZATION SYSTEM
```

An optimization platform for deciding how EV charging demand
should be distributed across available charging stations.

The system combines graph algorithms with a backend optimization
engine to account for distance, station capacity, availability
and load distribution.

```text
Charging Network
       │
       ▼
  Graph Modeling
       │
       ▼
 Shortest Path
       │
       ▼
Station Utility
       │
       ▼
Demand Allocation
       │
       ▼
Load Optimization
```

**Core algorithmic flow**

* Models charging infrastructure as a graph
* Uses shortest-path calculation for route distance
* Scores stations using distance, capacity and system penalties
* Allocates demand based on station utility
* Considers overload, waiting and clustering penalties

**Architecture**

`Optimization Engine` `Graph Algorithms` `Backend API`

**Stack**

`C++` `FastAPI` `Node.js` `PostgreSQL` `React` `Leaflet`

**Engineering focus**

`Dijkstra` `Greedy Optimization` `Graph Modeling` `Load Distribution`

---

### `04 // Decentralized Voting System`

```text
COMPLETED · VERIFIABLE VOTING SYSTEM
```

A voting platform exploring how blockchain technology can be used
to improve the integrity and verifiability of digital voting.

The system combines a conventional application backend with a
decentralized layer for recording and verifying voting activity.

```text
User
 │
 ▼
Application API
 │
 ├── Authentication
 ├── Election Management
 └── Vote Processing
          │
          ▼
    Blockchain Layer
          │
          ▼
   Verifiable Record
```

**What I explored**

* Authentication and voter workflows
* Election and voting logic
* Tamper-resistant vote recording
* Blockchain-based verification
* Separation between application logic and decentralized storage

**Architecture**

`REST API` `Application Layer` `Blockchain Layer`

**Stack**

`Node.js` `Express` `MongoDB` `Solidity` `Ethereum`

**Engineering focus**

`Integrity` `Verification` `Authentication` `Decentralization`

---

## `> engineering_principles`

```text
┌──────────────────────────────────────────────────────────────┐
│                                                              │
│  [01] DATA FIRST                                             │
│       Design schemas around actual access patterns.          │
│                                                              │
│  [02] CONCURRENCY AWARE                                      │
│       Think about race conditions before production does.    │
│                                                              │
│  [03] FAILURE IS NORMAL                                      │
│       Retries, idempotency and recovery belong in design.    │
│                                                              │
│  [04] DEPLOY EARLY                                           │
│       If it only works locally, it isn't finished.           │
│                                                              │
│  [05] KNOW THE TRADEOFFS                                     │
│       Good engineering is about decisions, not just code.    │
│                                                              │
│  [06] KEEP IT MAINTAINABLE                                   │
│       Code should be understandable without a walkthrough.   │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

---

## `> current_focus`

```text
sahil@backend-engineer:~$ ./focus.sh

[██████████████████░░] System Design
[████████████████░░░░] PostgreSQL
[███████████████░░░░░] Distributed Systems
[██████████████░░░░░░] Backend Architecture
[████████████░░░░░░░░] DSA
[██████████░░░░░░░░░░] AWS
```

```text
NEXT →

→ deeper relational modeling
→ query optimization
→ concurrency & load testing
→ distributed systems
→ system design case studies
→ production deployment
→ consistent DSA practice
```

---

## `> github_activity`

<div align="center">

<img
src="https://github-readme-stats.vercel.app/api?username=snmcodes99&show_icons=true&hide_border=true&bg_color=0D1117&title_color=22D3EE&icon_color=34D399&text_color=C9D1D9&hide_rank=true"
height="165"
/>

<img
src="https://github-readme-stats.vercel.app/api/top-langs/?username=snmcodes99&layout=compact&hide_border=true&bg_color=0D1117&title_color=22D3EE&text_color=C9D1D9&langs_count=6"
height="165"
/>

<br/><br/>

<img
src="https://github-readme-streak-stats.herokuapp.com/?user=snmcodes99&theme=dark&hide_border=true&background=0D1117&ring=22D3EE&fire=34D399&currStreakLabel=22D3EE"
height="165"
/>

</div>

---

## `> contribution_activity`

<div align="center">

<img
src="https://raw.githubusercontent.com/snmcodes99/snmcodes99/output/github-contribution-grid-snake-dark.svg"
width="100%"
alt="GitHub contribution activity"
/>

<br/><br/>

<img
src="https://github-readme-activity-graph.vercel.app/graph?username=snmcodes99&bg_color=0D1117&color=22D3EE&line=34D399&point=C9D1D9&area=true&hide_border=true"
width="100%"
alt="GitHub activity graph"
/>

</div>

---

## `> connect`

<div align="center">

<a href="https://github.com/snmcodes99">
<img src="https://img.shields.io/badge/GITHUB-snmcodes99-0D1117?style=for-the-badge&logo=github&logoColor=22D3EE"/>
</a>

<a href="https://linkedin.com/">
<img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0D1117?style=for-the-badge&logo=linkedin&logoColor=22D3EE"/>
</a>

</div>

<br/>

<div align="center">

```text
$ build
$ solve
$ iterate
$ ship
```

<img
src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:111827,100:0D1117&height=100&section=footer"
width="100%"
/>

</div>
