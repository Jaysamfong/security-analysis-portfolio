# Foresight Analyst — Gap-Closing Study Guide

**Prepared for:** Jayson Sam Fong
**Target role:** Foresight Analyst, CISA National Risk Management Center (NRMC)
**Purpose:** Convert a strong cyber-operator/educator profile into a credible *strategic-analysis* candidate by closing four specific gaps, plus building demonstrable portfolio work along the way.

---

## How to use this guide

This is not a generic reading list. It is built around the **four gaps** identified in your fit analysis, in priority order, plus a fifth integration module on analytic writing. Each module has the same shape:

- **Why it matters** — how it maps to the NRMC/foresight mission
- **Core concepts** — what to actually learn
- **Drills** — active practice, not passive reading
- **Resources** — where to go deeper (all open-source / publicly available)
- **Portfolio output** — a concrete artifact you produce, so you finish with evidence, not just knowledge

Your existing strengths (NIST/RMF/FedRAMP fluency, AI/emerging-tech literacy, writing and teaching ability, systems-level threat decomposition) are the foundation you're building on. This guide deliberately does **not** re-teach cyber tradecraft you already own. It teaches the *estimative, long-horizon, cross-domain* mode that foresight runs on.

**The mindset shift in one line:** you are moving from *"what is happening on this system right now?"* to *"what plausibly could happen to a whole sector over 5–15 years, and how confident am I?"*

---

## Module 1 — Structured Analytic Techniques (SATs)

> **This is your biggest gap and your highest-leverage module.** Do it first and give it the most time.

### Why it matters
SATs are the intelligence community's tradecraft for reasoning rigorously under uncertainty. Your analytical experience to date is *operational* (triage, IR lifecycle, IOC identification) — reactive and present-tense. Foresight is *estimative* — you make defensible judgments about things that haven't happened. SATs are how analysts externalize their reasoning, check their own biases, and produce judgments a decision-maker can trust. Interviewers for analytic roles probe for this directly.

### Core concepts

Learn what each technique is *for*, when to reach for it, and how to run it. Group them by function:

**Diagnostic techniques (test your own thinking):**
- **Key Assumptions Check** — list every assumption underlying a judgment, then stress each one. The single most useful habit you can build.
- **Analysis of Competing Hypotheses (ACH)** — lay out all plausible explanations, then evaluate evidence against *each*, actively looking for what *disproves* rather than confirms. Directly counters confirmation bias.
- **Quality of Information Check** — grade your sources for reliability and relevance before you lean on them.

**Contrarian techniques (challenge consensus):**
- **Devil's Advocacy** — deliberately argue the opposite of the prevailing view.
- **Red Team / Red Hat Analysis** — model how an adversary actually thinks and decides, not how you'd think in their shoes.
- **What-If Analysis** — assume a surprising event *has* occurred and reason backward to how it happened. (Note: this is the same cognitive move you already used naturally in our network-security discussion — you're better at this than you think.)
- **Premortem** — assume the project/judgment failed, then explain why.

**Imaginative techniques (generate new options):**
- **Structured Brainstorming** — divergent then convergent idea generation with rules that prevent early anchoring.
- **Cross-Impact Matrix** — map how a set of variables influence each other, exposing second-order effects.
- **Morphological / Quadrant analysis** — systematically enumerate combinations of key drivers.

### Drills
1. Take a recent cyber incident you know well. Write the **Key Assumptions Check** for the initial attribution. What was assumed vs. established?
2. Run a **full ACH** on a genuinely ambiguous question (e.g., "Was outage X caused by nation-state action, criminal ransomware, or operator error?"). Build the evidence-vs-hypothesis matrix. Force yourself to weight disconfirming evidence.
3. Write a one-page **Red Team** memo: "How would a sophisticated adversary attack the U.S. water sector's OT systems?" — reasoning as the adversary, not the defender.

### Resources
- **Richards Heuer & Randolph Pherson, *Structured Analytic Techniques for Intelligence Analysis*** — the standard reference. Learn the catalog.
- **Richards Heuer, *Psychology of Intelligence Analysis*** — the foundational text on cognitive bias in analysis; the U.S. government edition is publicly available.
- **CIA, *A Tradecraft Primer: Structured Analytic Techniques for Improving Intelligence Analysis*** — a free, concise government publication; an excellent starting point.
- **Sherman Kent Center** publications on analytic tradecraft (open access).

### Portfolio output
A short **"analytic tradecraft sample"**: pick one infrastructure risk question and produce a 2-page product that visibly uses a Key Assumptions Check and an ACH. This becomes an interview talking point and a writing sample.

---

## Module 2 — Strategic Foresight & Futures Thinking

> The long-horizon mode. This is the discipline the job title actually names.

### Why it matters
NRMC's Strategic Foresight subdivision exists to *anticipate and evaluate emerging risks* before they mature, and to identify priority risk-management topics. This is fundamentally different from tactical detection. It rewards breadth, comfort with ambiguity, and the ability to reason about trends, drivers, and low-probability/high-impact "wildcards."

### Core concepts

- **Horizon scanning** — systematically hunting for *weak signals* of change before they become obvious trends. (This is the strategic cousin of the threat-space enumeration you already do well.)
- **STEEP / PESTLE scanning frameworks** — Social, Technological, Economic, Environmental, Political (+ Legal) — a checklist so you scan *beyond* your home domain of cyber.
- **Drivers vs. trends vs. wildcards** — learn to distinguish underlying forces, observable trajectories, and disruptive surprises.
- **Three Horizons framework** — mapping the transition from the current system (H1) through disruption (H2) to a future system (H3).
- **Scenario planning (2x2 / GBN method)** — pick two critical, uncertain drivers, cross them into four plausible futures, and stress-test strategy against each. The workhorse technique of foresight.
- **Cone of Plausibility** — projecting a baseline future plus plausible and "wildcard" variants.
- **Backcasting** — start from a desired/feared future and work backward to the decisions that lead there.
- **Futures Wheel** — mapping first-, second-, and third-order consequences of a change. (You did this manually with the emanations/side-channel discussion.)

### Drills
1. Run a 30-minute **horizon scan** on one non-cyber sector (e.g., water or energy). Log 10 weak signals from open reporting. Tag each with a STEEP category.
2. Build a **2x2 scenario matrix** on a real question: "Two critical uncertainties shaping U.S. grid resilience by 2035." Name the four resulting futures and write a paragraph on each.
3. Draw a **Futures Wheel** for "widespread adoption of agentic AI in critical-infrastructure operations" — three rings deep. (Plays directly to your AI strength.)

### Resources
- **UK Government Office for Science, *The Futures Toolkit*** — free, practical, government-grade; arguably the single best starting resource.
- **Policy Horizons Canada** — free foresight methods, scans, and reports; excellent worked examples.
- **Institute for the Future (IFTF)** — foresight methodology and frameworks.
- **Peter Schwartz, *The Art of the Long View*** — the classic on scenario planning.
- **The Millennium Project, *Futures Research Methodology*** — comprehensive methods compendium.

### Portfolio output
A **2–3 page scenario brief** on an emerging-technology risk to critical infrastructure (AI-enabled attacks is a natural fit for you), using a proper 2x2 scenario structure and closing with "indicators to watch."

---

## Module 3 — Critical-Infrastructure Breadth (beyond cyber)

> Your profile is cyber-centric. NRMC's remit is *all-hazards and all-sectors*. Close the breadth gap.

### Why it matters
NRMC watches cyber *and* physical attacks, supply-chain vulnerabilities, nation-state aggression, insider threat, pandemics, natural disasters — and crucially, the **convergence** of previously siloed risks. A foresight analyst who can only reason about the cyber column is limited. The differentiator is cross-sector, cascading-failure thinking.

### Core concepts

- **The 16 critical infrastructure sectors** — know them cold, and know which agency (Sector Risk Management Agency / SRMA) owns each. Sectors include Energy, Water & Wastewater, Communications, Financial Services, Healthcare & Public Health, Transportation Systems, Food & Agriculture, Chemical, and others.
- **National Critical Functions (NCFs)** — CISA's 2019 framework of ~55 functions grouped under **Connect, Distribute, Manage, Supply**. This is *the* modern lens NRMC uses — it shifts analysis from "protect this asset" to "keep this function working." Learn this framework specifically; it's central to how NRMC thinks.
- **Cross-sector dependencies & cascading failure** — e.g., nearly everything depends on Energy and Communications; a water-sector failure cascades into healthcare and food. Learn to trace these chains.
- **Systemically Important Entities (SIEs)** — a newer NSM-22 concept: infrastructure whose disruption would cause nationally significant, cascading impact.
- **Resilience vs. protection** — modern policy explicitly accepts you *cannot* make all infrastructure immune to all threats; the goal is prioritized resilience. Internalize this framing.

### Drills
1. From memory, list all 16 sectors and their SRMA. Fill gaps, repeat until fluent.
2. Pick one NCF (e.g., "Supply Water") and map its top-5 cross-sector dependencies. Trace one cascading-failure chain three hops deep.
3. Write a half-page on a real **cross-sector cascade** (e.g., a communications outage's downstream effect on emergency services and finance).

### Resources
- **CISA — Critical Infrastructure Sectors** (cisa.gov) — the authoritative sector list and descriptions.
- **CISA — National Critical Functions** set and NCF framework materials.
- **NSM-22 (National Security Memorandum on Critical Infrastructure Security and Resilience, April 2024)** — read this; it's the current governing policy and it replaced PPD-21.
- **CISA National Risk Management Center pages and fact sheets** — understand NRMC's own structure (Analysis Division, Planning & Coordination), NISAC, and the STAR toolset.
- **The 2025 National Infrastructure Risk Management Plan** (successor to the 2013 NIPP) — read when available; it defines the current national approach.

### Portfolio output
A **one-page cross-sector dependency map** for a single NCF, with a short written cascade analysis. Demonstrates you can think in NRMC's native framework.

---

## Module 4 — Policy & Geopolitical Context

> The strategic environment foresight operates in. Shore up the non-technical context.

### Why it matters
Nation-state aggression and infrastructure policy are core to NRMC's mission, and NSM-22 explicitly brings intelligence-community analytic capability further into critical-infrastructure defense. You don't need to become a political scientist — you need enough fluency to situate technical risks in their strategic and policy context.

### Core concepts

- **The nation-state threat landscape** — the major state actors targeting U.S. critical infrastructure, their strategic objectives, and the concept of pre-positioning in infrastructure for future disruption. (Study "living-off-the-land" campaigns against infrastructure as case studies.)
- **Key U.S. policy documents** — at minimum: NSM-22, the National Cybersecurity Strategy (2023) and its implementation plan, CIRCIA (cyber incident reporting for critical infrastructure), and the concept of Sector Risk Management Agencies.
- **Supply-chain security policy** — ICT supply-chain risk management (SCRM), software bill of materials (SBOM), and why supply chain is treated as its own strategic risk (ties back to our earlier conversation).
- **All-hazards / public-health & natural-disaster dimension** — foresight includes pandemics, climate-driven events, and their convergence with cyber and physical risk.
- **Emerging-technology policy** — AI governance, quantum's threat to cryptography, and how policy is trying to get ahead of them. (Your strength — lean in.)

### Drills
1. Write a one-paragraph plain-English summary of NSM-22: what changed vs. PPD-21, and why it matters for risk analysis.
2. Pick one nation-state infrastructure-targeting campaign from open reporting and write a half-page: objective, method, and *strategic* (not just technical) significance.
3. Map one emerging technology (AI *or* quantum) to a specific critical-infrastructure risk and a policy response.

### Resources
- **NSM-22** and **CISA's NSM-22 explainer pages** (cisa.gov).
- **National Cybersecurity Strategy (2023)** and its Implementation Plan (White House).
- **CISA Secure by Design** and **ICT SCRM Task Force** materials.
- **CRS (Congressional Research Service) reports** on critical infrastructure — free, concise, well-sourced, non-partisan; excellent for policy grounding.
- **CISA / intelligence-community advisories** on nation-state activity against infrastructure (open versions).

### Portfolio output
A **1-page "strategic context memo"** on one emerging-technology risk to a critical-infrastructure sector, connecting the technical threat to policy and geopolitics. This directly showcases your ability to bridge technical depth and strategic framing — your unique selling point.

---

## Module 5 — Analytic Writing & Briefing (Integration)

> Foresight is a *writing and briefing* job first. This module ties the others together.

### Why it matters
The best analysis is worthless if it can't be communicated to a busy decision-maker. Your teaching, curriculum, and book-writing background is a real head start here — you already translate complexity for an audience. This module adapts that skill to *analytic* conventions.

### Core concepts

- **BLUF (Bottom Line Up Front)** — lead with the judgment, then support it. The opposite of academic build-up.
- **Estimative language / Words of Estimative Probability** — the disciplined vocabulary for expressing confidence ("likely," "highly likely," "roughly even chance") and *separating* your confidence in a judgment from the probability of the event. Learn Sherman Kent's framework and the modern IC standard.
- **Analytic Line vs. evidence** — clearly distinguishing your judgment from the facts supporting it, and flagging assumptions and information gaps explicitly.
- **The finished-intelligence format** — key judgments, supporting analysis, indicators/outlook. Study the structure of publicly released assessments (e.g., annual threat assessments) as models.
- **Briefing** — condensing a written product into a decision-maker's few minutes.

### Drills
1. Rewrite one of your earlier module outputs in strict **BLUF** format.
2. Take three judgments you've written and assign each an **estimative-probability** term; write one sentence justifying the confidence level for each.
3. Turn one 2-page product into a **3-slide / 3-minute brief**.

### Resources
- **Sherman Kent, *Words of Estimative Probability*** — short, foundational, public.
- **ODNI analytic standards (IC Directive 203)** — the official standards for analytic tradecraft and estimative language; publicly available.
- Publicly released **Annual Threat Assessments** — read as *structural models* for format and estimative language (not for content to reproduce).

### Portfolio output
A polished **2-page finished-analysis sample** with a BLUF, clear key judgments, estimative language, and an "indicators to watch" section — your single best writing sample for an analytic application.

---

## Suggested roadmap (flexible, ~8–10 weeks)

| Phase | Weeks | Focus | Milestone artifact |
|-------|-------|-------|--------------------|
| 1 | 1–3 | Module 1 (SATs) — foundational | ACH + Key Assumptions sample |
| 2 | 3–5 | Module 2 (Foresight) | 2x2 scenario brief |
| 3 | 5–7 | Module 3 (CI breadth) — overlap with policy | NCF dependency map |
| 4 | 6–8 | Module 4 (Policy/geopolitics) | Strategic context memo |
| 5 | 7–10 | Module 5 (Writing) — apply across all prior outputs | Finished-analysis sample + brief |

Run Module 5 (writing) *continuously* — apply its standards to every artifact from Modules 1–4 rather than saving it for the end.

---

## Self-assessment checklist

You've closed the gaps when you can honestly check these:

- [ ] I can run an ACH and a Key Assumptions Check on a real question without notes.
- [ ] I can build a defensible 2x2 scenario matrix from two critical uncertainties.
- [ ] I can name all 16 CI sectors and explain the NCF framework and why it matters.
- [ ] I can trace a cross-sector cascading failure three hops deep.
- [ ] I can summarize NSM-22 and its significance in plain English.
- [ ] I can write a BLUF product using correct estimative language.
- [ ] I have a portfolio of 5 short analytic artifacts demonstrating the above.

---

## Turning gaps into an interview narrative

Don't hide the pivot — frame it. Your story: *"I come from hands-on cyber operations and security education, which gives me technical depth and risk-framework fluency most analysts lack. I've deliberately built the estimative and foresight tradecraft on top of that — here are the analytic products to show it."* That framing turns "career-changer" into "rare technical-plus-strategic hybrid," which is exactly what a foresight shop watching emerging-technology risk wants.

Your two standout bridges to keep emphasizing:
1. **Risk-framework fluency** (NIST/RMF/FedRAMP → a *risk* center).
2. **Emerging-tech / AI literacy** (maps directly to NRMC's "malicious exploits of emerging technology" watch area).

---

*Note on sources: all resources listed are open-source or publicly released government/academic materials. Where classified specifics exist (e.g., some tradecraft and threat detail), this guide stays at the publicly documented conceptual level.*
