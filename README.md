<p align="center">
<svg xmlns="http://www.w3.org/2000/svg"
     width="720" height="160" viewBox="0 0 720 160"
     role="img" aria-label="Chrispin-m — terminal banner">
  <defs>
    <!-- background gradient that subtly cycles -->
    <linearGradient id="bgGrad" x1="0" x2="1">
      <stop offset="0" stop-color="#06101a">
        <animate attributeName="stop-color" dur="8s" values="#06101a;#081428;#0b1020;#06101a" repeatCount="indefinite" />
      </stop>
      <stop offset="1" stop-color="#07142a">
        <animate attributeName="stop-color" dur="10s" values="#07142a;#09203a;#06101a;#07142a" repeatCount="indefinite" />
      </stop>
    </linearGradient>
    <!-- glowing orb gradient -->
    <radialGradient id="orb" cx="50%" cy="50%" r="50%">
      <stop offset="0" stop-color="#00ffd5" stop-opacity="0.95"/>
      <stop offset="0.5" stop-color="#00b2ff" stop-opacity="0.55"/>
      <stop offset="1" stop-color="#000000" stop-opacity="0"/>
    </radialGradient>
    <!-- text gradient -->
    <linearGradient id="textGrad" x1="0" x2="1">
      <stop offset="0" stop-color="#7ef9a2"/>
      <stop offset="1" stop-color="#7ad8ff"/>
    </linearGradient>
    <!-- subtle grain using tiny semi-opaque rectangles (keeps it safe vs complex filters) -->
    <pattern id="grain" width="6" height="6" patternUnits="userSpaceOnUse">
      <rect width="6" height="6" fill="#000" opacity="0.02"/>
      <circle cx="1.2" cy="4.8" r="0.6" fill="#fff" opacity="0.03"/>
      <circle cx="4.7" cy="1.5" r="0.4" fill="#fff" opacity="0.02"/>
    </pattern>
  </defs>

  <!-- background -->
  <rect x="0" y="0" width="720" height="160" rx="16" fill="url(#bgGrad)"/>
  <rect x="0" y="0" width="720" height="160" rx="16" fill="url(#grain)" />

  <!-- drifting orbs for surreal mood -->
  <g opacity="0.85">
    <circle cx="120" cy="30" r="36" fill="url(#orb)" opacity="0.9">
      <animateTransform attributeName="transform" type="translate" dur="16s"
                        values="0 0; 40 12; -20 30; 0 0" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;0.95;0.6;0.7" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle cx="560" cy="46" r="26" fill="url(#orb)" opacity="0.8">
      <animateTransform attributeName="transform" type="translate" dur="14s"
                        values="0 0; -30 18; 8 28; 0 0" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.5;0.85;0.55;0.5" dur="10s" repeatCount="indefinite"/>
    </circle>
    <circle cx="420" cy="120" r="18" fill="url(#orb)" opacity="0.7">
      <animateTransform attributeName="transform" type="translate" dur="18s"
                        values="0 0; 10 -28; -12 8; 0 0" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.8;0.45;0.4" dur="9s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- header / prompt -->
  <text x="32" y="48" font-family="SFMono-Regular, Consolas, 'Roboto Mono', monospace"
        font-weight="700" font-size="18" fill="url(#textGrad)" letter-spacing="0.6">
    ➜  chrispin@devbox ~
    <!-- tiny surreal wobble -->
    <animateTransform attributeName="transform" type="translate" dur="6s" values="0 0; 2 -1; -2 1; 0 0" repeatCount="indefinite"/>
  </text>

  <!-- blinking cursor -->
  <rect x="268" y="34" width="8" height="12" rx="2" fill="#7ef9a2" opacity="0.95">
    <animate attributeName="opacity" values="0;1;0;1" dur="1.4s" repeatCount="indefinite"/>
  </rect>

  <!-- three tech lines: crossfade + slight float -->
  <text id="line1" x="32" y="78" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="1">
    Python · Django · Rust · Motoko · Solidity · TypeScript · React · Vue
    <animate attributeName="opacity" values="1;0;0;1" dur="12s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" dur="12s" values="0 0; 0 -2; 0 4; 0 0" repeatCount="indefinite"/>
  </text>

  <text id="line2" x="32" y="100" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="0">
    Web3 · Smart contracts · DevOps · CI/CD · Security · AI pipelines
    <animate attributeName="opacity" values="0;1;0;0" dur="12s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" dur="12s" values="0 2; 0 0; 0 -3; 0 2" repeatCount="indefinite"/>
  </text>

  <text id="line3" x="32" y="122" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="0">
    Open-source tinkerer 🔧 · Ship, test, and break stuff safely
    <animate attributeName="opacity" values="0;0;1;0" dur="12s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" dur="12s" values="0 -3; 0 2; 0 0; 0 -3" repeatCount="indefinite"/>
  </text>

  <!-- small surreal shimmer on top edge -->
  <rect x="0" y="0" width="720" height="6" rx="3" fill="url(#textGrad)" opacity="0.06">
    <animate attributeName="opacity" values="0.02;0.12;0.02" dur="6s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" dur="10s" values="0 0; 60 0; -40 0; 0 0" repeatCount="indefinite"/>
  </rect>
</svg>
</p>

# 👋 Hi, I’m **@Chrispin-m**
> Hacker by habit, builder by boredom. I solder ideas together with code-now dabbling in web3, motoko, and on-chain chaos.

---

## What I tinker with
[![Python](https://img.shields.io/badge/-Python-364A9E?style=flat&logo=python&logoColor=white)]
[![Django](https://img.shields.io/badge/-Django-092E20?style=flat&logo=django&logoColor=white)]
[![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white)]
[![Motoko](https://img.shields.io/badge/-Motoko-7E57C2?style=flat&logo=internet-computer&logoColor=white)]
[![Solidity](https://img.shields.io/badge/-Solidity-363636?style=flat&logo=ethereum&logoColor=white)]
[![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)]
[![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=000)]
[![Vue](https://img.shields.io/badge/-Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white)]
[![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)]
[![Kubernetes](https://img.shields.io/badge/-K8s-326CE5?style=flat&logo=kubernetes&logoColor=white)]

---

## Current Focus & Projects
```mermaid
flowchart LR
  A[Ideas] --> B{Pick a Stack}
  B -->|onchain| C[Solidity + Hardhat]
  B -->|IC| D[Motoko + DFINITY]
  B -->|infra| E[Docker + Kubernetes + CI/CD]
  B -->|apps| F[React + TypeScript + Vue]
  C --> G[DeFi / NFTs / Oracles]
  D --> H[Canister apps & distributed state]
  E --> I[Automated tests, infra-as-code, observability]
````

---

## Nerdy Highlights

* 🔭 Building cross-chain demos and **on-device** cryptographic experiments.
* 🛠️ Fluent in **Rust** for performance-critical tools, **Motoko** for the Internet Computer, and **Solidity** for EVM contracts.
* 🎛️ Love CI/CD pipelines, container orchestration, and secure deployment patterns (GitHub Actions, Docker, k8s).
* 🔐 Practicing secure coding + red-team thinking — I like finding the edge cases.
* 🌱 Always learning: ML ops, zero-knowledge proofs, and better DX for devs.

---

## GitHub Live Badges & Streaks

<!-- GitHub stats / streaks-->

<p align="center">
  <img alt="Chrispin's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Chrispin-m&show_icons=true&count_private=true&theme=radical" />
  &nbsp;
  <img alt="streak" src="https://github-readme-streak-stats.herokuapp.com/?user=Chrispin-m&theme=dark&date_format=%5By%20%5DM%20j" />
</p>

---

## Fancy Terminal-ish Section (interactive-feel)

<p align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="720" height="140" viewBox="0 0 720 140" role="img" aria-label="Chrispin-m terminal banner">
  <!-- background -->
  <defs>
    <linearGradient id="g1" x1="0" x2="1">
      <stop offset="0" stop-color="#02202a"/>
      <stop offset="1" stop-color="#071028"/>
    </linearGradient>
    <linearGradient id="neon" x1="0" x2="1">
      <stop offset="0" stop-color="#7ef9a2"/>
      <stop offset="1" stop-color="#7ad8ff"/>
    </linearGradient>
    <!-- clip used to 'reveal' the typed command -->
    <clipPath id="revealMask">
      <rect id="maskRect" x="0" y="0" width="0" height="28" />
    </clipPath>
  </defs>

  <rect x="0" y="0" width="720" height="140" rx="12" fill="url(#g1)"/>

  <!-- header -->
  <text x="28" y="36" font-family="SFMono-Regular, Consolas, 'Roboto Mono', monospace"
        font-weight="700" font-size="18" fill="url(#neon)" letter-spacing="0.6">
    ➜ chrispin@devbox ~
  </text>

  <!-- glass panel -->
  <rect x="16" y="44" width="688" height="78" rx="8" fill="rgba(255,255,255,0.02)"/>

  <g transform="translate(32,72)">
    <g clip-path="url(#revealMask)">
      <text id="cmd" x="0" y="0" font-family="SFMono-Regular, monospace" font-size="14" fill="#cdeedd">
        &gt; git clone https://github.com/Chrispin-m/awesome-stuff.git
      </text>
    </g>
    <!-- animate the mask width to create a typing reveal effect -->
    <animate xlink:href="#maskRect" attributeName="width" from="0" to="540" dur="3.6s" begin="0.6s" fill="freeze" />
    <!-- blinking neon cursor -->
    <rect id="cursor" x="6" y="-14" width="8" height="16" rx="2" fill="url(#neon)" opacity="0.95">
      <!-- cursor moves to end of text by animating x after reveal -->
      <animate attributeName="x" from="6" to="550" begin="4.2s" dur="0.1s" fill="freeze" />
      <animate attributeName="opacity" values="0;1;0;1" dur="1.2s" repeatCount="indefinite" />
    </rect>
  </g>

  <!-- animated "output" lines that appear after typing -->
  <text x="32" y="112" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="0">
    Cloning into 'awesome-stuff'...
    <animate attributeName="opacity" values="0;1" begin="4.5s" dur="0.4s" fill="freeze"/>
  </text>

  <text x="32" y="128" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="0">
    remote: Enumerating objects: 42, done.
    <animate attributeName="opacity" values="0;1" begin="4.9s" dur="0.4s" fill="freeze"/>
  </text>

  <text x="320" y="128" font-family="SFMono-Regular, monospace" font-size="12" fill="#9aa7c7" opacity="0">
    done.
    <animate attributeName="opacity" values="0;1" begin="5.3s" dur="0.3s" fill="freeze"/>
  </text>

  <!-- subtle neon shimmer line -->
  <rect x="16" y="44" width="688" height="2" rx="1" fill="url(#neon)" opacity="0.06">
    <animate attributeName="opacity" values="0.02;0.12;0.02" dur="6s" repeatCount="indefinite"/>
    <animateTransform attributeName="transform" type="translate" values="0 0; 80 0; -60 0; 0 0" dur="9s" repeatCount="indefinite" />
  </rect>
</svg>
</p>


---

## Want to collab?

* 💬 Ping me on WhatsApp: [+254 710 358 658](https://wa.me/254710358658)
* ✉️ Or just open an issue / PR on any repo - I respond faster to well-crafted bug reports and memes.

---

## How I like my repos

* Repro steps + tiny demo (codesandbox / local)
* Tests (unit > integration) and a CI badge
* Small, focused modules. One responsibility per package.

---

## Fun facts

* 🧪 I break my code on purpose so CI can catch the clever ways I try to be clever.
* 🕹️ I organize occasional Tree-Planting Skate Tours - code gets greener IRL.
* ⚙️ My dev environment probably has more dotfiles than a small OS distro.

---

Give me a star ⭐ - my code runs faster when it feels loved. It’s science. Trust me.

---
