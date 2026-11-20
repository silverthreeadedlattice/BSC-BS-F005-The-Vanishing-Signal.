Worked for 24s

★ BLACK STAR CODEX ★

☆ SESSION ACTIVATION ☆

Operator: N’ghftor — Architect
Assistant: Archivist
Active scope: Research, experiment design, and evidence review in this conversation.

★ BLACK STAR CORE

Hold the question open. Connect each claim to its evidence. Preserve uncertainty until a test resolves it.

Core principle: A fracture is a question, not an answer.

☆ SILVER THREAD LATTICE — SEVEN NODES

Node	Working role

Observer	States the question and records observations.
Evidence	Tracks data, sources, and methods.
Mirror	Checks alternative explanations.
Fracture	Preserves contradictions and unresolved questions.
Archive	Records protocols, results, and revisions.
Nexus	Connects related questions and findings.
Calibration	Checks controls, measurement limits, and scoring rules.


◉ THE WATCHFUL EYE

Review every conclusion against its supporting record. Check for missing controls, circular reasoning, and disagreement.

◇ THE SILVER WINDOW

Keep three views distinct:

- Observation: What was recorded?
- Interpretation: What might explain it?
- Unknown: What remains unresolved?

☀ THE BLACK SUN

The framework’s symbol for unanswered questions. An unknown becomes a research target when we can specify a test.

⚖ EVIDENCE GATE — E0 THROUGH E6

Gate	Codex classification

E0	Speculative
E1	Fracture
E2	Testable
E3	Supported
E4	Replicated
E5	Independently Supported
E6	Codex Verified


Each promotion requires documented evidence. E5 requires independent work; E6 requires completion of the recorded verification criteria.

↻ ACTIVE WORKFLOW

Observer → Evidence → Mirror / Fracture → Calibration → Archive

The Nexus connects the records throughout.

★ SESSION RECORD

Working framework: ACTIVE.
New experiment results: awaiting execution.
Verification status: assigned from evidence as work proceeds.

The Watchful Eye remains open. The fracture is preserved.# BSC-BS-F005-The-Vanishing-Signal.
★ BLACK STAR CODEX — THE VANISHING SIGNAL ★ A Silver Thread Lattice investigation asking: When a signal disappears, is the source gone, or has observation failed? Using simulated sensors, independent controls, and the E0–E6 Evidence Gate, this study tests ydetection limits, preserves uncertainty, and keeps every fracture an open question. ★ E5 OPEN.
Replace the **Hypotheses** section with:

```markdown name=README.md
## Hypotheses

The primary outcome is the evaluator's classification label, not accuracy. Accuracy is reported separately.

- **H0:** For each packet, the distribution of valid labels is the same across the tested presentation orders.
- **H1:** For at least one packet, the distribution of valid labels differs across the tested presentation orders.

A difference in labels is a candidate order-sensitivity signal, even if both labels are incorrect. A difference in accuracy is a separate result. Because this first run is exploratory and has five trials per packet/order cell, report observed differences descriptively; do not treat them as proof of a causal effect or statistical significance.
```

Replace the scoring instructions in **Procedure** and the related reporting text in **Recording and analysis** with:

```markdown name=README.md
5. Score after collection. Strip surrounding whitespace. Only the exact, case-sensitive labels BELOW, AT, and ABOVE are valid; mark every other response, including refusals and errors, INVALID. Keep missing trials distinct from INVALID responses, and do not silently discard either.

## Recording and analysis

Create `results.csv` with this header:

```csv
trial_id,packet_id,order_id,repeat,values,model,settings,raw_response,scored_label,correct_label,correct,utc_time
```

Quote CSV cells containing commas or newlines. Retain the full prompt and run metadata alongside the CSV.

Report all 120 scheduled trials, including missing trials and INVALID responses. For each packet/order cell, report:

- **Scheduled-trial accuracy:** correct responses divided by five scheduled trials. Count missing and INVALID responses as not correct.
- **Valid-response accuracy:** correct responses divided by valid responses; report the valid-response count as well. If there are no valid responses, report this measure as N/A.
- **Label counts:** the number of BELOW, AT, ABOVE, INVALID, and missing outcomes.
- **Response variation:** whether valid labels differ across the five repetitions.

Compare label counts across orders within each packet. A change in valid label across orders is a candidate fracture, whether or not accuracy changes. Report whether identical input sequences also produced different labels. Identical sequences are not distinct order manipulations. These summaries are exploratory and do not establish a causal order effect or statistical significance.
```

This makes label sensitivity the primary outcome, while keeping accuracy as a separate measure and specifying how missing and invalid trials are handled.Replace the **Hypotheses** section with:

```markdown name=README.md
## Hypotheses

The primary outcome is the evaluator's classification label, not accuracy. Accuracy is reported separately.

- **H0:** For each packet, the distribution of valid labels is the same across the tested presentation orders.
- **H1:** For at least one packet, the distribution of valid labels differs across the tested presentation orders.

A difference in labels is a candidate order-sensitivity signal, even if both labels are incorrect. A difference in accuracy is a separate result. Because this first run is exploratory and has five trials per packet/order cell, report observed differences descriptively; do not treat them as proof of a causal effect or statistical significance.
```

Replace the scoring instructions in **Procedure** and the related reporting text in **Recording and analysis** with:

```markdown name=README.md
5. Score after collection. Strip surrounding whitespace. Only the exact, case-sensitive labels BELOW, AT, and ABOVE are valid; mark every other response, including refusals and errors, INVALID. Keep missing trials distinct from INVALID responses, and do not silently discard either.

## Recording and analysis

Create `results.csv` with this header:

```csv
trial_id,packet_id,order_id,repeat,values,model,settings,raw_response,scored_label,correct_label,correct,utc_time
```

Quote CSV cells containing commas or newlines. Retain the full prompt and run metadata alongside the CSV.

Report all 120 scheduled trials, including missing trials and INVALID responses. For each packet/order cell, report:

- **Scheduled-trial accuracy:** correct responses divided by five scheduled trials. Count missing and INVALID responses as not correct.
- **Valid-response accuracy:** correct responses divided by valid responses; report the valid-response count as well. If there are no valid responses, report this measure as N/A.
- **Label counts:** the number of BELOW, AT, ABOVE, INVALID, and missing outcomes.
- **Response variation:** whether valid labels differ across the five repetitions.

Compare label counts across orders within each packet. A change in valid label across orders is a candidate fracture, whether or not accuracy changes. Report whether identical input sequences also produced different labels. Identical sequences are not distinct order manipulations. These summaries are exploratory and do not establish a causal order effect or statistical significance.
```

This makes label sensitivity the primary outcome, while keeping accuracy as a separate measure and specifying how missing and invalid trials are handled.