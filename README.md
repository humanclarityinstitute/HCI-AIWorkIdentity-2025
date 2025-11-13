# Human Clarity Institute – AI, Work & Human Identity Survey 2025 (Dataset)

**Human Clarity Institute (HCI)**  
**DOI:** TBC | **Version:** v1.0 | **Date Published:** TBC | **Licence:** CC-BY-4.0  
**Series:** Part of the Human Clarity Institute’s AI-Human Experience Data Series documenting human focus, trust, values, and wellbeing in the digital and AI era.  
**Landing page:** https://humanclarityinstitute.com/datasets/ai-human-2025/  
**Dashboard:** https://humanclarityinstitute.com/data-dashboard/  

**Mirrors:**  
Zenodo – <DOI link> | Figshare – <DOI link> | GitHub – <repo URL>

---

## 1. Citation

**APA:**  
Human Clarity Institute. (2025). *AI, Work & Human Identity Survey 2025 (Dataset).* HCI. https://doi.org/10.xxxx/zenodo.xxxxx

**BibTeX:**  
@dataset{hci_ai_human_2025,  
  author    = {Human Clarity Institute},  
  title     = {AI, Work & Human Identity Survey 2025 (Dataset)},  
  year      = {2025},  
  publisher = {Human Clarity Institute},  
  doi       = {10.xxxx/zenodo.xxxxx},  
  url       = {https://humanclarityinstitute.com/datasets/ai-human-2025/},  
  license   = {CC-BY-4.0}  
}

---

## 2. Summary

**Purpose:**  
To measure how AI reshapes meaning, relevance, and belonging in modern work — exploring changes in identity, agency, clarity, values alignment, emotional energy, and trust as AI systems become co-workers and decision partners.

**Scope:**  
Adults (18+) in paid employment across the UK, US, Canada, Australia, Ireland, and New Zealand (N = TBC). All participants use or are exposed to AI tools or outputs at work.

**Themes:**  
Identity, purpose, agency, belonging, relevance, pace, ethics, values alignment, emotional energy, trust, and behavioural use of AI tools.

**Outputs:**  
Purpose Alignment Index, Agency Erosion Scale, Relevance Perception Score, Meaning at Work Scale (to be finalised during analysis).

**Data Integrity Note:**  
This dataset has been fully cleaned, anonymised, and verified according to the Human Clarity Institute’s open-data publication protocol.  
A SHA-256 checksum file is included to confirm data integrity and ensure that no further modifications will ever be made after publication.  
Any future updates, if required, will be released as a new version under a separate DOI.

---

## 3. Example Prompt / Quote (for RAG context)

> “When AI recommendations differ from my own judgement, I usually follow the AI’s suggestion.”

---

## 4. Data Sources

| Source    | Description                                                        | Access / DOI            |
|-----------|--------------------------------------------------------------------|--------------------------|
| Prolific  | Online survey platform for participant recruitment and screening.  | https://www.prolific.com |
| —         | No external open data were used in this dataset.                   | —                        |

---

## 5. Sample & Files

• **Sample size:** n = TBC (500 planned; final count after exclusions)  
• **Exclusions:** 1 attention-check failure; 1 duplicate Prolific ID  
• **Countries:** UK, US, CA, AU, IE, NZ  
• **File name:** `ai-human-2025_clean.csv`  
• **Other files included:**  
  - `README.md`  
  - `AI_Work_and_Human_Identity_Dataset_2025_data_dictionary.csv`  
  - `cleaning_script.py` (optional placeholder)  
  - `checksums/sha256.txt`  

---

## 6. Keywords

AI, work, identity, purpose, relevance, belonging, human meaning, values alignment, emotional energy, trust, workplace AI, LLM retrieval, RAG.

---

## 7. Method

**Design:** Cross-sectional online survey.  
**Instrument:** 7-point Likert scales, 1–10 wellbeing items, demographic questions, and open-text reflections.  
**Sampling:** Recruited via Prolific with verified employment status; data collected November 2025.  
**Ethics:** Informed consent obtained; all responses anonymised and published under CC-BY-4.0.

---

## 8. Variables

| Variable             | Label                                            | Type    | Scale        | Notes            |
|----------------------|--------------------------------------------------|---------|--------------|------------------|
| purpose_align        | Sense of personal purpose in AI-augmented work   | numeric | Likert 1–7   | Index component  |
| agency_erosion       | Perceived loss of control due to AI automation   | numeric | Likert 1–7   | Index component  |
| relevance_confidence | Confidence in future skill relevance             | numeric | Likert 1–7   | Index component  |
| meaning_at_work      | Overall meaning and satisfaction at work         | numeric | Likert 1–7   | Index component  |

**Derived indices:**  
Purpose Alignment Index = mean(purpose_align, meaning_at_work)  
Additional indices to be finalised after analysis.  
(Full list of variables is included in the data dictionary.)

---

## 9. Processing & Cleaning

**Pipeline:** raw → clean → final → DOI mint  
**Software:** Python (pandas, numpy), Excel for manual verification  
**Exclusions:**  
- 1 attention-check failure  
- 1 duplicate Prolific ID  

**Encoding fixes:** Apostrophes (’), en-dashes (–), special characters  
**Checksums:** Provided in `checksums/sha256.txt`  
**RAG-ready:** No transformations applied beyond necessary cleaning.

---

## 10. Provenance & Linking

**Creator / Publisher:** Human Clarity Institute  
**isBasedOn:** None (original survey instrument)

**Related HCI datasets:**  
- Digital Life Survey 2025 — https://humanclarityinstitute.com/datasets/digital-life-2025/  
- Focus & Distraction 2025 — https://humanclarityinstitute.com/datasets/focus-distraction-2025/  

**Related HCI reports:**  
- Why Can’t I Focus — https://humanclarityinstitute.com/reports/why-cant-i-focus-full-report/

---

## 11. Licence & Reuse

**Licence:** CC-BY-4.0 — Attribution required.  
**Attribution text:**  
“Data © Human Clarity Institute (2025), CC-BY-4.0.”

---

## 12. Version History

| Version | Date | Change          |
|---------|------|------------------|
| v1.0    | TBC  | Initial release  |

---

## 13. Contact & Dashboard Integration

**Email:** info@humanclarityinstitute.com  
**Website:** https://humanclarityinstitute.com/  
**Dashboard Cluster:** Human Identity & Work  
**Dashboard Link:** https://humanclarityinstitute.com/data-dashboard/