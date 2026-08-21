# Human in the Map

The Sprinkling Act method for reconstructing how one AI workflow actually runs, and for measuring the distance between what an organisation declares about it and what its own material establishes.

Live reference: [sprinklingact.com/methodology](https://sprinklingact.com/methodology)
Current version: v1.6, August 2026. See [`CHANGELOG.md`](CHANGELOG.md).
License: MIT.

This repository holds three documents. This one describes the analysis. [`ai-act-gates.md`](ai-act-gates.md) describes the EU AI Act gate framework, which is the regulatory layer and comes after the analysis, not before it. [`TRANSITION.md`](TRANSITION.md) records what this repository documented until July 2026, why that object was abandoned, and what was deliberately left uncorrected.

## 1. The position

The established models place a person inside a decision. **In the loop** when the system waits for their approval, **on the loop** when they watch and may intervene, **in command** when they hold final authority. All three are local, and each describes one control point at a time.

None of them answers the question a director actually asks. That question is not *who approves this output*, it is *where are the humans across everything now running, and what does the whole set cost*. It is a question about the map, not about the loop.

Human in the Map is the position that question is asked from. It is also the position an organisation cannot occupy from inside itself, which is the entire reason a third party is involved.

## 2. What is measured

**The distance between the declared and the established, on one named workflow.**

That distance is not a commercial intuition. Two independent March 2026 studies size it.

*AI Agents at Work 2026*, Okta and Apprize360, 292 executives and 492 knowledge workers across seven countries including France and Germany: 90% of leaders report confidence in their organisation's visibility over AI tools, while more than half of workers admit using tools without approval.
*Status: converging sources. Commissioned by an identity management vendor, with an interest in establishing a governance deficit. Modest sample, no breakdown by company size.*

*TrustedTech* and *Censuswide*, 2,001 employees in the UK and the US: senior decision-makers use unapproved AI tools at 65%, against 31% for the staff they manage.
*Status: converging sources. Commissioned by an IT reseller. UK and US only, no continental Europe, no breakdown by company size.*

These caveats travel with the figures every time they are reused, not only on first mention.

What the two studies make possible: the director is simultaneously the person who believes themselves the most covered and the person contributing the most to what they cannot see. The analysis measures that distance in one particular case, theirs. It is an object in its own right, not a degraded inventory.

**Two words for two things.** The visibility gap is what is measured: the distance between what a director describes and what the elements establish. Reconstruction is what happens in order to measure it: establishing what takes place from sources that are not people's recollection, then setting the two against each other. The first names the result, the second the method.

## 3. Three levels, three different questions

| | Question | Source | |
|---|---|---|---|
| **Evidence check** | What supports what you already know about this workflow? | Self-administered | Free · six questions · no account · nothing sent or stored |
| **Baseline** | Where does a director stand on the visibility gap, on one named workflow? | The director | €3,900 |
| **Full Map** | Every critical point the Baseline surfaced, with the gap document | The director and the three or four people who run the work | From €9,900 · requires a delivered Baseline |

Each level can conclude that there is no next step. The free tool has four outcomes, two of which route away from the offer: a deployment that is already documented, and no decision ahead. The Baseline concludes whether a Full Map is warranted, on conditions written in advance (section 8), not on an appreciation formed after reading.

The Baseline is a precondition for the Full Map, and the reason is methodological before it is commercial. The Full Map's central deliverable is the gap document: the difference between the measurement taken with the director alone and the one taken with the three or four people who run the work. Without a delivered Baseline there is no term of comparison, so the requirement is a constraint on the method rather than a step in a sales ladder. It has a second effect worth stating: a scoping report that can conclude *do not proceed* only means something if nobody skips it.

Two rules follow from that.

**The Baseline report is sealed before the first Full Map interview.** Revised after hearing the teams it would no longer be a comparison, it would be a reconstruction, and the gap it is supposed to establish would have been erased by the act of measuring it.

**The gap is attributed line by line, by the date of the element, not carried as a single quantity.** An element predating the close of the Baseline collection is a blind spot, established. One postdating it is drift, a finding in its own right. A line carried by a statement alone stays unattributed and is marked as such. The close of the collection is therefore dated in the report, distinctly from the readout date.

## 4. How the work runs

**01. The unit is a distance, not an inventory.** The scope is one workflow, named and bounded in writing before anything starts. What is measured inside it is the distance between what the director describes and what the elements they provide establish. We do not inventory an organisation's AI use: at the Baseline the single source is the director, and what they cannot see does not become visible because we question them better. The workflow examined is the one they designate, not one we select by comparing several, which would require the overview we have just said we do not have.

**02. Exports, not access.** We ask for material a team can share rather than credentials to their systems: an export, a shared calendar, a version history, a folder of dated files, a subscription invoice. Nothing is installed, no agent runs on the client side, nothing is left behind.

**03. Declared first, then checked.** We start from the procedure as written and from what the director describes of it, which at the Baseline is the single source. Then we look for the elements that would confirm or contradict it. Starting the other way round would tell us what the systems were configured to do, not what the organisation does.

**04. Every finding says what it rests on.** A finding rests on the procedure as written, on elements we could examine, or on an inference we make explicit. The reader always knows which.

**05. A gap needs a second source.** When the procedure and the elements disagree, we look for a second source of a different kind before presenting the point as established. One source contradicting another is a question, not yet a conclusion.

**06. Open questions stay open.** Where nothing available lets us check a point, it is reported as an open question. It is never quietly upgraded into an established fact.

**07. No score.** No grade, no maturity level, no percentage of an invisible total. A number would hide exactly what the analysis exists to surface.

**08. Dated and bounded.** The analysis holds for a scope and a date. Workflows move, tools get added, roles change. We say from what point a finding stops being reliable.

### Interviews by episode

Interviews never ask *tell me how this works*. They ask *the last time this task ran, what happened, in what order, with whom*. This is the Day Reconstruction Method (Kahneman et al., *Science*, 2004): reconstructing by episode reduces recall bias. It also imposes a constraint that is easy to miss, which is that the material has to be recent. Episodic memory does not carry months.

## 5. What the report contains

The reconstruction is the work; it is not the deliverable. The deliverable is the layer that makes the reconstruction decidable. A page that changes no decision belongs in the annex.

**01. The chain, not the list.** Each AI use is placed in its full chain of action, from the human input to the output actually used, with every transition named. A tool outside its chain is a line on an invoice, not a finding.

**02. Form and failure at each transition.** Each transition carries its form, person to tool or tool to tool, and where it fails, its error type. That crossing is what makes a finding comparable from one file to the next, and therefore indexable.

**03. The named authority, or its absence.** For each control point: who decides, who approves, who can halt. The absence of a name is the most frequent finding and the heaviest. It is also what Article 26(2) of the AI Act requires of deployers of high-risk systems.

**04. An evidence status on every line.** Four statuses, section 6. A gap is only established once a second source of a different kind confirms it.

**05. Rework time, at Full Map.** First-pass acceptance rate, and rework minutes, on the critical chains. They do not appear in the Baseline: estimating them means asking the people who do the work, not the person who decides, and an estimate of someone else's time is not a measurement. Without those two numbers the report stays a description; with them it becomes an arbitration. That is what separates the two levels, not a shortcoming of the first.

**06. The portable share of the skill.** What, in what the teams learned, would survive a change of tool. This single line often carries the decision on its own.

**07. Structural incompatibilities, at Full Map.** Where two tools adopted by different departments will produce friction once their data meet. The only finding that bears on the future, and the only one that requires a view from above, which is why it does not appear in the Baseline: a single source, looking from one position, cannot establish it. Where the Baseline glimpses one, it is recorded as an open question, never as an established finding.

**08. The expiry date.** From when each family of findings stops being reliable, and why. A date per family, not a general validity note.

## 6. Evidence statuses

Every line carries one of four:

| Status | Meaning |
|---|---|
| **Confirmed** | Declared and corroborated by an element of a different kind |
| **Declared, no independent trace** | Stated, nothing available confirms or contradicts it |
| **Gap established** | Declaration and elements disagree, and a second source of a different kind confirms the disagreement |
| **Open question** | Nothing available lets us settle it |

The rule of the gap is what a guarantee can be attached to. Any finding presented as established that cannot be evidenced on request is withdrawn, and the engagement refunded in full.

## 7. What elements can and cannot establish

The boundary is stated in advance, because a method that discovers its own limits during delivery has already sold something it cannot produce.

| Establishable on a provided element | Declaration only |
|---|---|
| Existence of a tool, from an invoice, a subscription, an export | Real intervention frequency |
| Dates and sequences, from a version history or a calendar | Real authority, as opposed to nominal authority |
| Volumes, from files or dated entries | What happens when something goes wrong |
| Existence of a validation field, and whether it is filled | What teams actually use |
| People who touched an artefact, where the export carries it | The portable share of the skill |
| | Structural incompatibilities still to come |

## 8. What a Baseline concludes

Three outcomes, written as observable conditions before the work starts.

**The scope warrants a Full Map** if at least one condition is observed: an AI use appears in the provided elements without appearing in the director's description · a decision point is identified with no observable holder · a divergence between the written procedure and the elements bears on an output that leaves the organisation · the director identifies, on reading, uses they did not know about.

**It warrants one conditionally** if the observed distance concentrates on a single identifiable, bounded point whose treatment does not require examining the whole.

**It warrants no next step** if none of those conditions is observed within the limits of the arrangement, or if no dated decision depends on the distance measured.

No numeric threshold is published while no series of real reports exists to calibrate one. These conditions will be revised on real data, with a dated changelog entry.

## 9. What the Baseline does not establish

Stated here, and repeated at the point in the report where each limit takes effect, never gathered into a closing *Limits* section.

**It does not establish an inventory of the organisation's AI workflows.** The source is the director alone. What they do not know does not become visible because they are questioned better.

**It does not establish what the teams do.** That is the blind spot the data quantifies: more than half of workers use tools without approval while their director reports 90% confidence. The Baseline measures that gap; it does not close it.

**It does not establish first-pass acceptance rate or rework minutes.** Both rest on a time estimate, and self-reported time is systematically overestimated. Here the distance is doubled, since the director would be estimating time spent by other people, a case the literature we consulted does not cover. Direction of the bias unknown, therefore never used as an argument. Both numbers are announced as Full Map deliverables.

**It does not establish structural incompatibilities.** That finding requires a view from above, which a single source looking from one position does not have. Where the Baseline glimpses one it is recorded as an open question, and it is established at the Full Map or not at all.

**It certifies nothing and judges nothing.** Not an audit, not legal advice, not a certification.

## 10. Where the AI Act fits

After the analysis, not before it. Most work sold as governance assumes the buyer already knows how the work runs today, which is exactly what is missing. The gate framework in [`ai-act-gates.md`](ai-act-gates.md) is what names the obligations once a workflow has been reconstructed.

Two articles bear directly on the analysis rather than on the classification:

- **Article 4**, AI literacy, applies to every deployer since 2 February 2025. The Commission Q&A of 7 May 2025 imposes no format but recommends documentation. The market answers it on the input side, with e-learning and attendance; nobody measures the output. Verified against the text: **Article 4 is not named anywhere in Article 99**, so the 15 M€ figure that circulates for AI literacy is wrong. Sanctions run through national law, with the operational frame at 2 August 2026.
- **Article 26(2)**, competence, training and authority of the people assigned to human oversight. High risk only, and that one does sit on the 15 M€ / 3% scale.

**The shorter lever is not the AI Act.** Annex III standalone high-risk obligations moved to 2 December 2027 under the Digital Omnibus provisional trilogue agreement of 7 May 2026, subject to formal adoption by the co-legislators, and that distance reads as permission to wait. It is not one, because Regulation (EU) 2016/679 already applies to the same facts. Article 28: a processor acting on your behalf requires a contract, and unapproved AI tools may fall under it. Article 30: a record of processing activities is required, and a reconstruction documents chains that the record ignores. Article 32: undocumented AI data flows fail the appropriate-measures standard by construction.

This is not a GDPR compliance exercise, not a data protection audit, and Sprinkling Act does not act as anyone's data protection officer.

## 11. What breaks at a hand-off

Research on hand-off failures produces a distribution that reverses the assumption most leadership starts from.

| Failure at the point of passage | Share |
|---|---|
| Signal corruption | 36.8% |
| Data gap | 29.1% |
| Referential drift | 27.3% |
| Capability gap | 6.8% |

Close to two thirds of failures are transmission problems. The capability gap, the one assumed first by almost every management team, weighs under seven percent. The question worth settling before funding anything: *is the problem that people do not know, or that what they needed never reached them?*

**Reserve carried with the figures**: proportions observed on multi-agent systems. We use them as a reading grid for human-AI chains, not as a prediction of any particular distribution.

## 12. What the method rests on

- **Star and Strauss, CSCW 1999.** The invisibility of work is an organisational process, not a property. Making it visible is therefore an organisational operation, and not one an employee can perform from inside.
- **Kahneman et al., *Science* 2004, Day Reconstruction Method.** Reconstructing by episode reduces recall bias. It also constrains the material to be recent.
- **Triangulation**, from organisational research: interview plus documents. The method has an established name, and we use it under that name.
- **Cheung, Cambridge, May 2026, *AI debt*.** The frame is published and carries no data. That is the hole this work sits in.
- **arXiv 2503.18238**, field experiment on 2,310 participants: people working in human-AI teams make 71% fewer direct edits and send 63% more messages. The work neither disappeared nor shrank; it moved from doing to instructing, and the part that grew is the part no job description contains. *Limits carried with the figures: an advertising task, no human-only condition, no capture of long-term collaboration.*
- **Eurostat `isoc_eb_ai`.** 70.9% of EU enterprises that gave up on AI cite the lack of skills. First declared obstacle in Europe, ahead of cost and of regulation. This is a population anchor, not a benchmark of what we measure.

**The term we claim: role debt.** Not *role drift*, which identity management already uses for the creeping accumulation of access rights. Role debt joins a family already forming, technical debt to AI debt to instruction debt, rather than being invented in isolation. Like any debt it has a principal, a rate, and a debtor, which is why it can be counted.

## 13. Index thresholds

Findings across engagements accumulate into an index. No public data calibrates what this method measures, so the thresholds are published before they are reached, with a public counter at [sprinklingact.com/index](https://sprinklingact.com/index).

| Threshold | Unlocks | Reason |
|---|---|---|
| **k = 5** | Publishing a broken-out cell | "Belgian company, HR tech, 40 employees" identifies it at two files. Usual floor in public statistics |
| **N = 30** | A distribution, quartiles only | Below it, you are describing the sample, not a population |
| **N = 100** | Deciles | Ten observations per decile |

`k` protects the organisations analysed, `N` protects the reader. Below N = 30, raw counts only: *of 12 files, 9 with no named authority* is true; *you are in the third decile* is not.

## 14. Limits

- The analysis covers the workflow agreed on. Other workflows in the same organisation may run very differently, and nothing here should be read as covering them.
- We work from the elements a team can share. Where a point cannot be checked against anything available, it is reported as an open question rather than resolved by inference.
- Not an audit and not a certification. Nothing is checked against a standard, no judgement is issued, and no result is opposable to a third party as proof of anything.
- Not legal advice. Sprinkling Act is not a law firm, not a notified body and not a certification body. A regulatory reading is an annotation on top of the analysis and does not replace qualified counsel.
- The analysis describes how a workflow runs. It does not decide whether to extend, renew, fix or stop, and it does not predict what a change will produce.
- **Measuring and solving are different trades.** Nothing is sold after the report: no tool, no licence, no automation, no reselling of anyone's platform. A measurer who sells the remedy destroys the economic condition of the measurement. This is what makes a finding checkable, rather than a promise of neutrality.

## 15. Citation

```
Shucrani, L. B. (2026). Human in the Map: reconstructing AI workflows and measuring
the distance between the declared and the established. Sprinkling Act, Brussels.
https://github.com/sprinkling-act/methodology
```

The April 2026 methodology card, a condensed snapshot of the gate framework at v1.1, is timestamped via OpenTimestamps and anchored on Bitcoin: [sprinkling-act/timestamps](https://github.com/sprinkling-act/timestamps).

Published research, DOI-indexed: [sprinkling-act/zenodo-mirror](https://github.com/sprinkling-act/zenodo-mirror).

## 16. What this repository is not

- Not software. It is a documented method that people apply.
- Not a legal opinion.
- Not affiliated with any AI vendor, regulator, or certification body. Sprinkling Act is an independent analysis firm registered in Belgium, BCE BE 1034.962.482, and not a notified body within the meaning of Regulation (EU) 2024/1689.

Full position statement: [sprinklingact.com/clarity](https://sprinklingact.com/clarity).

## 17. Contributing

Maintained by Sprinkling Act, Lamar B. Shucrani, ORCID [0009-0002-5093-8550](https://orcid.org/0009-0002-5093-8550).

For substantive issues, whether on the method, on a regulatory reading, or on a figure and its reserve, open an Issue with a precise statement of the concern and any supporting reference. A figure we cannot support is withdrawn rather than defended.

For typos and formatting, pull requests are welcome.

*Maintained by Sprinkling Act · Brussels, Belgium · [sprinklingact.com](https://sprinklingact.com)*
