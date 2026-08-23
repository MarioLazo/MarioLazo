<div align="center">

# Mario Lazo

**I help enterprises turn AI and data investments into operating change that executives can fund, govern, and scale.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mariolazo/)
[![Book](https://img.shields.io/badge/Book-AI_Data_Privacy_%26_Protection-23201B?style=flat-square)](https://a.co/d/08QZ6bfp)
[![Agentic CoE](https://img.shields.io/badge/Agentic_CoE-⭐_16-1F5F5B?style=flat-square&logo=github&logoColor=white)](https://github.com/MarioLazo/agentic-coe)

</div>

---

## Most people think production AI fails for technical reasons

It usually does not. And the reason is more uncomfortable than "the model was
not good enough."

Across 623+ case studies and production implementations, and 65+ practitioner
interviews with the people actually running these systems, the pattern that
repeats is not a model problem:

> **Most production AI failures are meaning failures.** The system answered a
> question nobody needed answered, optimised a metric nobody cared about, or
> ran at an autonomy level the organisation was not equipped to govern.

Every one of those systems worked. That is what makes them hard to catch.

## The question that finds them

> ### *"If this gives the right answer to the wrong question, how would you know?"*

Not rhetorical. It needs a specific operational answer **before** architecture
work begins, and the most dangerous response is a confident, fast one from a
team that has never considered it.

---

## How I work

**Vendor-agnostic, first principles, no BS.** I want the abstractions that
hold, and the real lessons from what shipped, including the failures.

**Inversion first.** Ask how this fails before asking how it succeeds. Most of
what I know came from post-mortems, not launches.

**Intellectual honesty about the gaps**, including in my own work. A confident
answer that has not been stress-tested is the most dangerous artifact in the
room. My published material carries a corrections ledger for that reason.

---

## The frameworks I work from

From production post-mortems, not theory. Each one exists because something
went wrong in a way the existing vocabulary could not name.

**The Meaning Gap.** The distance between what a system optimises and what the
organisation actually needs. Two axes: *Run* (can it execute reliably?) and
*Reason* (is it reasoning about the right problem?). Most organisations measure
only Run. The dangerous quadrant is **Precise but Wrong**: high operational
confidence in a system solving the wrong problem. *Presented at the Toronto
Machine Learning Summit.*

**Three Proofs.** Every initiative must demonstrate **Technology** (does it
work?), **Value** (does it matter?), and **Competence** (can *we* run it, and
fix it when it breaks?). Each has a predictable failure mode when missing:
succeeds in POC and fails at scale; works but moves no metric; delivers value
until the first incident, then has no owner and no path back.

<sub>Competence is the harder question and the one that predicts whether a pilot
survives. A deployment can be entirely compliant and still fail it, because
nobody on the client side can operate or remediate it at 2am.</sub>

**Five Modes.** What is *your* job now, as capability increases:
**Doing** → **Directing** → **Delegating** → **Designing** → **Defining**.
The human moves from doing the work, to specifying the steps, to specifying the
outcome, to setting the environment, to setting standards for work they will
never see.

<sub>The asymmetry is the point: <b>autonomy transfers down that ladder and
responsibility does not.</b> An agent cannot be held accountable, so the further
you delegate, the more of your job becomes deciding what "correct" means in
advance, because you will not be in the room when it is decided.</sub>

**CLASSIC.** Seven dimensions for measuring whether a deployment is actually
working: **C**ost, **L**atency, **A**ccuracy, two context-chosen **S** slots
(Security, Safety, or Supportability), **I**ntegrity, **C**ompleteness. Built to
be said out loud in a room with a client, not computed offline.

<sub>The two flexible slots are deliberate. A frame that forces Safety into a
conversation about a read-only reporting agent has wasted a slot, and one that
omits Security in a PHI environment is negligent.</sub>

**Agent Seniority Ladder.** Five levels of autonomy, each with distinct data
requirements, risk profile and governance needs. The most common misjudgment:
**claiming Level 4 readiness while operating at Level 2.**

---

## Current work

### 🏛️ [Agentic CoE](https://github.com/MarioLazo/agentic-coe) &nbsp;·&nbsp; ⭐ 16

The practitioner's map for an **Agentic Center of Excellence**: the operating
model, governance structure, decision rights and quality gates that move
enterprise AI past pilot purgatory.

Most AI programs stall not because the technology fails, but because nothing
around it is built to fund, govern or scale what works.

Ships the **Agent Card** documentation standard, a ten-gate **Pre-Flight
Checklist**, the **BXT Scorecard** for use-case selection, and grounding-layer
depth on retrieval, evaluation and cost engineering.

<br>

### 📘 [From Vibe Coding to Agent Engineering](https://github.com/MarioLazo/vibe-coding-to-agent-engineering) &nbsp;·&nbsp; *Part 1, free*

A course for people who have never measured an agent.

It opens on a randomised controlled trial where experienced developers
predicted they would be **24% faster** with AI, believed afterwards they had
been **20% faster**, and were measured **19% slower**. They were reviewing
their own work the entire time.

**If your quality signal is your own impression, that is the size of the error
you are working with.** Now hand the work to an agent.

<br>

### 🕒 [Agent Reliability Engineering](https://github.com/MarioLazo/agent-reliability) &nbsp;·&nbsp; *Part 2*

**The 3pm Test.** Would you deploy this agent on a Tuesday at 3pm?

Everything after it works. Six notebooks that run offline, deterministically,
in about ten seconds, with **no API key and no dependencies**.

```
agent             | correct | own tests | meaning
--------------------------------------------------
A-ships-fast      |  FAIL   |   PASS    |  PASS
B-by-the-book     |  PASS   |   PASS    |  FAIL
C-read-the-ticket |  PASS   |   PASS    |  PASS
```

`own tests` is green for all three. It is also the column every agent demo
shows you.

<sub>Part 3, on voice and multimodal agents, is in development.</sub>

---

## Track record

| | |
|---|---|
| **NetSuite** | Global professional services and customer success capabilities: enterprise applications, integrations, global delivery, practice economics |
| **Blue Prism · UiPath** | Automation, enterprise adoption, customer outcomes, transformation |
| **IG Labs** | Enterprise AI strategy, agentic operating models, governance, solution architecture, reusable AI capabilities |

**Where I create the most value:** AI and data transformation · enterprise AI
strategy · AI governance and trust · practice and commercial leadership.

---

## Writing, speaking, teaching

**Books.** *AI Data Privacy and Protection*, co-author, Technics Publications,
2024. A second, on building the Agentic Center of Excellence, is in progress.

**Agentic Field Notes.** Dated write-ups from actual builds. What happened,
what broke, what it cost. **Never edited after publication**, because a dated
note cannot go stale.

**Speaking and teaching**

- **"The Meaning Gap"**, Toronto Machine Learning Summit. Why systems that answer correctly still fail
- **MLOps World / GenAI World**, Austin
- **University of Texas at Dallas**, teaching AI coding agents, bridging academic curriculum and production engineering

---

## Let's compare notes

I am looking for **research collaboration, thought partnership, and people
building the data and AI community.**

If you are working on the hard part, not whether AI *can* do something but
whether an organisation can trust it, govern it, operationalise it and prove
value from it at scale, I would like to hear from you.

Practitioners with production scar tissue. Researchers working on evaluation
and governance. Executives navigating the operating-model question.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mariolazo/)

</div>

---

<sub>**Areas of interest** · AI Transformation · Data & AI Strategy · AI Adoption & Enablement · Intelligent Automation · AI Governance · Enterprise Operations · AI/Data Practice Leadership</sub>

<sub>*Technical rigor matters. So does building systems that serve people, not just metrics.*</sub>
