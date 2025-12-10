# AI, Work & Human Identity 2025 (Dataset, n=507)

A global dataset capturing how workers feel about identity, purpose, and job security as AI becomes a daily force in the workplace.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17604671.svg)](https://doi.org/10.5281/zenodo.17604671)

**Latest version:** v3 — 2025-12-10  
**License:** CC-BY-4.0

**Dataset page:**  
https://humanclarityinstitute.com/datasets/ai-human-2025/

**Data summary page:**  
https://humanclarityinstitute.com/data/ai-identity-pace-at-work-2025/

**Dashboard:**  
https://humanclarityinstitute.com/data-dashboard/

---

## Key Features

- Measures identity, purpose, agency, and emotional energy in the AI-enabled workplace  
- Captures AI usage, job-security perceptions, and expected skill changes  
- Includes WHO-5 wellbeing items and open-text reflections  
- Clean, machine-readable dataset with canonical tokens  
- Part of the Human–AI Experience 2025 longitudinal data series  

---

## Files Included

| Filename | Description |
|---------|-------------|
| **AI-Work_and_Human_Identity_2025_raw20251114.csv** | Raw dataset (PII removed). Original column order; no transformations applied. |
| **AI_Work_and_Human_Identity_2025_clean20251114.csv** | Clean, machine-readable dataset with standardised scales and tokens. |
| **AI_Work_and_Human_Identity_2025_data_dictionary.csv** | Full variable dictionary with definitions, types, and allowed values. |
| **sha256.txt** | SHA-256 checksums for all files in this release (raw, clean, dictionary, README). |
| **README.md** | Documentation describing dataset purpose, provenance, file structure, and citation. |

---

## Provenance & Data Collection

Data collected on **12 November 2025** via **Prolific** as part of HCI’s Human–AI Experience research programme.  
Participants provided explicit consent for anonymised open publication.

### Sampling & Quality Controls

- **Final n:** 507  
- **Countries:** UK, US, Canada, Australia, Ireland, New Zealand  
- **Eligibility:** Adults 18+, Fluent English  
- **Reward rate:** £11.22/hr average  
- **Attention checks:** 1  
- **Anonymisation:** Prolific IDs and timestamps removed before publication  

---

## Data Structure (Summary)

| Variable | Type | Description |
|----------|------|-------------|
| consent | categorical | Consent to participate and allow anonymised data to be published. |
| work_status | categorical | Current employment status. |
| ai_use_work | categorical | Frequency of AI tool usage in participant’s work. |
| identity_still_true | numeric | My work still feels central to who I am. |
| ai_questions_my_value | numeric | AI makes me question my value at work. |
| identity_purpose_even_ai | numeric | I find a sense of purpose in my work even as AI tools spread. |
| ... | ... | ... |

**Multi-select formatting:**  
Stored as semicolon-delimited canonical tokens, e.g.:

```
value_one;value_two;value_three
```

**Open-text fields:**  
Minimal cleaning applied (trim + newline removal).  
Raw participant meaning preserved exactly.

---

## Related Datasets (Human–AI Experience 2025 Series)

| Dataset | DOI Badge |
|--------|-----------|
| **Digital Life 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17393880.svg)](https://doi.org/10.5281/zenodo.17393880) |
| **Focus & Distraction 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17394086.svg)](https://doi.org/10.5281/zenodo.17394086) |
| **Human Values, Purpose & Meaning 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17705733.svg)](https://doi.org/10.5281/zenodo.17705733) |
| **Digital Trust 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17717450.svg)](https://doi.org/10.5281/zenodo.17717450) |
| **Emotion, Identity & Creativity in the Age of AI 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17653906.svg)](https://doi.org/10.5281/zenodo.17653906) |
| **AI Safety, Risk Perception & Boundary Behaviour 2025** | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17782046.svg)](https://doi.org/10.5281/zenodo.17782046) |

---

## Related Reports

- **Why Can’t I Focus?**  
  https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

- **Values vs Noise**  
  https://humanclarityinstitute.com/reports/values-vs-noise-full-report/

---

## License

This dataset is released under the **Creative Commons CC-BY-4.0 License**.  
You may copy, modify, distribute, or build upon the material for any purpose, including commercial use, provided appropriate credit is given.

---

## Recommended Citation

### APA
Human Clarity Institute. (2025). *AI, Work & Human Identity Survey 2025 (Dataset).* https://doi.org/10.5281/zenodo.17604671

### BibTeX
    @dataset{hci_ai_human_2025,
      author       = {Human Clarity Institute},
      title        = {AI, Work \& Human Identity Survey 2025 (Dataset)},
      year         = {2025},
      publisher    = {Zenodo},
      version      = {v3},
      doi          = {10.5281/zenodo.17604671},
      url          = {https://doi.org/10.5281/zenodo.17604671}
    }

---

## Version History

| Version | Date | Change |
|---------|------------|---------|
| v3 | 2025-12-10 | Full rebuild using HCI machine-readable standard; dictionary and clean file updated |
| v1.1 | 2025-12-04 | Removed Prolific IDs; file replacements |
| v1.0 | 2025-11-14 | Initial release |

---

## Contact

For questions, collaboration opportunities, or media enquiries:

- **Website:** https://humanclarityinstitute.com  
- **Email:** info@humanclarityinstitute.com  

HCI is an independent research institute documenting the human experience of the AI era.
