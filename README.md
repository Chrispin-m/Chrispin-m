<!-- Animated terminal-style SVG-->
<p align="center">
  <svg width="720" height="120" viewBox="0 0 720 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title">
    <title id="title">Chrispin-m — terminal banner</title>
    <defs>
      <linearGradient id="g" x1="0" x2="1">
        <stop offset="0" stop-color="#00ff99"/>
        <stop offset="1" stop-color="#00d4ff"/>
      </linearGradient>
      <style>
        <![CDATA[
          .bg { fill:#0b1020; rx:12; ry:12; }
          .term { font: 600 18px/1 'SFMono-Regular', Consolas, "Roboto Mono", monospace; fill: url(#g); }
          .sub { font: 400 12px/1 'SFMono-Regular', monospace; fill:#9aa7c7; }
        ]]>
      </style>
    </defs>
    <rect class="bg" x="0" y="0" width="720" height="120" rx="12" ry="12"/>
    <text x="28" y="38" class="term">➜  chrispin@devbox ~</text>
    <text x="28" y="62" class="sub" id="typed">Loading...</text>
    <!-- animate a few tech-lines (typing effect) -->
    <animate 
      xlink:href="#typed" attributeName="opacity" from="0" to="1"
      begin="0s" dur="0.001s" fill="freeze" />
    <set xlink:href="#typed" attributeName="opacity" to="1" begin="0.01s" />
    <text x="28" y="62" class="sub">
      <tspan id="t1">Python · Django · Rust · Motoko · Solidity · TypeScript · React · Vue</tspan>
      <animate attributeName="display" values="inline;none" begin="0s" dur="4s" repeatCount="indefinite" />
    </text>
    <text x="28" y="80" class="sub">
      <tspan id="t2">Web3 · Smart contracts · DevOps · CI/CD · Security · AI pipelines</tspan>
      <animate attributeName="display" values="none;inline" begin="4s" dur="4s" repeatCount="indefinite" />
    </text>
    <text x="28" y="98" class="sub">
      <tspan id="t3">Open-source tinkerer 🔧 · Ship, test, and break stuff safely</tspan>
      <animate attributeName="display" values="none;inline" begin="8s" dur="4s" repeatCount="indefinite" />
    </text>
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

> Paste this snippet into an issue, blog, or any markdown that allows inline SVGs to get a live-typing terminal flair.

```html
<svg width="640" height="64" viewBox="0 0 640 64" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" rx="8" fill="#0b0f1a"/>
  <text x="12" y="40" font-family="monospace" font-size="16" fill="#7ef9a2">
    <tspan id="type">> git clone https://github.com/Chrispin-m/</tspan>
  </text>
  <animate xlink:href="#type" attributeName="opacity" from="0" to="1" dur="1.8s" begin="0s" fill="freeze"/>
</svg>
```

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

```
