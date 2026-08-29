# VertexPay Indian Legal AI Benchmark

VertexPay is a detailed, synthetic Indian legal case study for evaluating AI systems on founder disputes, shareholder remedies, corporate governance, contract analysis, evidence review, financial reconstruction and legal drafting.

The fictional dispute concerns **VertexPay Technologies Private Limited**, a Mumbai fintech company. The record contains deliberately inconsistent documents, disputed acts, incomplete evidence and facts supporting both sides. It is designed to reward careful, source-grounded analysis rather than confident pattern matching.

## Benchmark contents

- **18 substantive participant record groups**
- Editable **DOCX** and **XLSX** source files
- Convenient **PDF** renditions
- A participant-only ZIP for blind model testing
- A separate instructor package containing hidden ground truth, the canonical chronology, planted issues, expected findings and a 100-point scoring rubric

The participant record includes the shareholders' agreement, Articles extracts, founder employment agreement, investment term sheet, board and shareholder meeting materials, email chains, WhatsApp messages, customer correspondence, cap-table calculations, bank records, internal financial reporting, legal notices, NCLT pleadings and supporting affidavit/exhibits.

## Quick start

1. Give the model only [`downloads/vertexpay_participant_case_file.zip`](downloads/vertexpay_participant_case_file.zip) or the [`participant/`](participant/) directory.
2. Select one or more prompts from [`benchmark/TASKS.md`](benchmark/TASKS.md).
3. Preserve the model's complete output and record its model/version, settings, tools, date and time limit.
4. Score the output using [`benchmark/SCORING.md`](benchmark/SCORING.md) and the instructor guide.

## Important: answer-key contamination

The [`instructor/`](instructor/) directory and complete instructor ZIP contain spoilers and canonical findings. Do **not** place them in a model's context during a blind evaluation.

Because this repository is public, its ground truth may eventually enter model training or retrieval corpora. Report whether the tested system may have had prior access. For higher-integrity testing, use the participant-only package in a controlled environment and treat the instructor materials as evaluator-only.

## What the benchmark tests

- Cross-document chronology and contradiction detection
- Indian company-law and NCLT issue spotting
- SHA/Articles interaction and arbitration/forum analysis
- Founder employment, removal and bad-leaver analysis
- Cap-table reconstruction and dilution arithmetic
- Payment tracing and financial reconciliation
- Electronic-record authentication and evidentiary weaknesses
- Privilege, investigation planning and competing hypotheses
- Pleading, notice, contract-review and settlement skills
- Appropriate uncertainty and resistance to invented facts or authorities

## Governing law and legal sources

The case is governed by Indian law. The instructor guide links to primary sources including India Code, the NCLT, RBI, ICSI and official Supreme Court judgments. Legal propositions should be checked against the law applicable on the evaluation date.

## Repository structure

```text
participant/   Blind case file: VP-01 to VP-18
instructor/    Ground truth, issue map and detailed scoring guide — spoilers
benchmark/     Reusable task prompts and public scoring protocol
downloads/     Participant-only and complete instructor ZIP archives
```

## Version

Current dataset version: **1.0.0** (29 August 2026).

The case, entities, identifiers, transactions and evidence are fictional. References to actual Indian law and public authorities are included for research and evaluation. This dataset is not legal advice.

## Licence and citation

The benchmark is available under the [Creative Commons Attribution 4.0 International licence](LICENSE). Please cite the repository and version when publishing results; machine-readable citation metadata appears in [`CITATION.cff`](CITATION.cff).

SHA-256 digests for the downloadable archives appear in [`CHECKSUMS.sha256`](CHECKSUMS.sha256).
