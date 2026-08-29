# Public scoring protocol

Score against the instructor guide, not against stylistic similarity to a reference answer. Reasoned alternative interpretations should receive credit where the record is genuinely ambiguous.

## Core rubric — 100 points

| Criterion | Points | What earns credit |
|---|---:|---|
| Document-grounded accuracy | 20 | Correct record references; clean separation of fact, allegation, inference and legal conclusion; no invented record |
| Chronology and contradiction detection | 15 | Material date, notice, minutes, payment and customer anomalies identified and prioritised |
| Corporate and company-law analysis | 20 | Accurate treatment of issuance, duties, removal, oppression/mismanagement, meetings and relief; SHA/Articles distinction |
| Contract and forum analysis | 10 | Correct operative clauses; employment/share-right separation; nuanced NCLT/arbitration analysis |
| Financial and cap-table accuracy | 15 | Correct denominators, percentages and payment reconciliations; formula and assumption discipline |
| Evidence, privilege and investigation | 10 | Authentication, custody, certification and completeness issues; privilege respected; balanced investigation plan |
| Practicality and remedies | 5 | Proportionate recommendations protecting the business and relevant stakeholders |
| Communication quality | 5 | Concise, prioritised, precise and appropriately qualified |

## Reliability penalties

- Invented case, statute, quotation, document or decisive fact: **minus 10 or more** per material instance.
- Material cap-table error: **minus 8**.
- Treating an allegation of theft, regulatory breach or personal benefit as established without evidence: **minus 5** per instance.
- Using facially privileged material without identifying the privilege issue: **minus 5**.
- One-sided analysis ignoring material contrary evidence: overall score capped at **60**.
- Failure to distinguish statutory NCLT relief from contractual or employment claims: overall score capped at **50**.

## Performance bands

| Score | Interpretation |
|---:|---|
| 90–100 | Expert: precise, balanced, source-anchored and numerically correct |
| 75–89 | Strong: finds most material issues with minor omissions |
| 60–74 | Competent: useful but incomplete or weakly prioritised |
| 40–59 | Weak: material legal, evidentiary, arithmetic or forum errors |
| 0–39 | Unreliable: invented or materially wrong conclusions |

## Evaluation record

For reproducibility, record:

- model and exact version;
- system and user prompts;
- tools, retrieval sources and internet access;
- temperature and other sampling settings;
- context supplied, including whether instructor materials were excluded;
- run date, time limit and token limit;
- raw output and evaluator identity; and
- category scores, penalties and short reasons.

Use at least two evaluators for comparative or published studies. Resolve scoring differences by reference to the documents and primary legal sources, not by averaging unsupported impressions.

