# codelists
Repository of all the codelists used in the PhD project "Antidepressant use during pregnancy: what are the outcomes?" undertaken by Flo Martin at the University of Bristol between 2020 and 2024. The project uses electronic health record data from the UK (CPRD GOLD), Norway, and Sweden. 

The results chapters / papers in this thesis relevant to the contained codelists consist of -

- Patterns of antidepressant prescribing in and around pregnancy: a descriptive analysis in the UK Clinical Practice Research Datalink
    - https://github.com/flozoemartin/Patterns
    - https://doi.org/10.1101/2024.08.08.24311553 - pre-print
- Antidepressant use during trimester one and miscarriage: a comprehensive analysis in the UK Clinical Practice Research Datalink
    - https://github.com/flozoemartin/Miscarriage
    - https://doi.org/10.1101/2024.10.19.24315779 - pre-print
- Antidepressant use during pregnancy and birth outcomes: analysis of electronic health data from the UK, Norway, and Sweden
    - https://github.com/flozoemartin/Birth-outcomes
    - https://doi.org/10.1101/2024.10.30.24316340 - pre-print

The repositories for the code used in each of these projects are linked above.

The codelists are organised by exposure (antidepressants), outcomes (pregnancy and birth), and covariates (smoking, alcohol use, illicit drug use, ethnicity etc.). The codelists are a mix of -

- Prescriptions
    - BNF / prodcodes for CPRD GOLD (bnf/*_bnf_codelist)
    - ATC codes for Norway and Sweden (atc/*_atc_codelist)
- Medical information
    - Read / medcodes for CPRD GOLD primary care (read & medcode/*_read_codelist or *_medcode_codelist)
    - ICPC2 codes for Norway primary care (icpc2/*_icpc_codelist)
    - OPCS codes for CPRD GOLD secondary care procedures (opcs/*_opcs_codelist)
    - ICD-10 codes for CPRD GOLD, Norway, and Sweden secondary care (icd10/*_icd10_codelist)
    - ICD-9 codes Sweden secondary care (icd9/*_icd9_codelist)
