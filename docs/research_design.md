# Research Design: Aim, Objectives, Research Questions and Gaps

This file is the single source for the project's aim, objectives (Obj), research questions (RQ) and research gaps (G). Every requirement, notebook cell and dashboard page refers back to these IDs.

## Aim

To examine the relationship between annual wastewater network-plus base expenditure and selected operational outcomes among England's nine water and sewerage companies over 2017/18–2024/25, and to communicate the evidence through a transparent, reproducible analytical dashboard.

## Research questions

| ID | Research question |
|---|---|
| RQ1 | How do base expenditure and the selected outcomes vary across the nine companies between 2017/18 and 2024/25? |
| RQ2 | What associations exist between expenditure and each modelled outcome after recognising company scale, persistent company differences and shared annual conditions? |
| RQ3 | How sensitive are these associations to how base expenditure is scaled, influential companies and the timing assigned to expenditure and performance? |
| RQ4 | How effectively can a reproducible Power BI artefact communicate these relationships and their limitations to an informed non-specialist? |

## Objectives

| ID | Objective | Serves |
|---|---|---|
| Obj1 | Build a documented company-year dataset that links base expenditure, company scale and the selected outcomes, preserving source definitions and reporting periods. | RQ1–RQ4 |
| Obj2 | Compare expenditure and outcome trajectories across companies and years on consistent financial and measurement bases. | RQ1 |
| Obj3 | Assess expenditure–outcome associations, distinguishing persistent company differences from within-company change and shared annual conditions. | RQ2 |
| Obj4 | Test how sensitive the interpretation is to expenditure scaling, influential companies and timing assumptions. | RQ3 |
| Obj5 | Develop a Power BI artefact that presents comparisons, relationships, definitions and data-quality information accessibly. | RQ4 |
| Obj6 | Evaluate the artefact's reproducibility, numerical consistency and usability against documented requirements. | RQ4 |

## Research gaps

| ID | Gap | Addressed by |
|---|---|---|
| G1 Scope | No reviewed study was found that examines, outcome by outcome, how wastewater network-plus base expenditure relates to sewer flooding, collapses and pollution for England's nine water and sewerage companies over 2017/18–2024/25. | RQ1, RQ2 |
| G2 Robustness | The reviewed sector studies rarely account for having few companies when estimating uncertainty, seldom test sensitivity to expenditure scaling, timing and influential companies, and do not usually state the smallest association their data could detect. | RQ2, RQ3 |
| G3 Communication | The regulatory publications reviewed (Ofwat, 2025a; 2025b) present spending beside performance, but they do not estimate the association between them or show its uncertainty. | RQ4 |

## Traceability summary

| Gap | Research question | Objective(s) |
|---|---|---|
| G1 | RQ1 | Obj1, Obj2 |
| G1, G2 | RQ2 | Obj1, Obj3 |
| G2 | RQ3 | Obj1, Obj4 |
| G3 | RQ4 | Obj5, Obj6 |

## Key scope decision

**Base expenditure only.** Base expenditure (the cost of running and maintaining existing sewers) is used throughout; total expenditure is not used anywhere. Reasons: one consistent Ofwat definition covers every year of the 2017/18–2024/25 window; it matches what the outcomes mainly depend on (maintenance of existing networks); and it avoids the lumpiness of enhancement projects. Limitation: the project cannot say whether enhancement investment (for example storm-overflow schemes) affects outcomes.

## References

Ofwat (2025a) *Water company performance report 2024–25* [online]. Available from: https://www.ofwat.gov.uk/publication/water-company-performance-report-2024-25/ [Accessed 26 October 2026].

Ofwat (2025b) *Data for the Water Company Performance Report 2024–25: open data-friendly machine-readable format* [online]. Available from: https://www.ofwat.gov.uk/publication/data-for-the-water-company-performance-report-2024-25-open-data-friendly-machine-readable-format/ [Accessed 26 October 2026].
