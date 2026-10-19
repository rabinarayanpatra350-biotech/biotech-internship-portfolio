# Biotechnology Research Internship — Complete Portfolio

**Rabi Narayan Patra** | 26 September – 31 October 2026 | 5 weeks, 5 deliverables

A complete record of the Biotechnology Research Assistant internship: a single biotechnological product problem
carried from literature review through experimental design, laboratory procedure, sequence analysis, prototype
design and finally a consolidated report and research briefing.

## The project, in one paragraph

PHA bioplastic is fully biodegradable, biocompatible and made from renewable carbon — and it costs
**US$4–6 per kg** against **US$1.1–1.4** for the petrochemical plastics it must displace, with the carbon
feedstock accounting for **up to half** of production cost. The internship therefore treats PHA as a
**feedstock** problem rather than a polymer-chemistry problem, and pursues a process that takes its carbon from
food waste, delivered by a modular unit sited where the waste is generated.

## The five weeks

| Week | Deliverable | The question it answered |
|---|---|---|
| **1** | [Experimental design and literature review](week1/) | Can the product work, and what constrains it? |
| **2** | [Laboratory procedure document](week2/) | How is the process run at the bench? |
| **3** | [Bioinformatics analysis](week3/) | Which enzyme, and how do we know? |
| **4** | [Prototype design document](week4/) | What would the product be? |
| **5** | [Final report and briefing deck](week5/) | How does it all hold together? |

## How the weeks interlock

This is the portfolio's central claim, and it is documented rather than asserted: **ten of the prototype's
design decisions trace to specific findings in earlier weeks**, and none of them is a preference.

- The prototype's **pH-static control loop** holds the reactor at **1 g/L** — one-fifth of the inhibition
  threshold that **Week 2** measured. A week that had said only *"VFA feeds are difficult"* would have produced
  no design at all.
- The prototype's **synthase-selection step** exists because **Week 3** found a class-specific lipase-box
  signature that predicts substrate range. The enzyme is chosen to suit the feed rather than the feed bought to
  suit the enzyme.
- The prototype's **modular architecture** exists because **Week 1** established that the feedstock's cost
  advantage is destroyed by transporting it. Wet waste is 75–80% water.

The dependency also runs **backwards**: the prototype's cost analysis re-opened Week 1's premise and found it
holds, but for a reason Week 1 had not identified — food waste is not merely cheap, it is **expensive to
transport**, so the value lies in not moving it.

## The failure, reported in full

**Week 3's first multiple-sequence alignment method was broken.** It produced a plausible-looking output and a
phylogeny that was wrong — the most dangerous kind of error, because nothing about the output signalled a
problem. It was caught by a validation test asking whether same-class sequences cluster closer together than
different-class sequences. They did not: its distances correlated **−0.16** with an independent estimator and
**inverted** the taxonomic signal. It was replaced with a reference-guided alignment passing at **r = 0.942**.

**Lesson: an alignment is a hypothesis. An unchecked one is an assumption dressed as a result.** The same
verification principle recurs three times across the internship — orthogonal analytical methods, an independent
distance estimator, a stoichiometric mass-balance ceiling — and that recurrence is the strongest evidence this
was one project rather than five.

## What the internship produced that stands regardless

1. **The cost structure of PHA**, documented with sources, with the feedstock identified as the determining
   line item.
2. **A quantified constraint** — VFA inhibition above ~5 g/L, stated as a design requirement rather than a
   difficulty.
3. **A usable screening result** — the class-specific lipase-box signature predicts substrate range from seven
   residues of sequence, a tool any PHA programme can apply whether or not it adopts this process.
4. **A design principle** — a limitation you can measure becomes something you can engineer against.

## Repository contents

```
├── README.md
├── internship_overview.md                  # the arc across the five weeks
├── week1/  summary.md + submission_description.txt
├── week2/  summary.md + submission_description.txt
├── week3/  summary.md + submission_description.txt
├── week4/  summary.md + submission_description.txt
└── week5/  summary.md + submission_description.txt
```

Each week's `submission_description.txt` is a **verbatim copy** of what was submitted to the internship portal,
so the portfolio reproduces the actual submissions rather than paraphrasing them.

**In the v1.0 release bundle:** the five reports in DOCX and PDF, the Week 5 briefing deck in PPTX and PDF, the
five per-week reproducibility bundles, and a combined archive of the whole portfolio.

## Per-week repositories

Each week was submitted in its own repository, as required; those remain the canonical submissions and are
linked from the table above.

## Author

**Rabi Narayan Patra** — Biotechnology Research Intern, 2026.
GitHub: [@rabinarayanpatra350-biotech](https://github.com/rabinarayanpatra350-biotech)
