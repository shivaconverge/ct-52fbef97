# The Circuit Thesis — pitch deck (v2), full content

> Machine-readable transcription of the investor deck at
> `loop_hierarchy/decks/circuit-thesis-v2/index.html`
> (served at http://avinashs-macbook-air.tailfcedfe.ts.net:8090/).
> 15 slides. Bold marks the emphasis used on the slide itself. `[Figure]` blocks
> describe the visual; `[Assets]` lists the images the slide uses.
>
> Company: an AI harness ("the machine") for autonomous, long-running agents.
> Founders: Nitin Jindal, Gagan Gupta, Avinash Saxena (IIT Delhi '06).
> Core vocabulary: work is a *circuit* (feedback loop), not a flowchart; circuits
> nest as a *fractal*; the *world* is the outermost ring; the model is a *battery*;
> humans are *players* who steer attention; the machine is never "done".

---

## Slide 1 · Title

**The Circuit Thesis**

> **Work is a circuit. It isn't real until it comes back.**

---

## Slide 2 · The answer, first  `(eyebrow: 00 · The answer, first)`

### Imagine running a business like a multiplayer game — autonomous, always on.

The machine plays around the clock — **finding opportunities, dreaming plans,
right-sizing ambition, building, shipping, selling — and folding the world's
answer back into the plan**, going around again. A fractal of circuits wired
through the world.

Humans aren't operators inside it. They're **players above it** — many at once,
each steering attention where they know the game best. The machine absorbs the
steer on its next revolution and keeps running.

Kicker: **So why doesn't this exist yet?**

[Figure] Nested running circuits at center ("the machine — always on"); three
human glyphs outside ("players — steer attention") casting dashed attention
beams onto different inner circuits. Caption: *many players · one machine ·
attention is the only input*.

---

## Slide 3 · The flood  `(eyebrow: 01 · The problem)`

### AI ships thousands of games. Nobody plays them.

[Assets] Three screenshots of single-prompt frontier-model games
(oneshot-1/2/3.jpg). Caption under grid: *frontier-model showcases — one
prompt, first output, untouched*.

Kicker: Impressive as "made by AI." In reality, **proof-of-concept quality** —
shallow thinking, wrong physics, no EQ. **True for games, true for business.**

---

## Slide 4 · The diagnosis  `(eyebrow: 01 · The problem)`

### Not a skill problem. Agents are built on the wrong shape.

Agents were supposed to find opportunities, dream the plan, and run the
business. The output is always **proof-of-concept grade**.

That is not a leaf problem. Quality at the leaf is manufactured by **the rings
above it** — and today every ring is wrong. At the root: a **wrong picture of
the world**, with no wire to correct it.

Kicker: Wrong at every scale — **fractally wrong** — and the outermost ring,
**the world**, isn't even in the circuit.

[Figure] Five dashed (broken) concentric rings labeled, inside-out:
*output: POC* → *first step — unchecked* → *plan — narrow & shallow* →
*goal — mischosen* → *ambition — mis-sized*; a sixth, barely-visible ghost ring
outside: *the world — not wired in*. Footer: *the world ring missing · nothing
can close*. Caption: *Fig. 1 — wrong at five scales; the sixth ring missing
entirely.*

---

## Slide 5 · The team  `(eyebrow: 02 · The team)`

### Three founders who've built together since 2006.

- **Gagan Gupta** — **Model architecture & training**. **Four US patents** in
  computer vision. **Twenty years of production deep learning.**
- **Nitin Jindal** — **GPU inference at scale** — frontier-model performance at
  production economics. **NIST-ranked** vision work.
- **Avinash Saxena** — CTO of Zomato. Founder of Roposo & BarRaiser. Built
  consumer products — and the AI that ran them — **at India scale**.

[Assets] paris-2008.jpg — the three at a Paris café, captioned *Paris, 2008.*

Chips: `IIT Delhi '06 — same batch` · `18 years building together` ·
`shipped Roposo's media compression — cost −30%`

---

## Slide 6 · First principle  `(eyebrow: 03 · First principle)`

### An open circuit carries no current.

Anything — a feature, a market, a company — is a circuit: **what comes out
returns to shape what goes in.**

*Work is a __fractal__ of circuits, and the outermost ring is __the world__ —
nothing closes until it passes through it.*

*That is __fractally right__.*

[Figure] Six nested closed rings, inside-out: *keystroke ⊂ function ⊂ feature ⊂
product ⊂ company ⊂ the world*; footer: *seconds ⊂ minutes ⊂ days ⊂ quarters ⊂
decades ⊂ reality*. Caption: *Fig. 2 — the same closed shape, six scales deep.*

---

## Slide 7 · Why now  `(eyebrow: 04 · Why now)`

### The model is a battery.

LLMs have absorbed every playbook ever written — **code, design, markets,
operations**. Enormous charge, sitting still.

Current needs a closed circuit **through the world**: draw, check, return,
draw again.

Kicker: **Extraction is the art.** Every model release adds charge — the
circuit is the extractor.

[Figure] A battery cell ("the model", charge marks inside) wired into a closed
loop that passes through a box labeled *world*, with current arrows; labels
*the circuit* / *current*; footer: *current only flows through the world*.
Caption: *Fig. 3 — charge is not power.*

---

## Slide 8 · What we're building  `(eyebrow: 05 · What we're building)`

### The machine that closes them.

It takes a goal, explores the opportunity space, dreams the plan,
**right-sizes the ambition** — and runs until the result is real **in the
world**. Three things hold the shape:

1. **Thinks wide and deep.** A slower circuit holds the whole opportunity
   space — approaches, risks, unknowns — feeding direction down.
2. **Makes results real.** Nothing lands unless verified better — against the
   **live, deployed world** — compute compounds; POCs can't.
3. **Right-sizes the run.** Grows circuits, **prunes what's finished** — the
   run itself never tires.

Kicker: Coherence isn't a property of the model. It's manufactured by the shape.

---

## Slide 9 · The prize  `(eyebrow: 06 · The prize)`

### Flowcharts do tasks. A fractal of circuits runs a company.

| | Tasks — *the flowchart ceiling* | A company — *the circuit horizon* (winner) |
|---|---|---|
| Autonomy | Minutes of autonomy. One pass through the boxes, then a human notices, re-prompts, and reruns. | Always on. Every ring verifies the rings inside it; the plan redraws itself. |
| Pricing | *priced against software budgets* | *priced against the revenue it creates* |

---

## Slide 10 · Exhibit A  `(eyebrow: Exhibit A · The witness)`

### Early results are promising. Coherence: 40 → 72 → 720+ hours.

Three months of rigorous experiments — **billions of tokens burned**. Below,
one of them: the same goal, a Contra-class run-and-gun, given to three
machines. The variable that decided it: **the shape around the model**.

Three columns:

1. *The flowchart* — **Claude ultracode · Opus 4.8** (exh-opus-uc.jpg):
   One shot: **nothing playable at all**. Handed the full spec: this.
   **A proof of concept.**
2. *The flowchart · newest model* — **Claude ultracode · Fable 5**
   (exh-fable-uc.jpg): A stronger model, a prettier screenshot — still
   **a proof of concept**.
3. *The circuit · older model* — **Our harness · Opus 4.8** (exh-harness.jpg,
   winner): Weeks unattended, gated, verified, live — **the older model,
   inside the circuit, wins**.

Disclosure line: **matched:** goal text · **different:** the shape — the
circuit ran the **older** model and won anyway.

Kicker: The older model, inside the circuit, **beat the newest model one-shot**.

---

## Slide 11 · Profile — Nitin Jindal  `(eyebrow: ● The team · profiles)`

- **LLM & VLM inference optimisation** — quantisation, KV-cache, speculative
  decoding, hardware-aware compilation, on GPU clusters and edge silicon. For a
  machine that burns billions of tokens, **inference cost is the COGS**.
- Extreme-efficiency proofs: face authentication running **one year on a
  battery**; 8-face simultaneous recognition on a low-cost embedded chip.
- Face-recognition algorithm ranked **worldwide top-25** on the US NIST FRVT
  benchmark.
- MS, Vision & AI, Grenoble · IIT Delhi CS '06, **Best Graduation Project**.

[Assets] nitin.jpg (portrait); evidence row ev-face/ev-iris/ev-inspect/ev-toll
— *field systems — face recognition · iris · inline QA · toll automation*.

---

## Slide 12 · Profile — Gagan Gupta  `(eyebrow: ● The team · profiles)`

- **Full LLM lifecycle** — distributed pre-training, instruction tuning,
  preference optimisation, multimodal (VLM) alignment.
- Vision systems shipped worldwide: **Walmart** — photo-to-product search over
  millions of items in under a second; **Disney Orlando** — 99%+ people
  counting at every park gate.
- Named inventor on **four US patents** in computer vision and face recognition.
- Masters, INRIA France · IIT Delhi CS '06 — co-built Roposo's compression,
  **infrastructure cost down 30%**.

[Assets] gagan.jpg (portrait); evidence row ev-aerial/ev-track/ev-count/
ev-synopsis — *field systems — aerial detection · tracking · counting · video
synopsis*.

---

## Slide 13 · Profile — Avinash Saxena  `(eyebrow: ● The team · profiles)`

- **Zomato** — CTO. India's food-delivery giant, through its early
  hyper-growth. → today: Eternal, listed on NSE, ~$28B market cap
- **Roposo** — founder. Consumer short-video platform; $21M raised from
  **Tiger Global**, India Quotient, Binny Bansal. → acquired by InMobi's
  Glance; Google later invested $145M
- **BarRaiser** — founder & CEO. AI-powered interview intelligence. → today:
  running product, tech and sales across India, the US and the UK

[Assets] avinash.jpg (portrait); logo chips Zomato / Roposo / BarRaiser.

Kicker: After years running sales as much as software, across three
continents — back to the eternal love: **building**.

---

## Slide 14 · FAQ  `(eyebrow: Q&A · Before you ask)`

### The questions you're already asking.

1. **"Isn't this just Claude in a while-loop?"**
   A while-loop drifts in minutes. A circuit verifies every step against the
   world — **that's what 720 hours of coherence means**.
2. **"What happens when the next model drops?"**
   **Our ceiling rises for free.** Anthropic sells the engine; we sell the
   self-driving car.
3. **"Who's accountable when it runs alone?"**
   **Today: players hold the gate.** Trust is earned run by run; we're raising
   to build the robustness that widens it.
4. **"Doesn't it just burn tokens forever?"**
   **Does a company ever finish?** When one opportunity dries up, the machine
   finds the next — spend follows returns, not a clock.
5. **"Why won't the labs build this?"**
   They're winning the model war — **anchored to today's users and their own
   stack**. The shape is a different game, and every better model makes ours
   better.
6. **"Where's the moat?"**
   Three months, billions of tokens of run-lessons **baked into the shape** —
   and every run teaches the next.
7. **"What about hallucinations?"**
   A hallucination is imagination without a gate. Inside ours it's **a feature,
   not a bug** — the dreaming is the search, and nothing lands until the live
   world confirms it.
8. **"720 hours can't fit in a context window."**
   Let's leave some things for **the secret sauce**.

---

## Slide 15 · Close

**The Circuit Thesis**

# The game is already running. Come play.

> Bet on the shape that comes back.

*(footer: 2026 · end of deck)*

---

## Appendix — notes for an agent working with this deck

- **Narrative arc:** thesis poster → the answer first (imagine) → the problem
  (flood of POC games + fractally-wrong diagnosis) → team → first principle
  (circuits) → why now (battery) → what we're building → the prize → evidence
  (Exhibit A) → founder profiles → FAQ → close.
- **Language rules held throughout:** the machine is never "done" or "built" —
  always running/being built; "players" refers only to humans steering the
  machine (founders are "the team"); the world appears in every ring diagram
  as the outermost ring; "coherence"/"drift" used sparingly.
- **Open items (not yet in the deck):** a wedge slide — wedge as *criterion*
  (worlds that answer fast, machine owns the whole loop, shots cost ≈ compute;
  games only an example), $10M seed / 18 months, milestone ladder
  M1 Hardened → M2 Factory works → M3 Portfolio in motion; use of funds
  ≈ 55% compute / 25% robustness & gate / 15% world plumbing / 5% founders-ops.
- **Related material:** partner-review flowcharts at
  `loop_hierarchy/decks/partner-review-flowcharts.md`; business-model matrix at
  `loop_hierarchy/decks/business-model-matrix.html`.
