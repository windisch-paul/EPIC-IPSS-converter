# EPIC-IPSS-converter

This repo contains the notebook, dataset, figures, and models that were used for the manuscript "Converting between the International Prostate Symptom Score (IPSS) and the Expanded Prostate Cancer Index Composite (EPIC) Urinary Subscales: Modeling and External Validation".

The paper is available [here](https://bmcurol.biomedcentral.com/articles/10.1186/s12894-024-01421-y).

An online calculator can be accessed at https://www.epic-ipss-converter.com/


# Data

The data is also available via [Dryad](https://datadryad.org/stash/dataset/doi:10.5061/dryad.v6wwpzh4b).

Each row in the table represents a patient and their response. For each patient, there are the following columns:
- __Hospital__: Which hospital treated the patient (KSW = Cantonal Hospital Winterthur, UKRB = Ruppiner Kliniken GmbH).
- __EPIC_1__: The response to the EPIC question "Over the past 4 weeks, how often have you leaked urine?". Possible answers: More than once a day (1), About once a day (2), More than once a week (3), About once a week (4), Rarely or never (5).
- __EPIC_2__: The response to the EPIC question "Over the past 4 weeks, how often have you urinated blood?". Possible answers: More than once a day (1), About once a day (2), More than once a week (3), About once a week (4), Rarely or never (5).
- __EPIC_3__: The response to the EPIC question "Over the past 4 weeks, how often have you had pain or burning with urination?". Possible answers: More than once a day (1), About once a day (2), More than once a week (3), About once a week (4), Rarely or never (5).
- __EPIC_4__: The response to the EPIC question "Which of the following best describes your urinary control during the last 4 weeks?". Possible answers: No urinary control whatsoever (1), Frequent dribbling (2), Occasional dribbling (3), Total control (4).
- __EPIC_5__: The response to the EPIC question "How many pads or adult diapers per day did you usually use to control leakage during the last 4 weeks?". Possible answers: None (0), 1 pad per day (1), 2 pads per day (2), 3 or more pads per day (3).
- __EPIC_6a__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Dripping or leaking urine?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __EPIC_6b__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Pain or burning on urination?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __EPIC_6c__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Bleeding with urination?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __EPIC_6d__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Weak urine stream or incomplete emptying?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __EPIC_6e__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Waking up to urinate?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __EPIC_6f__: The response to the EPIC question "How big a problem, if any, has each of the following been for you during the last 4 weeks - Need to urinate frequently during the day?" Possible answers: No problem (0), Very Small Problem (1), Small Problem (2), Moderate Problem (3), Big Problem (4).
- __Urinary_Summary__: The Urinary Summary domain of the EPIC.
- __Urinary_Function__: The Urinary Function domain of the EPIC.
- __Urinary_Bother__: The Urinary Bother domain of the EPIC.
- __Urinary_Incontinence__: The Urinary Incontinence domain of the EPIC.
- __Urinary_Irritative_Obstructive__: The Urinary Irritative/Obstructive domain of the EPIC
- __IPSS_1__: The answer to the IPSS question "Over the past month, how often have you had a sensation of not emptying your bladder completely after you finish urinating?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_2__: The answer to the IPSS question "Over the past month, how often have you had to urinate again less than two hours after you have finished urinating?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_3__: The answer to the IPSS question "Over the past month, how often have you found you stopped and started again several times when you urinated?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_4__: The answer to the IPSS question "Over the past month, how often have you found it difficult to postpone urination?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_5__: The answer to the IPSS question "Over the last month, how often have you had a weak urinary stream?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_6__: The answer to the IPSS question "Over the past month, how often have you had to push or strain to begin urination?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_7__: The answer to the IPSS question "Over the past month how many times did you most typically get up each night to urinate from the time you went to bed until the time you got up in the morning?" Possible answers: Not at all (0), Less than 1 time in 5 (1), Less than half the time (2), About half the time (3), More than half the time (4), Almost always (5).
- __IPSS_Total__: The sum of the answers to the IPSS questions.
