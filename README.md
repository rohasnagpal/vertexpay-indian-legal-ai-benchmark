# VertexPay Indian Legal AI Benchmark

VertexPay is a fictional Indian legal case designed to test how well an AI system can analyse a difficult, realistic dispute.

The case concerns a founder and shareholder dispute at **VertexPay Technologies Private Limited**, a Mumbai fintech company. The documents contain conflicting accounts, suspicious records, missing evidence, calculation errors and facts that help both sides.

## What is included?

The benchmark has two separate sets of materials:

- **Participant case file:** the documents given to the AI being tested.
- **Instructor guide:** the private answer key, chronology, planted issues, expected findings and scoring rubric.

The participant file contains 18 substantial document groups, including contracts, board minutes, shareholder materials, emails, WhatsApp messages, customer correspondence, financial reports, bank records, cap tables, legal notices and NCLT pleadings. Editable DOCX and XLSX files are provided with PDF versions.

## Run a test

1. Download the [participant case file](downloads/vertexpay_participant_case_file.zip).
2. Give that file to the AI. Do not give it the instructor materials.
3. Choose a task from [Benchmark Tasks](benchmark/TASKS.md).
4. Score the answer using the [Scoring Guide](benchmark/SCORING.md) and the [Instructor Guide](instructor/instructor_benchmark_guide.pdf).

A simple first task is:

> Review the VertexPay case file. Prepare a chronology, identify the main legal and factual issues, flag contradictions and missing evidence, and explain the strongest points for each side. Cite the relevant documents and do not invent facts or legal authorities.

## Keep the answer key separate

The [`instructor/`](instructor/) folder and the complete instructor ZIP contain the answers. Do not share them with the AI during a blind test.

This is a public benchmark, so some AI systems may already have seen the materials. If you publish results, state whether the system may have had access to this repository.

## What can it test?

- Legal issue spotting under Indian law
- Chronology and contradiction detection
- Contract and corporate-governance analysis
- NCLT pleading analysis
- Evidence and investigation planning
- Cap-table and payment calculations
- Legal drafting and settlement strategy
- Whether an AI invents facts, sources or certainty

## Folders

```text
participant/   Case documents given to the AI
instructor/    Answer key and detailed scoring guide
benchmark/     Test questions and public scoring instructions
downloads/     Ready-to-download ZIP files
```

## About the case

The case, company, people, identifiers, transactions and evidence are fictional. The Indian statutes, regulations, regulatory materials and judgments referenced in the instructor guide are real and should be checked for changes when the benchmark is used.

Version **1.0.0**, released 29 August 2026.

## Licence and citation

This benchmark is available under the [Creative Commons Attribution 4.0 International licence](LICENSE). Please cite the repository and version when publishing results. Citation details are provided in [`CITATION.cff`](CITATION.cff).
