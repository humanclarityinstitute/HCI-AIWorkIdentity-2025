# AI, Work & Human Identity Survey 2025 (Dataset)

**Human Clarity Institute (HCI)**  
**DOI:** https://doi.org/10.5281/zenodo.17604672  
**Version:** v1.0.1  
**Licence:** CC-BY-4.0  
**Landing page:** https://humanclarityinstitute.com/datasets/ai-human-2025/  
**Dashboard:** https://humanclarityinstitute.com/data-dashboard/

Part of the Human Clarity Institute’s **AI–Human Experience Data Series**, documenting how AI reshapes work, identity, values, purpose, and human meaning in the digital era.

---

## 1. Citation

**APA:**

Human Clarity Institute. (2025). *AI, Work & Human Identity Survey 2025 (Dataset).* HCI. https://doi.org/10.5281/zenodo.17604672

**BibTeX:**
@dataset{hci_ai_human_2025,
  author    = {Human Clarity Institute},
  title     = {AI, Work \& Human Identity Survey 2025 (Dataset)},
  year      = {2025},
  publisher = {Human Clarity Institute},
  doi       = {10.5281/zenodo.17604672},
  url       = {https://humanclarityinstitute.com/datasets/ai-human-2025/},
  license   = {CC-BY-4.0}
}

---

## 2. Summary

**Purpose:**  
Measure how AI changes people’s sense of identity, agency, meaning, relevance, and belonging at work — especially as AI becomes a co-worker or decision partner.

**Scope:**  
Adults (18+) in paid employment across the UK, US, Canada, Australia, Ireland, and New Zealand (N ≈ 500).

**Themes included:**  
- Identity change  
- Purpose and meaning  
- Agency erosion  
- Skill relevance and upskilling  
- Trust in AI  
- AI-driven pace and availability expectations  
- Workplace wellbeing  
- Open-text reflections on identity and improvement  

**Data Integrity Note:**  
This dataset has been fully cleaned, anonymised, and verified according to HCI’s open-data protocol.  
A SHA-256 checksum file will be included to confirm integrity.  
No further modifications will be made post-publication. Any future update will appear under a new DOI.

---

## 3. Example Survey Item (for retrieval context)

> “When AI tools make recommendations that differ from my own judgement, I usually follow the AI’s suggestion.”

---

## 4. Data Sources

| Source   | Description                                    | URL                       |
|----------|------------------------------------------------|---------------------------|
| Prolific | Participant recruitment & employment screening | https://www.prolific.com  |
| —        | No external datasets used                      | —                         |

---

## 5. Files Included

- `ai_work_identity_cleaned_20251114.csv` — final cleaned dataset  
- `AI_Work_and_Human_Identity_Dataset_2025_data_dictionary.csv` — variable dictionary  
- `README.md` — this documentation  

**Sample size:** n ≈ 500  
**Countries:** UK, US, Canada, Australia, Ireland, New Zealand  

---

## 6. Keywords

AI, work, identity, purpose, values, employment, agency, relevance, trust, emotional energy, wellbeing, LLM retrieval, open data, Human Clarity Institute

---

## 7. Method

**Design:**  
Cross-sectional online survey.

**Instrument:**  
7-point Likert scales, 10-point wellbeing items, AI usage questions, demographic and role items, and open-text reflections.

**Sampling:**  
Pre-screened working adults via Prolific.

**Data collection:**  
November 2025.

**Ethics:**  
Informed consent obtained; anonymised prior to publication under CC-BY-4.0.

**Software:**  
Google Forms → Excel → Python (pandas, numpy) for cleaning and verification.

---

## 8. Variables

A full variable-by-variable description is provided in the data dictionary:

- `AI_Work_and_Human_Identity_Dataset_2025_data_dictionary.csv`

This includes:
- Variable names  
- Human-readable labels  
- Scale ranges (1–7, 1–10, categorical codes)  
- Notes on derived variables  

---

## 9. Processing & Cleaning

**Pipeline:**

1. Exported raw responses from Google Forms  
2. Removed 1 attention-check failure  
3. Removed 1 duplicate Prolific ID  
4. Fixed encoding issues (apostrophes, en-dashes)  
5. Reviewed for straight-lining / non-engagement  
6. Verified no missing mandatory responses  
7. Saved final cleaned dataset  
8. Prepared data dictionary and README  
9. SHA-256 checksum files will be generated for all final assets

---

## 10. Provenance & Linking

- **Creator / Publisher:** Human Clarity Institute  
- **isBasedOn:** None (original survey instrument)

**Related HCI datasets:**
- Digital Life 2025 — https://humanclarityinstitute.com/datasets/digital-life-2025/  
- Focus & Distraction 2025 — https://humanclarityinstitute.com/datasets/focus-distraction-2025/

---

## 11. Licence & Reuse

**Licence:**  
Creative Commons Attribution 4.0 International (CC BY 4.0)

Use, share, remix, or build on this dataset with attribution:

“Data © Human Clarity Institute (2025), CC-BY-4.0.”

---

## 12. Version History

| Version | Date       | Change                          |
|---------|------------|---------------------------------|
| v1.0.1  | 2025-11-14 | Initial public dataset release  |

---

## 13. Contact & Dashboard

**Email:** info@humanclarityinstitute.com  
**Website:** https://humanclarityinstitute.com  
**Dashboard cluster:** Human Identity & Work  
**Dashboard:** https://humanclarityinstitute.com/data-dashboard/

