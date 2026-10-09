# WRF PYTHON

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-academia_rd-lightgrey)

> Anticloud-hardened packaging of the upstream project `WRF_PYTHON` in category **ACADEMIA RD**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ACADEMIA RD · **Upstream:** https://github.com/the-anticloud/anticloud-wrf-python.git · **Upstream pin:** `a12a6b7caa65fb0811c9d33acd470238da848ec0` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

wrf-python
==============

A collection of diagnostic and interpolation routines for use with output from the Weather Research and Forecasting (WRF-ARW) Model.

This package provides over 30 diagnostic calculations, several interpolation routines, and utilities to help with plotting via cartopy, basemap, or PyNGL. The functionality is similar to what is provided by the NCL WRF package.

Installation
----------------------------

    conda install conda-forge::wrf-python

Documentation
----------------------------------

https://wrf-python.readthedocs.io

Citation
------------------

If you use this software, please cite it as described in the [documentation](
https://wrf-python.readthedocs.io/en/latest/citation.html).

--------------------

*This material is based upon work supported by the NSF National Center for Atmospheric Research, a major facility sponsored by the U.S. National Science Foundation and managed by the University Corporation for Atmospheric Research. Any opinions, findings and conclusions or recommendations expressed in this material do not necessarily reflect the views of the U.S. National Science Foundation.*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `build_envs/`, `build_scripts/`, `doc/`, `fortran/`, `hpc_install/`, `src/`, `test/`
- Snapshot size: **295 files**, **41244 lines of code** (measured; see Benchmarks)
- Primary languages: `.png` (122), `.py` (70), `.rst` (22), `.f90` (21), `.ipynb` (10), `.ncl` (8)
- Upstream commit pinned for this packaging: `a12a6b7caa65fb0811c9d33acd470238da848ec0`

---

## Installation

----------------------------

    conda install conda-forge::wrf-python

Documentation
----------------------------------

https://wrf-python.readthedocs.io

Citation
------------------

If you use this software, please cite it as described in the [documentation](
https://wrf-python.readthedocs.io/en/latest/citation.html).

--------------------

*This material is based upon work supported by the NSF National Center for Atmospheric Research, a major facility sponsored by the U.S. National Science Foundation and managed by the University Corporation for Atmospheric Research. Any opinions, findings and conclusions or recommendations expressed in this material do not necessarily reflect the views of the U.S. National Science Foundation.*

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

This package provides over 30 diagnostic calculations, several interpolation routines, and utilities to help with plotting via cartopy, basemap, or PyNGL. The functionality is similar to what is provided by the NCL WRF package.

Installation
----------------------------

    conda install conda-forge::wrf-python

Documentation
----------------------------------

https://wrf-python.readthedocs.io

Citation
------------------

If you use this software, please cite it as described in the [documentation](
https://wrf-python.readthedocs.io/en/latest/citation.html).

--------------------

*This material is based upon work supported by the NSF National Center for Atmospheric Research, a major facility sponsored by the U.S. National Science Foundation and managed by the University Corporation for Atmospheric Research. Any opinions, findings and conclusions or recommendations expressed in this material do not necessarily reflect the views of the U.S. National Science Foundation.*

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

----------------------------------

https://wrf-python.readthedocs.io

Citation
------------------

If you use this software, please cite it as described in the [documentation](
https://wrf-python.readthedocs.io/en/latest/citation.html).

--------------------

*This material is based upon work supported by the NSF National Center for Atmospheric Research, a major facility sponsored by the U.S. National Science Foundation and managed by the University Corporation for Atmospheric Research. Any opinions, findings and conclusions or recommendations expressed in this material do not necessarily reflect the views of the U.S. National Science Foundation.*

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 295 |
| Lines of code | 41244 |
| Dependency references | 24 |
| Dependencies by ecosystem | conda: 17, native: 2, pypi: 5 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| native | Python | - | CMakeLists.txt |
| native | OpenMP | - | CMakeLists.txt |
| pypi | basemap | - | pyproject.toml |
| pypi | numpy | >=1.11 | pyproject.toml |
| pypi | setuptools | >=61 | pyproject.toml |
| pypi | wrapt | - | pyproject.toml |
| pypi | xarray | - | pyproject.toml |
| conda | conda-forge | - | build_envs/environment.yml |
| conda | python | - | build_envs/environment.yml |
| conda | compilers | - | build_envs/environment.yml |
| conda | basemap | - | build_envs/environment.yml |
| conda | cartopy | - | build_envs/environment.yml |
| conda | jupyter | - | build_envs/environment.yml |
| conda | matplotlib | - | build_envs/environment.yml |
| conda | netcdf4 | - | build_envs/environment.yml |
| ... | (9 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `CMakeLists.txt`
- `pyproject.toml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

Please read the contributor guide here:

https://wrf-python.readthedocs.io/en/latest/contrib.html

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `WRF_PYTHON` (category: ACADEMIA RD)
- **Upstream URL:** https://github.com/the-anticloud/anticloud-wrf-python.git
- **Pinned commit (SHA):** `a12a6b7caa65fb0811c9d33acd470238da848ec0`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`a49a252536cb6ee4966bd522a02e87dc4fcd654b00733643d906679bb6d4d0b9`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

