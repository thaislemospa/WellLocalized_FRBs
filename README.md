# WellLocalized_FRBs

A catalog of well-localized fast radio bursts (FRBs) with identified host galaxies and measured redshifts currently available in the literature.

## Contents

This repository contains two catalogs:

* **frbs_full.csv** — the current sample of well-localized FRBs, comprising 117 events.
* **frbs_sub.csv** — a subsample of the full catalog.

## Catalog Description

Both catalogs contain the following columns:

| Column         | Description                                                                                             |
| -------------- | ------------------------------------------------------------------------------------------------------- |
| Name           | FRB name according to the Transient Name Server (TNS).                                                  |
| Telescope      | Telescope or collaboration responsible for the detection.                                               |
| Classification | Repeating or Non-Repeating FRB.                                                                         |
| RA             | Right Ascension (hours).                                                                                |
| DEC            | Declination (degrees).                                                                                  |
| Redshift       | Host galaxy redshift.                                                                                   |
| u_redshift     | Uncertainty in the host galaxy redshift, when available.                                                |
| DM_MW_ISM      | Milky Way interstellar medium contribution to the dispersion measure, estimated using the NE2001 model. |
| DM_obs         | Observed dispersion measure of the FRB.                                                                 |
| u_obs          | Uncertainty in the observed dispersion measure.                                                         |
| Reference      | Literature reference associated with the event.                                                         |
| Observation    | Additional comments or notes.                                                                           |

## Notes

Some events, particularly those detected by DSA-110, do not have reported values for **u_obs**. Readers interested in mitigating the impact of missing dispersion measure uncertainties may refer to https://arxiv.org/abs/2504.21129 and https://arxiv.org/abs/2507.17693 for further discussion.

The catalog is intended to be updated periodically as new well-localized FRBs and host galaxy identifications become available in the literature.

## Usage

This repository is intended to provide an easily accessible compilation of host-associated FRBs for statistical studies, cosmological analyses, population studies, and educational purposes.

## Contact

For questions, suggestions, corrections, or contributions, please contact:

* [thaislemos@on.br](mailto:thaislemos@on.br)
* [thais.lemospa@gmail.com](mailto:thais.lemospa@gmail.com)

Suggestions and contributions are always welcome.

## Acknowledgements

I hope this repository will be useful for students, researchers, and anyone interested in performing analyses using FRB data.
