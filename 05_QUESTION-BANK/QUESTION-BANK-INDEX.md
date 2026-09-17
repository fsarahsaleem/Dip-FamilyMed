# DFM Question Bank — Initial Corpus Index

**Status:** Initial ingestion complete
**Corpus:** 10 uploaded DFM selection/screening PDFs
**Target exam:** July 2027

## Corpus

| ID | Source | Questions/items | Notes |
|---|---|---:|---|
| 1996 | DFM Selection Examination — March 1996 | 39 | No answer key uploaded; answers must be treated as evidence-supported, not examiner-confirmed |
| 1997 | DFM Selection Examination 1997 | 39 | Question paper only |
| 2010 | DFM Selection Examination 2010 | 38 | Question paper only |
| 2011 | DFM Selection Examination 2011 | 40 | Question paper only |
| 2015 | DFM Selection Examination 2015 | 40 | Question paper only |
| 2017 | DFM Screening Exam 2017 | 38 | Question paper only |
| 2019-A | DFM Screening 2019 | 39 | Same content as 2019-B; counted once for frequency analysis |
| 2019-B | Screening Examination DFM 2019 (02.04.2019) | 40 | Duplicate/near-duplicate of 2019-A; retained as a separate source record but not double-counted |
| 2021 | DFM Screening Examination — December 2021 | 37 | Question paper only |
| 2026 | Selection Examination for DFM 2026 — Answers | 40 | Answer-key/explanation source; question wording is partially represented in the PDF |

**Approximate unique question items represented:** 351, excluding the duplicate 2019 paper and treating the 2026 answer document as a separate partial source.

## Processing rules

1. The question papers are evidence of what was examined, not proof that every historical statement is medically correct today.
2. Historical answer keys will be stored separately from current evidence-based answers.
3. A question will only be marked `Examiner-confirmed` when an answer key is actually available for that question/source.
4. Repeated concepts are mapped by concept, not by superficial wording alone.
5. Frequency counts below refer to **unique paper sources** unless otherwise stated.
6. When a historical item conflicts with current guidance, the conflict will be preserved and explicitly labelled during study.

## High-recurrence concepts identified in the initial corpus

| Concept | Papers observed | Frequency signal |
|---|---|---:|
| Pruritus / causes of pruritus | 1996, 1997, 2010, 2011, 2017 | 5 |
| Dengue / dengue haemorrhagic-fever features | 1997, 2015, 2017, 2019 | 4 |
| Obesity and associated disease | 1997, 2019 | 2 |
| Malaria investigation / blood film | 1996, 2010, 2011 | 3 |
| Foreign-body urgent removal | 1996, 2010, 2011 | 3 |
| Hilar lymphadenopathy | 2010, 2011 | 2 |
| Carpal tunnel syndrome | 2010, 2011 | 2 |
| Obsessive-compulsive disorder | 2010, 2011 | 2 |
| Hair biology | 2010, 2011 | 2 |
| Drugs affecting breast milk | 2010, 2011 | 2 |
| Drugs associated with impotence | 2010, 2011 | 2 |
| Alpha blockers in BPH | 2010, 2011 | 2 |
| Varicocele | 2010, 2011 | 2 |
| Leptospirosis | 2010, 2011, 2017 | 3 |
| Drowning | 2010, 2011, 2017 | 3 |
| Psoriasis | 2010, 2011, 2017 | 3 |
| Depo-provera / DMPA | 2010, 2011, 2019 | 3 |
| Headache referral / red flags | 2010, 2011, 2017, 2019 | 4 |
| Pneumothorax | 2010, 2011 | 2 |
| Salivary calculi | 2010, 2011 | 2 |
| Childhood anaemia | 2010, 2011 | 2 |
| Acute tonsillitis / pharyngitis | 1996, 1997, 2010, 2011, 2019, 2021 | 6 |
| Congenital/neonatal hypothyroidism | 1996, 1997, 2010, 2011, 2017 | 5 |
| Constipation / bowel symptoms in children | 1996, 2019, 2021 | 3 |
| Intussusception | 1996, 1997, 2019 | 3 |
| IUCD / contraception | 1996, 1997, 2010, 2011, 2021 | 5 |
| Diabetes in pregnancy | 1996, 1997 | 2 |
| Hydatidiform mole | 1996, 1997, 2017 | 3 |
| Mantoux false-negative / TB | 1996, 2019, 2021 | 3 |
| Osteoporosis risk factors | 1997, 2019 | 2 |
| Diabetes and skin manifestations | 1996, 1997, 2019, 2021 | 4 |
| Acute gastroenteritis in children / ORS | 1996, 2011, 2019 | 3 |
| Pregnancy / obstetric risk factors | 1996, 1997, 2011, 2015, 2017, 2019 | 6 |
| Depression / psychiatry | 2015, 2017, 2021, 2026 | 4 |
| Screening in primary care | 2019, 2021, 2026 | 3 |
| Back pain red flags | 2019, 2021, 2026 | 3 |
| Anaemia / iron deficiency | 1997, 2010, 2011, 2019, 2026 | 5 |

> **Important:** These are an initial concept-frequency map from the uploaded corpus. They are not yet a formal statistical blueprint. Some broad categories combine several related question types, and the 2026 source is an answer document rather than a full question paper.

## Topic families represented

- Family practice principles, records, continuity, coordination and opportunistic care
- Screening and prevention
- Adult medicine and emergency presentations
- Diabetes and complications
- Cardiovascular disease and hypertension
- Respiratory medicine
- Gastroenterology/hepatology
- Neurology/headache
- Psychiatry
- Dermatology
- Paediatrics and neonatology
- Obstetrics and gynaecology
- Sexual/reproductive health and contraception
- ENT and ophthalmology
- Infectious diseases and tropical medicine
- Haematology
- Musculoskeletal/rheumatology
- Urology/men's health
- Geriatrics
- Clinical pharmacology / adverse drug effects

## Next processing layer

1. Build `BY-TOPIC` question sets.
2. Assign each question a primary topic + subtopic.
3. Add question IDs and source references.
4. Add answer status: `Examiner-confirmed`, `Evidence-supported`, or `Unresolved`.
5. Link recurring concepts to high-yield summaries.
6. Use the recurrence map to build the first evidence-based roadmap.
7. Recalculate frequency when additional papers are uploaded.
