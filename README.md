<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="Rzbyte — Architecting the boundary where autonomous agents touch real money" src="assets/header-dark.svg" width="100%">
</picture>

<a href="https://safehands.fun"><img src="https://img.shields.io/badge/safehands.fun-0e75b6?style=for-the-badge&logoColor=white" /></a>
<a href="https://x.com/rzbyte_"><img src="https://img.shields.io/badge/@rzbyte__-0D1117?style=for-the-badge&logo=x&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Indonesia-161B22?style=for-the-badge" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stats-light.svg">
  <img alt="20 projects shipped, 11 of 13 months shipped, 7 chains deployed to, 4 live right now" src="assets/stats-dark.svg" width="100%">
</picture>

</div>

<br/>

## How I think about the problem

These are separate projects, not one system — nothing flows between them. What connects them is the question each one answers. Grouping them this way is how I pick what to build next.

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/layers-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/layers-light.svg">
  <img alt="Three layers: DETECT, DECIDE, ACT" src="assets/layers-dark.svg" width="100%">
</picture>
</div>

**Nothing should reach a wallet without a verdict first.** That is the line most of this work is drawn around.

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
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stack-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/stack-light.svg">
  <img alt="Stack: TypeScript, Python, Solidity, PHP; Node.js, FastAPI, Laravel, Postgres, Prisma, Docker; Next.js, Vercel; Pharos, Solana, Celo, OKX X Layer, Somnia, Lisk, PortalDot" src="assets/stack-dark.svg" width="100%">
</picture>
</div>

<br/>

---

<div align="center">
<i>Most things here were built under time pressure for a specific problem.<br/>The READMEs say what works and what doesn't.</i>
</div>
