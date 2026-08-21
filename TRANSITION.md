# What changed in August 2026, and why

Between January and July 2026 this repository documented a framework for placing an AI system under Regulation (EU) 2024/1689. Since August 2026 it documents something else: the reconstruction of one workflow and the measurement of the distance between what an organisation declares about it and what its own material establishes.

Nothing published before that point has been withdrawn, rewritten or backdated. The earlier framework is still here, under [`ai-act-gates.md`](ai-act-gates.md), still versioned, and it is still applied. What changed is where it sits in the order of work. This file records what moved and on what grounds, because a positioning that changes without stating its reasons is indistinguishable from one that changes because the last one did not sell.

## 1. What the earlier work was

| | |
|---|---|
| **Object** | A regulatory position: is this AI system prohibited, high risk, limited risk, minimal, and which obligations follow |
| **Method** | Six gates read against Articles 5, 6, 50, 51 and 53, article by article |
| **Deliverables** | A free scored diagnostic, a written position report, continuous regulatory monitoring |
| **Vocabulary** | Pre-conformity · position assessment · classification · readiness |
| **Public record** | Method card v1.1, April 2026, 23 pages, OpenTimestamps-anchored · screening of 50 European AI companies, DOI [10.5281/zenodo.19671328](https://doi.org/10.5281/zenodo.19671328) · two further papers, May 2026 |

That work was not wrong. It was answering a question asked one step too late.

## 2. The four facts that moved it

**2.1 The April screening measured the market against itself.** Screening 50 European AI companies returned 74% triggering high-risk classification under Annex III and 96% publishing no AI Act position. The second figure reads as latent demand only if you assume the 96% are looking for a position and have not found one. The alternative reading is that a position is not what they are looking for, and nothing in the data separates the two. A finding that supports two opposite commercial conclusions equally well does not support either.

**2.2 The regulatory clock moved back sixteen months.** The Digital Omnibus provisional trilogue agreement of 7 May 2026 (European Parliament press release IPR42011, subject to formal adoption by the co-legislators) moved standalone Annex III high-risk obligations from 2 August 2026 to 2 December 2027, and Annex I product-embedded safety components from 2 August 2027 to 2 August 2028. An offer whose argument is a date loses its argument when the date recedes. This is a dated, checkable fact, and no version of a deadline-driven offer survives it without changing object.

**2.3 Classification assumes what is missing.** Qualifying a system article by article presupposes knowing how the work actually runs. That is the part that is not known. Two independent March 2026 studies size the gap: Okta and Apprize360 (292 executives, 492 knowledge workers, seven countries) find 90% of leaders confident in their organisation's visibility over AI tools while more than half of workers admit using tools without approval; TrustedTech and Censuswide (2,001 employees, UK and US) find senior decision-makers using unapproved AI tools at 65% against 31% for the staff they manage. Both were commissioned by vendors with an interest in establishing a governance deficit, run on modest samples, with no breakdown by company size, and those reserves travel with the figures every time they are reused. Read together they say the buyer of a compliance report is the person least positioned to know what the report should cover. Compliance work was being sold downstream of a map nobody had drawn.

**2.4 The score hid the object.** A 0-100 band is an answer. The object of the work is a gap. A single number aggregates exactly what the analysis exists to pull apart, and it lets a reader stop at the number instead of at the line that carries no source. The band is not carried over, and no numeric threshold replaces it until a series of real reports exists to calibrate one.

## 3. What follows from those four

The unit of sale is no longer a system, a company or a compliance state. It is **the distance between the declared and the established, on one workflow the director designates**, measured from a position the organisation cannot occupy from inside itself. That position is what the method is named after.

Three consequences, each of which costs something:

- **The single source is stated as a limit, not hidden as a scope.** At the Baseline the source is the director alone. What escapes them does not become visible because they are questioned better, so the Baseline measures the gap and does not close it.
- **What rests on someone else's time estimate leaves the Baseline.** First-pass acceptance rate and rework minutes, then structural incompatibilities, moved to the Full Map, where the estimate comes from the people who do the work rather than from the person who decides.
- **A level is allowed to conclude that there is no next step.** Written as conditions observable in advance, before any report exists, rather than as an appreciation formed on reading.

## 4. What was kept

- **The gate framework**, at [`ai-act-gates.md`](ai-act-gates.md), unchanged in substance and still versioned. It moved downstream: it names the obligations once a workflow has been reconstructed, instead of standing in for the reconstruction.
- **The published research**, exactly as deposited. See section 6.
- **The rules that never depended on the positioning**: nothing is sold after the report · every finding states what it rests on · every figure carries its reserve at every reuse, not only on first mention · a figure that cannot be supported is withdrawn rather than defended.

## 5. What was removed, by name

The free scored diagnostic · the position report sold as "Full Report" · continuous monitoring as previously described · the 0-100 band · and four expressions that named an object that no longer exists: *pre-conformity*, *position assessment*, *we classify AI systems*, *private independent assessment authority*.

Also removed, and for a different reason: a table of upcoming publications with announced dates in [`zenodo-mirror`](https://github.com/sprinkling-act/zenodo-mirror). Those dates passed without deposits. It was deleted rather than rolled forward, because rolling a missed date forward is how a public record stops being one.

## 6. What is not corrected, on purpose

The three Zenodo papers and the April method card use the earlier vocabulary. They are not being edited.

A timestamped document guarantees one thing, which is that this text existed on that date. Editing it to match a later position destroys that guarantee and leaves nothing in its place. The papers are dated, their DOIs resolve, their OpenTimestamps proofs verify against the Bitcoin chain, and they say what was thought in April and May 2026. Read them as of their date.

The same rule applies to this repository's own history. Commits from before August 2026 were not rewritten.

## 7. What did not change

The entity: Sprinkling Act, Brussels, BCE BE 1034.962.482, self-funded, no venture capital, no commercial relationship with AI vendors, regulators or certification bodies. The repository name: `methodology` was not renamed to `human-in-the-map`, because the site, the Zenodo deposits and the timestamped method card all link to the current path, and a rename would break every one of those links to gain a label. Still not an audit, still not a certification, still not legal advice.

---

Method as published: [`README.md`](README.md) · version history: [`CHANGELOG.md`](CHANGELOG.md) · live reference: [sprinklingact.com/methodology](https://sprinklingact.com/methodology)

*Maintained by Sprinkling Act · Brussels, Belgium*
