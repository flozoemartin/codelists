# codelists
Repository of all the codelists used in the PhD project "Antidepressant use during pregnancy: what are the outcomes?" undertaken by Flo Martin at the University of Bristol between 2020 and 2024. The project uses electronic health record data from the UK (CPRD GOLD), Norway, and Sweden. 

The results chapters / papers in this thesis relevant to the contained codelists consist of -

- [Patterns of antidepressant prescribing in and around pregnancy: a descriptive analysis in the UK Clinical Practice Research Datalink](https://github.com/flozoemartin/Patterns)
    - [PRE-PRINT](https://doi.org/10.1101/2024.08.08.24311553) submitted to BJOG on August 13th 2024
- Antidepressant use during trimester one and miscarriage: a triangulation of methods in the UK Clinical Practice Research Datalink
    - In prep for submission to BMJ
- Antidepressant use during pregnancy and birth outcomes: analysis of electronic health data from the UK, Norway, and Sweden
    - In prep for submission to BMJ
- Antidepressant use during pregnancy and preterm delivery: a target trial emulation in the UK Clinical Practice Research Datalink
    - In prep for submission to IJE

The repositories for the code used in each of these projects are linked above.

The codelists are organised by exposure (antidepressants), outcomes (pregnancy and birth), and covariates (smoking, alcohol use, illicit drug use, ethnicity etc.). The codelists are a mix of -

- Prescriptions
    - BNF / prodcodes for CPRD GOLD (*_bnf_codelist)
    - ATC codes for Norway and Sweden (*_atc_codelist)
- Medical information
    - Read / medcodes for CPRD GOLD primary care (*_read_codelist / *_medcode_codelist)
    - ICPC2 codes for Norway primary care (*_icpc_codelist)
    - ICD-10 codes for CPRD GOLD, Norway, and Sweden secondary care (*_icd10_codelist)
    - ICD-9 codes Sweden secondary care (*_icd9_codelist)
