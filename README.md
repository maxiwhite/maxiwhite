<div align="center">

<img src="https://raw.githubusercontent.com/maxiwhite/maxiwhite/main/banner.svg" width="100%" alt="Maximilien White — The OS composes. The domains remain real." />

<br/><br/>

<a href="https://uniform1ty.github.io"><img src="https://img.shields.io/badge/▶_LANDING_PAGE-uniform1ty.github.io-2DD4E8?style=for-the-badge&labelColor=0B0E15" alt="Landing page" /></a>
<a href="https://github.com/UNIFORM1TY"><img src="https://img.shields.io/badge/ORG-UNIFORM1TY-8B7CF6?style=for-the-badge&labelColor=0B0E15" alt="Organization" /></a>
<a href="https://github.com/UNIFORM1TY/uniformity-os"><img src="https://img.shields.io/badge/tests-91%2F91-34D399?style=for-the-badge&labelColor=0B0E15" alt="91/91 tests passing" /></a>

<br/><br/>

**Systems architect.** I build systems that stay separate and still work together.

</div>

---

## ⬡ Uniformity — the operating system that composes

Uniformity standardises **identity, canonical object state, permissions, evidence, action, verification and history** across a portfolio of deliberately distinct products — without collapsing every domain into one application.

```text
Object → State → Signal → Evidence → Intelligence → Action → Verification → History
```

> **One owner per truth.** The OS composes; the domains remain real.

---

## ⚡ Install

```bash
git clone https://github.com/UNIFORM1TY/uniformity-os.git
cd uniformity-os
npm install
npm test          # 91 / 91 passing
npm run present   # the guided presentation
```

**Prerequisite:** Node.js 18+

| Command | What it runs |
| :--- | :--- |
| `npm test` | The full suite — `node --test`, 91 tests, zero dependencies |
| `npm run present` | Guided presentation across the reference slice |
| `npm run demo:juno` | The JUNO-106 reference object |
| `npm run demo:web` | JUNO web surface |
| `npm run demo:discovery` | Architecture / discovery surface |
| `npm run service:fridge-brain` | The advisory service, standalone |
| `npm run service:relay` | The relay server |

**Default presentation ports**

| Surface | Port |
| :--- | :--- |
| Discovery / Architecture / Guided | `127.0.0.1:8790` |
| JUNO reference object | `127.0.0.1:8791` |
| Truth Review | `127.0.0.1:8792` |
| Fridge Brain service | `127.0.0.1:8793` |

Override with `DISCOVERY_PORT`, `JUNO_PORT`, `TRUTH_REVIEW_PORT`, `FRIDGE_BRAIN_PORT`.

---

## 🧭 The product model

| | Surface | Owns | Must never own |
| :--- | :--- | :--- | :--- |
| ⬡ | **Uniformity** — the OS | identity, canonical object/state, permissions, events, orchestration, role/context | instrument semantics, advisory reasoning |
| ⬢ | **LOGARHYTHM / SUBANGEL** — one instrument world | instrument & workshop semantics, human-facing experience | cross-domain OS truth |
| ⬡ | **JUNO-106** — reference object | proving the runtime | being a product |
| ⬢ | **Fridge Brain** — advisory service | interpretation, provenance, hypotheses, one proposed next action | canonical state mutation |
| ⬡ | **RESELL · UCMR** — domain adapters | their own domain semantics and workflows | instrument-domain truth |
| ⬢ | **Hermes + Nous** — research / operator | research cross-reference, governed execution support | product truth |

### Role projections — same object, different eyes

Every projection resolves the **same canonical `object_id`**. Depth and language change; truth does not.

| Projection | Sees |
| :--- | :--- |
| **Matt** — technical | Signal → Reason → Evidence → full trace, ranked hypotheses, provenance |
| **Susanna** — operational | status, blocker, who acts next, next workshop step |
| **Customer** — safe | customer-safe status and required approval only |
| **Logarhythm** — public | cultural presentation, no private workshop intelligence |

---

## 🔒 Boundaries, enforced not documented

- **Fridge Brain may propose; it may never mutate.** Uniformity filters evidence *before* it crosses the service boundary; the service validates defensively and returns assessment only.
- **A completed action** appends verified evidence, updates canonical state **exactly once**, and becomes visible through every permitted projection.
- **History is immutable.** Records are superseded, never erased.
- **Staging is not verification.** Every claim carries a command, a result and a timestamp.

---

## 🛠 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Convex](https://img.shields.io/badge/Convex-EE342F?style=flat-square&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

<div align="center">

<img height="150em" src="https://github-readme-stats.vercel.app/api?username=maxiwhite&show_icons=true&hide_border=true&bg_color=0B0E15&title_color=2DD4E8&icon_color=8B7CF6&text_color=8B93A7&count_private=true" alt="GitHub stats" />
<img height="150em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maxiwhite&layout=compact&hide_border=true&bg_color=0B0E15&title_color=2DD4E8&text_color=8B93A7&count_private=true" alt="Top languages" />

<br/><br/>

<a href="https://uniform1ty.github.io"><img src="https://img.shields.io/badge/Explore_the_ecosystem-2DD4E8?style=for-the-badge&labelColor=0B0E15" alt="Explore" /></a>

<br/><br/>

<sub><b>The OS composes; the domains remain real.</b></sub>

</div>
