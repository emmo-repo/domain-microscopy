# Domain Ontology for Microscopy (DOM)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15767873.svg)](https://doi.org/10.5281/zenodo.15767873)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![CI tests](https://github.com/emmo-repo/domain-microscopy/actions/workflows/ci_tests.yml/badge.svg)](https://github.com/emmo-repo/domain-microscopy/actions/workflows/ci_tests.yml)
[![GitHub release](https://img.shields.io/github/v/release/emmo-repo/domain-microscopy)](https://emmo-repo.github.io/domain-microscopy)

<!--
[![FOOPS Score](https://img.shields.io/badge/FOOPS%20Score-79.0%25-yellow)](https://foops.linkeddata.es/FAIR_validator.html)

[![GitHub release](https://img.shields.io/github/v/release/emmo-repo/emmo/domain-pemfc)](https://emmo-repo.github.io/)
![docs](https://github.com/emmo-repo/domain-pemfc/actions/workflows/docs-build-and-deploy.yml/badge.svg)
[![unstable](http://badges.github.io/stability-badges/dist/unstable.svg)](http://github.com/badges/stability-badges)
-->

A domain ontology for microscopy that has a special focus on Transmission Electron Microscopy, Scanning Electron Microscopy and Light Microscopy.

This ontology builds on CHAMEO, and extends the following branches with specialised classes for microscopy:
- characterisation processes
- sample preparation processes
- image processing processes
- measurement results

Based on DOM, specialised sub-domain ontologies for [TEM] and [SEM] are under development.


### Imported ontologies
Version dependencies on imported ontologies:

| Version    | [EMMO] | [CHAMEO] | Status      |
|------------|--------|----------|-------------|
| 0.0.1      | 1.0.0  | 1.0.0    | stable      |
| 0.0.2      | 1.0.0  | 1.0.0    | stable      |
| 0.5.3      | 1.0.0  | 1.0.0    | stable      |
| 0.6.0-beta | 1.0.2  | 1.0.2    | development |


## License
This ontology is released under the [Creative Commons Attribution 4.0
International](https://creativecommons.org/licenses/by/4.0/legalcode)
license (CC BY 4.0).


### Acknowledgement
This work has been supported by the following projects:

  - [SFI PhysMet](https://www.ntnu.edu/physmet/) (2020-2028) that receives funding from the Research Council of Norway, project no. 309584.
  - [MatCHMaker](https://he-matchmaker.eu/) (2023-2027) that receives funding from the European Unio's Horizon Europe Research and Innovation Programme, under Grant Agreement n. 101091687.


[EMMO]: https://github.com/emmo-repo/EMMO
[CHAMEO]: https://github.com/emmo-repo/domain-characterisation-methodology
[TEM]: https://github.com/TEM-Gemini-Centre/TEMGeminiOntology
[SEM]: https://github.com/emmo-repo/domain-concrete/blob/master/sem.ttl
