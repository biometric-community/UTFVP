# UTFVP

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FUTFVP-181717?logo=github)](https://github.com/biometric-community/UTFVP)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.utwente.nl/)

**UTFVP** — tbiom catalog packaging for `utfvp` (vein; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/UTFVP
- **Upstream source**: https://www.utwente.nl/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `utfvp` |
| Category | `vein` |
| Access | `register` |
| Upstream homepage | https://www.utwente.nl/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: University of Twente Finger Vascular Pattern; request from authors.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/UTFVP.git
cd UTFVP
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_utfvp.sh
```

Place licensed archives under `projects/datasets/utfvp/` (gitignored).

## Dataset structure

```text
UTFVP/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.utwente.nl/
- Packaging: https://github.com/biometric-community/UTFVP/issues
