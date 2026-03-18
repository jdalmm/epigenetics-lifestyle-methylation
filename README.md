# Epigenetic Effects of Lifestyle on Neuroplasticity Genes

**A systematic computational analysis of lifestyle-associated DNA methylation 
changes at BDNF, NR3C1, and FKBP5 in humans**

*Independent research project · João Duarte · ISA-ULisboa · 2026*

---

## Research Question

Do different research groups agree when measuring methylation at the same 
neuroplasticity genes under the same type of lifestyle intervention? And does 
the tissue type analysed (blood, saliva, brain) moderate the results?

This systematic analysis addresses a gap in the literature: no publicly 
available curated dataset compares directional consistency of epigenetic 
effects across intervention types and tissue sources for these three genes.

---

## Target Genes

| Gene | Full Name | Role |
|------|-----------|------|
| **BDNF** | Brain-Derived Neurotrophic Factor | Neuronal growth, plasticity, learning and memory |
| **NR3C1** | Glucocorticoid Receptor Gene | Cortisol response, HPA axis regulation |
| **FKBP5** | FK506 Binding Protein 5 | Glucocorticoid receptor co-chaperone; stress sensitivity |

---

## Interventions Analysed

- **Chronic stress & trauma** — including early-life adversity and PTSD-related studies
- **Physical exercise** — aerobic training and acute exercise protocols
- **Diet & nutrition** — omega-3, caloric restriction, and dietary pattern studies

---

## Methodology

1. Systematic literature search on PubMed using predefined search terms
2. Study inclusion/exclusion based on PRISMA-inspired protocol
3. Data extraction into a structured CSV dataset (14 variables per study)
4. Computational analysis in Python — directional consistency, tissue effects, 
   methodological quality
5. Target output: peer-reviewed publication + bioRxiv preprint

---

## Repository Structure
```
/data          → curated dataset (CSV) — studies extracted from literature
/notebooks     → Python analysis pipeline (Jupyter Notebooks)
/figures       → publication-quality visualisations
/paper         → manuscript drafts
/references    → key papers and annotation notes
```

---

## Status

| Phase | Description | Status |
|-------|-------------|--------|
| Phase 1 | Scientific foundations & literature review | 🟡 In progress |
| Phase 2 | Systematic data collection | ⬜ Upcoming |
| Phase 3 | Computational analysis | ⬜ Upcoming |
| Phase 4 | Writing & publication | ⬜ Upcoming |

---

## Tools & Skills

- **Python:** pandas, numpy, scipy, matplotlib, seaborn
- **Databases:** PubMed, NCBI, EMBL-EBI
- **Training:** EMBL-EBI Functional Genomics I, II & III (completed March 2026)
- **Reference management:** Zotero

---

## Contact

João Duarte · Biology Student · ISA-ULisboa  
duartejoao381@gmail.com
https://www.linkedin.com/in/jo%C3%A3o-duarte-3b0ab3194/
3. Cola isto:
```
study_id,gene,cpg_region,intervention_type,intervention_detail,tissue,cell_type,sample_size_n,direction,effect_size,p_value,method,quality_notes,doi
