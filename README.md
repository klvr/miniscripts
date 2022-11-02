# Repository for (recyclable) specific mini-scripts

Contains small functions / scripts for commonly repeated tasks.
To be sourced into other projects when needed.

## Contents:

    project/
    │   README.md         - ReadMe file.
    │   miniscripts.Rproj - R-project file.
    |   renv.lock         - File for recreating my local R environment via the 'renv'-package.
    │
    └───src/ - Main container in this repository.
    │   │
    │   └───recoding/ - Contains functions for recoding of questionnaire responses
    │       recoding.cape.R    - Community Assessment of Psychic Experiences.
    │       recoding.ellsdyn.R - Text-based titration version of Ellsberg/Ambiguity task. 
    │       recoding.fdc.R     - Five Dimensions of (informational) curiosity.
    │       recoding.gender.R  - Gender demographic responses.
    │       recoding.ius.R     - Intolerance of Uncertainty scale.
    │       recoding.nfc.R     - Need for Cognition scale.
    │       recoding.rq.R      - Generic reasoning items (single answer + probability matching).
    │
    └───renv/ - Contains resources needed to recreate my local R environment via the 'renv'-package.
    
