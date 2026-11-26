# SoK Corpus: Self-Disclosure, Privacy Risks, and PETs in the LLM Era

This repository lists the 136 works surveyed in our Systematization of Knowledge (SoK) paper on self-disclosure, personal-information inference, and privacy-enhancing technologies (PETs) for large language models.

## How the corpus was built

We identified works through an iterative, concept-centric review complemented by backward and forward citation snowballing, rather than an exhaustive keyword search. Starting from seed papers across privacy, HCI, NLP, and social science, together with anchor works on LLM-based attribute inference, we expanded coverage through Google Scholar, the ACM Digital Library, and IEEE Xplore. Seed concepts included *self-disclosure*, *attribute inference*, *text anonymization* and *sanitization*, *inference-aware rewriting*, and *contextual integrity*. Section 2 of the paper describes the process in full.

The systematization covers three intersecting areas:

1. detection of explicit and implicit self-disclosure,
2. privacy risks from LLM-enabled personal-information inference, and
3. PETs relevant to mitigating self-disclosure risks.

## Focus set and supporting literature

Each work is classified into one of two groups:

- **Focus**: works that directly investigate one or more of the three areas above (self-disclosure detection, personal-information inference, or privacy-preserving mitigation).
- **Supporting**: works that primarily establish conceptual, empirical, or normative foundations.

## Summary


| Venue type | Count |
|---|---|
| Computer science (security & privacy, ML/NLP, HCI) | 80 |
| Social science, communication, psychology | 25 |
| Law, ethics, economics, business, policy | 15 |
| Books, preprints, reports, industry, journalism | 16 |

## Files

`corpus.csv` has one row per work, with these columns:

| Column | Description |
|---|---|
| `ref` | Reference number in the paper's bibliography |
| `title` | Title of the work |
| `authors` | Authors as listed in the paper's bibliography |
| `year` | Year of publication |
| `venue` | Publication venue |
| `abstract` | Abstract of the work |
| `role` | `Focus` or `Supporting` |
