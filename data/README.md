# Data

The raw measurement file (`New data.xlsx`) is **not distributed in this repository**.

Per the manuscript's Data Availability statement, the dataset (195 subjects: 100 females,
95 males; Assiut n=104, Benha n=91) is available from the corresponding author on
reasonable request, consistent with the study's ethics approval
(Assiut University Committee on Research Ethics, Approval No. 04-2025-300570).

To reproduce the pipeline locally:

1. Request the dataset from the corresponding author (see main [README](../README.md#contact)).
2. Place it here as `data/New data.xlsx`.
3. Run [`Final_code_v2.ipynb`](../Final_code_v2.ipynb) top to bottom.

### Expected columns

| Column | Description |
|---|---|
| `Subject` | Anonymized subject ID |
| `age (years)` | Age at scan |
| `sex (F=0, M=1)` | Biological sex label |
| `regionn` | Cohort — `Assiut` (Upper Egypt) or `Benha` (Lower Egypt) |
| `Rt./Lt. Max. AP (cm)` | Right/left maxillary sinus anteroposterior diameter |
| `Rt./Lt. Max. TR (cm)` | Right/left maxillary sinus transverse diameter |
| `Rt./Lt. Max. CC (cm)` | Right/left maxillary sinus craniocaudal diameter |
| `Nfa (nasofrontal angle)` | Nasofrontal angle |
| `Pa (pyramidal angle)` | Pyramidal angle |
| `NT nasion tip distance` | Nasion–tip distance |
