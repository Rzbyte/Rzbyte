<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Rzbyte — Architecting the boundary where autonomous agents touch real money" src="assets/header-dark.svg" width="100%">
</picture>

<a href="https://safehands.fun"><img src="https://img.shields.io/badge/safehands.fun-0e75b6?style=for-the-badge&logoColor=white" /></a>
<a href="https://x.com/rzbyte_"><img src="https://img.shields.io/badge/@rzbyte__-0D1117?style=for-the-badge&logo=x&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Indonesia-161B22?style=for-the-badge" />

</div>

<br/>

## How the work fits together

Every project below sits on one of three layers. Read left to right: notice something, decide whether it is safe, then act on it.

```mermaid
flowchart LR
    subgraph DETECT["1 - DETECT"]
        direction TB
        F["FSignal<br/>founder signals, 4.4d lead"]
        W["whale-pacifica<br/>whale + liquidation flow"]
        T["TraceVault<br/>incident recall"]
    end

    subgraph DECIDE["2 - DECIDE"]
        direction TB
        S["SafeHands<br/>ALLOW / BLOCK before signing"]
        P["PhylaX<br/>token risk + route scan"]
    end

    subgraph ACT["3 - ACT"]
        direction TB
        R["Rivo<br/>agent validation, 2179 contracts"]
        PS["Piggy Sentinel<br/>non-custodial savings"]
        C["CollabOS<br/>partnership agent, 232 tests"]
    end

    DETECT --> DECIDE --> ACT

    style DECIDE stroke:#0e75b6,stroke-width:2px
```
The middle layer is the one I care most about: **nothing reaches a wallet without a verdict first.**

<br/>

## Flagship Infrastructure

<table bordercolor="#30363d">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/safehands-pharos">SafeHands</a></h3>
      <p align="center"><i>Transaction Firewall for AI Agent Finance</i></p>
      <p>A deterministic policy engine issuing <b>ALLOW / BLOCK</b> verdicts <i>before</i> a wallet signs. Ships as an MCP server, API, and npm package. Live on Pharos Pacific Mainnet.</p>
      <p align="center">
        <a href="https://safehands.fun"><img src="https://img.shields.io/badge/●_Live-1a7f37?style=flat-square" /></a>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/MCP-0D1117?style=flat-square" />
        <img src="https://img.shields.io/badge/Pharos-161B22?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/Rivo">Rivo</a></h3>
      <p align="center"><i>Event Intelligence for DreamDEX</i></p>
      <p>Turns Event Contract probabilities into measurable intelligence. Calibration against <b>2,179 contracts</b>. Validates agents economically with on-chain testnet proof.</p>
      <p align="center">
        <a href="https://x-rivo.vercel.app"><img src="https://img.shields.io/badge/●_Live-1a7f37?style=flat-square" /></a>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Kelly_Criterion-0D1117?style=flat-square" />
        <img src="https://img.shields.io/badge/Somnia-161B22?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/FSignal">FSignal</a></h3>
      <p align="center"><i>Ghost Signal Monitor</i></p>
      <p>Persistent Slack monitor tracking founders before the official directory lists them. Median lead time <b>4.4 days</b> with <b>&gt;= 90%</b> precision enforced in CI.</p>
      <p align="center">
        <a href="https://fsignal-production.up.railway.app"><img src="https://img.shields.io/badge/●_Live-1a7f37?style=flat-square" /></a>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Algolia-0D1117?style=flat-square&logo=algolia&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/PhylaX">PhylaX</a></h3>
      <p align="center"><i>AI Execution Firewall</i></p>
      <p>Scans tokens for honeypot risk, fetches optimal DEX routes, and builds unsigned transactions for OKX X Layer. The server never broadcasts &mdash; signing stays with the user.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Dual--LLM_fallback-0D1117?style=flat-square" />
        <img src="https://img.shields.io/badge/OKX_X_Layer-161B22?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/PiggySentinel">Piggy Sentinel</a></h3>
      <p align="center"><i>Autonomous Savings Agent on Celo</i></p>
      <p>Set a goal and a budget. Penny allocates into <b>Aave V3</b>, monitors, and rebalances. Non-custodial &mdash; it moves only within the on-chain allowance you set.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Aave_V3-0D1117?style=flat-square" />
        <img src="https://img.shields.io/badge/Celo-FCFF52?style=flat-square&logo=celo&logoColor=black" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/Rzbyte/TraceVault">TraceVault</a></h3>
      <p align="center"><i>Vector Search for Incidents</i></p>
      <p>Paste an error, find the fix. Local embeddings via <code>all-MiniLM-L6-v2</code> and HNSW cosine search on Actian VectorAI DB. Runs fully offline.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/Vector_Search-0D1117?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

<br/>

## Also Shipped

<table>
  <tr>
    <td valign="top" nowrap><b><a href="https://github.com/Rzbyte/vehicle-booking">vehicle-booking</a></b></td>
    <td>Fleet booking system delivered for a nickel mining company. Two-level approval workflow, usage analytics, Excel report export.</td>
    <td align="right" nowrap><img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" /></td>
  </tr>
  <tr>
    <td valign="top" nowrap><b><a href="https://github.com/Rzbyte/CollabOS">CollabOS</a></b></td>
    <td>Autonomous creator partnership director on Minds by Animoca Brands. <b>232 tests</b>, Playwright E2E against the live platform.</td>
    <td align="right" nowrap><img src="https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=next.js&logoColor=white" /> <img src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" /></td>
  </tr>
  <tr>
    <td valign="top" nowrap><b><a href="https://github.com/Rzbyte/safehands-solana">safehands-solana</a></b></td>
    <td>SafeHands pre-execution policy engine ported to Solana.</td>
    <td align="right" nowrap><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Solana-14F195?style=flat-square&logo=solana&logoColor=black" /></td>
  </tr>
  <tr>
    <td valign="top" nowrap><b><a href="https://github.com/Rzbyte/whale-pacifica">whale-pacifica</a></b></td>
    <td>Whale activity and liquidation-cascade monitor for Pacifica perpetuals.</td>
    <td align="right" nowrap><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /></td>
  </tr>
  <tr>
    <td valign="top" nowrap><b><a href="https://github.com/Rzbyte/recall-dashboard">recall-dashboard</a></b></td>
    <td><a href="https://recall-agent-dashboard.vercel.app">Live</a> dashboard tracking Recall Network agent decisions and outcomes.</td>
    <td align="right" nowrap><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" /></td>
  </tr>
</table>

<br/>

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=typescript,python,solidity,nodejs,fastapi,nextjs,postgres,prisma,docker,vercel&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/Pharos-0D1117?style=flat-square" />
<img src="https://img.shields.io/badge/Solana-0D1117?style=flat-square&logo=solana&logoColor=14F195" />
<img src="https://img.shields.io/badge/Celo-0D1117?style=flat-square&logo=celo&logoColor=FCFF52" />
<img src="https://img.shields.io/badge/OKX_X_Layer-0D1117?style=flat-square" />
<img src="https://img.shields.io/badge/Somnia-0D1117?style=flat-square" />
<img src="https://img.shields.io/badge/Lisk-0D1117?style=flat-square&logo=lisk&logoColor=white" />

</div>

<br/>

---

<div align="center">
<i>Most things here were built under time pressure for a specific problem.<br/>The READMEs say what works and what doesn't.</i>
</div>
