# TRIAD Guard

TRIAD Guard is a prototype decision-support application for the TRIAD-QEHS framework, which integrates journey, driver and vehicle management for chemical road transport. It implements the readiness gate (Eqs. 1–5), live re-gating (Eq. 6), route risk (Eq. 7), the QEHS performance index (Eq. 8) and the maturity score (Eq. 9) described in:

> Hussain W, Hashmi SAM, Anggraini L, Lock SSM, Sutisna NA, Heryana G, Mumtaz M, Khan S. One journey, one system: integrated safety management of chemical road transport. Manuscript submitted for publication.

## Running it

The application is a single HTML file with no installation, server or internet connection required. Download `index.html` and open it in a current version of Chrome, Edge, Firefox or Safari. All data stay in the browser.

## What it contains

- Journey, driver and vehicle keys with default critical and supporting criteria (Table 4 of the paper)
- Readiness gate with the three-key non-compensatory rule, two-person conditional release and override log
- Live trip with triggers that reopen a key until a required action is recorded
- Emergency, debrief and learning-loop screens
- QEHS dashboard with 18 indicators, maturity scoring and a calibration module with sensitivity analysis and a self-test against the worked example (Table 5 of the paper)

## Limitations

Route, fleet and segment values are illustrative or synthetic. Weights, thresholds and targets are initial proposals to be validated by expert consensus and calibration against outcomes. Isolation distances and legal limits must come from the ERG, ERICards and national law. The prototype has not been field-tested and does not replace the judgement of qualified people.

## Contact

Corresponding author: Waqar Hussain, Universiti Teknologi PETRONAS, Malaysia.

## Citation

Please cite the archived release on Zenodo and the paper. Citation metadata are in `CITATION.cff`.

## Licence

Released under the MIT Licence (see `LICENSE`).
