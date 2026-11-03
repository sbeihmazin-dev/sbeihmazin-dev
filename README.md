# Mazin Sbeih

**Worked in banks. Sold to banks. Now I build for them.**

[LinkedIn](https://www.linkedin.com/in/mazin-sbeih)

<img src="assets/control-layer.svg" width="100%" alt="Animated diagram of my AI control layer: an agent proposes a change, a human approves scope, an edit made before the failing test is blocked by a hook, the failing test is written first, the build goes green, CodeRabbit reviews, and the merge waits for a human.">

<img src="assets/value.svg" width="100%" alt="The value. Speed without blind trust: agents write the code; scripts, not the agent, decide whether it passes. An audit trail by default: every change carries a scoped proposal, a failing test written first, a review note, and a human approval. Mistakes stopped before they land: source edits are blocked until a failing test exists, destructive git commands need confirmation, and agents cannot merge.">

<img src="assets/usecases.svg" width="100%" alt="Use cases. Banks and credit unions adopting AI coding agents under risk and compliance scrutiny. Fintech and stablecoin teams writing payment, ledger, and sanctions code that has to survive bank due diligence. AI adoption teams that need working guardrails, not just a policy document.">

<img src="assets/compare.svg" width="100%" alt="Why it's different: enforced, not requested. Most AI coding setups keep rules in a prompt, let the agent say when it is done, test after the code is written, let agents push and merge, trust every change equally, and take compliance numbers from memory. This control layer enforces rules with hooks and scripts, counts done only when the verify script passes, blocks edits until a failing test exists, reserves merges for a human, tiers changes by risk, and requires a primary-source citation for every regulatory threshold.">

<img src="assets/about.svg" width="100%" alt="About me: 10 years on both sides of the table. Inside banks, 2016 to 2021, at Wells Fargo, Bank of the West, and U.S. Bank. Selling to banks, 2021 to 2026, at Alkami, Amount, and Array. Building for banks now: stablecoin settlement infrastructure and this control layer. AI toolkit: Claude Code, OpenAI Codex, GitHub Copilot, CodeRabbit, ChatGPT, Obsidian.">

<details>
<summary>Read this page as text</summary>

### The control layer
A governance system I built around AI coding agents, so one person can ship compliance-grade software fast without taking the agent's word for anything. Agents propose, hooks and scripts enforce the rules, and a human makes the calls that matter.

**The value**
- **Speed without blind trust.** Agents write the code. Scripts, not the agent, decide whether it passes.
- **An audit trail by default.** Every change carries a scoped proposal, a failing test written first, a review note, and a human approval.
- **Mistakes stopped before they land.** Source edits are blocked until a failing test exists, destructive git commands need confirmation, and agents cannot merge.

**Use cases**
- Banks and credit unions adopting AI coding agents under risk and compliance scrutiny.
- Fintech and stablecoin teams writing payment, ledger, and sanctions code that has to survive bank due diligence.
- AI adoption teams that need working guardrails for agentic development, not just a policy document.

**Why it's different**

| Most AI coding setups | This control layer |
|---|---|
| Rules live in a prompt the agent can ignore or forget | Rules are enforced by hooks and scripts the agent cannot skip |
| "Done" is whatever the agent says | "Done" means the verify script exited clean, with its output shown |
| Tests and review happen after the code is written | Code edits are blocked until a failing test is recorded and approved |
| Agents can push and merge on their own | Only a human merges, and pushes to main need approval |
| Every change gets the same level of trust | Risk-tiered: low-risk docs changes move with fewer stops; anything touching money, sanctions, or the ledger stops at human gates |
| Compliance numbers come from memory | Every regulatory threshold must cite its primary source, or the check fails |

**About me**
- **Inside banks (2016 to 2021):** Wells Fargo, Bank of the West, U.S. Bank.
- **Selling to banks (2021 to 2026):** Alkami, Amount, Array: digital banking, lending, and identity platforms.
- **Building for banks (now):** stablecoin settlement infrastructure (non-custodial, fail-closed sanctions screening, double-entry ledger) and this control layer.
- **AI toolkit:** Claude Code, OpenAI Codex, GitHub Copilot, CodeRabbit, ChatGPT, Obsidian.

</details>
