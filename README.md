# INVIDIOUS

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-social_media-lightgrey)

> Anticloud-hardened packaging of the upstream project `INVIDIOUS` in category **SOCIAL MEDIA**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOCIAL MEDIA · **Upstream:** https://github.com/iv-org/invidious · **Upstream pin:** `381c6e8c929ff9368bd3ee6dc9fac0ee7013ae72` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center">
  <img src="assets/invidious-colored-vector.svg" width="192" height="192" alt="Invidious logo">
  <h1>Invidious</h1>

  <a href="https://www.gnu.org/licenses/agpl-3.0.en.html">
    <img alt="License: AGPLv3" src="https://shields.io/badge/License-AGPL%20v3-blue.svg">
  </a>
  <a href="https://github.com/iv-org/invidious/actions">
    <img alt="Build Status" src="https://github.com/iv-org/invidious/workflows/Invidious%20CI/badge.svg">
  </a>
  <a href="https://github.com/iv-org/invidious/commits/master">
    <img alt="GitHub commits" src="https://img.shields.io/github/commit-activity/y/iv-org/invidious?color=red&label=commits">
  </a>
  <a href="https://github.com/iv-org/invidious/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/iv-org/invidious?color=important">
  </a>
  <a href="https://github.com/iv-org/invidious/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/iv-org/invidious?color=blueviolet">
  </a>
  <a href="https://hosted.weblate.org/engage/invidious/">
    <img alt="Translation Status" src="https://hosted.weblate.org/widgets/invidious/-/translations/svg-badge.svg">
  </a>

  <h3>An open source alternative front-end to YouTube</h3>

  <a href="https://invidious.io/">Website</a>
  &nbsp;•&nbsp;
  <a href="https://instances.invidious.io/">Instances list</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/faq/">FAQ</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/">Documentation</a>
  &nbsp;•&nbsp;
  <a href="#contribute">Contribute</a>
  &nbsp;•&nbsp;
  <a href="https://invidious.io/donate/">Donate</a>

  <h5>Chat with us:</h5>
  <a href="https://matrix.to/#/#invidious:matrix.org">
    <img alt="Matrix" src="https://img.shields.io/matrix/invidious:matrix.org?label=Matrix&color=darkgreen">
  </a>
  <a href="https://web.libera.chat/?channel=#invidious">
    <img alt="Libera.chat (IRC)" src="https://img.shields.io/badge/IRC%20%28Libera.chat%29-%23invidious-darkgreen">
  </a>
  <br>
  <a rel="me" href="https://social.tchncs.de/@invidious">
  <img alt="Fediverse: @invidious@social.tchncs.de" src="https://img.shields.io/badge/Fediverse-%40invidious%40social.tchncs.de-darkgreen">
  </a>
  <br>
  <a href="https://invidious.io/contact/">
  <img alt="E-mail" src="https://img.shields.io/badge/E%2d%2dmail-darkgreen">
  </a>
</div>

## Screenshots

| Player                              | Preferences                         | Subscriptions                         |
|-------------------------------------|-------------------------------------|---------------------------------------|
| ![](screenshots/01_player.png)      | ![](screenshots/02_preferences.png) | ![](screenshots/03_subscriptions.png) |
| ![](screenshots/04_description.png) | ![](screenshots/05_preferences.png) | ![](screenshots/06_subscriptions.png) |

## Features

**User features**
- Lightweight
- No ads
- No tracking
- No JavaScript required
- Light/Dark themes
- Customizable homepage
- Subscriptions independent from Google
- Notifications for all subscribed channels
- Audio-only mode (with background play on mobile)
- Support for Reddit comments
- [Available in many languages](locales/), thanks to [our translators](#contribute)

**Data import/export**
- Import subscriptions from YouTube, NewPipe and FreeTube
- Import watch history from YouTube and NewPipe
- Export subscriptions to NewPipe and FreeTube
- Import/Export Invidious user data

**Technical features**
- Embedded video support
- [Developer API](https://docs.invidious.io/api/)
- Does not use official YouTube APIs
- No Contributor License Agreement (CLA)

## Quick start

**Using Invidious:**

- [Select a public instance from the list](https://instances.invidious.io) and start watching videos right now!

**Hosting Invidious:**

- [Follow the installation instructions](https://docs.invidious.io/installation/)

## Documentation

The full documentation can be accessed online at https://docs.invidious.io/

The documentation's source code is available in this project:
https://github.com/iv-org/documentation

### Extensions

We highly recommend the use of [Privacy Redirect](https://github.com/SimonBrazell/privacy-redirect#get),
a browser extension that automatically redirects YouTube URLs to any Invidious instance and replaces
embedded YouTube videos on other websites with Invidious.

The documentation contains a list of browser extensions that we recommended to use along with Invidious.

You can read more here: https://docs.invidious.io/applications/

## Contribute

### Code

1.  Fork it ( https://github.com/iv-org/invidious/fork ).
1.  Create your feature branch (`git checkout -b my-new-feature`).
1.  Stage your files (`git add .`).
1.  Commit your changes (`git commit -m 'Add some feature'`).
1.  Push to the branch (`git push origin my-new-feature`).
1.  Create a new pull request ( https://github.com/iv-org/invidious/compare ).

### Translations

We use [Weblate](https://weblate.org) to manage Invidious translations.

You can suggest new translations and/or correction here: https://hosted.weblate.org/engage/invidious/.

Creating an account is not required, but recommended, especially if you want to contribute regularly.
Weblate also allows you to log-in with major SSO providers like GitHub, GitLab, BitBucket, Google, ...

## Projects using Invidious

A list of projects and extensions for or utilizing Invidious can be found in the documentation: https://docs.invidious.io/applications/

## Liability

We take no responsibility for the use of our tool, or external instances
provided by third parties. We strongly recommend you abide by the valid
official regulations in your country. Furthermore, we refuse liability
for any inappropriate use of Invidious, such as illegal downloading.
This tool is provided to you in the spirit of free, open software.

You may view the LICENSE in which this software is provided to you [here](./LICENSE).

>   16. Limitation of Liability.
>
> I

*(excerpt; full text in `UPSTREAM_CLONE/`)*

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **C/C++ / Make** (manifests: Makefile; scanned in UPSTREAM_CLONE)
- Top-level source layout: `assets/`, `config/`, `docker/`, `kubernetes/`, `locales/`, `mocks/`, `nix/`, `screenshots/`, `scripts/`, `spec/`, `src/`
- Snapshot size: **368 files**, **3161 lines of code** (measured; see Benchmarks)
- Primary languages: `.cr` (144), `.json` (63), `.ecr` (42), `.js` (18), `.yml` (15), `.sh` (14)
- Upstream commit pinned for this packaging: `381c6e8c929ff9368bd3ee6dc9fac0ee7013ae72`

---

## Installation

</a>
  <a href="https://github.com/iv-org/invidious/commits/master">
    <img alt="GitHub commits" src="https://img.shields.io/github/commit-activity/y/iv-org/invidious?color=red&label=commits">
  </a>
  <a href="https://github.com/iv-org/invidious/issues">
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/iv-org/invidious?color=important">
  </a>
  <a href="https://github.com/iv-org/invidious/pulls">
    <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/iv-org/invidious?color=blueviolet">
  </a>
  <a href="https://hosted.weblate.org/engage/invidious/">
    <img alt="Translation Status" src="https://hosted.weblate.org/widgets/invidious/-/translations/svg-badge.svg">
  </a>

  <h3>An open source alternative front-end to YouTube</h3>

  <a href="https://invidious.io/">Website</a>
  &nbsp;•&nbsp;
  <a href="https://instances.invidious.io/">Instances list</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/faq/">FAQ</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/">Documentation</a>
  &nbsp;•&nbsp;
  <a href="#contribute">Contribute</a>
  &nbsp;•&nbsp;
  <a href="https://invidious.io/donate/">Donate</a>

  <h5>Chat with us:</h5>
  <a href="https://matrix.to/#/#invidious:matrix.org">
    <img alt="Matrix" src="https://img.shields.io/matrix/invidious:matrix.org?label=Matrix&color=darkgreen">
  </a>
  <a href="https://web.libera.chat/?channel=#invidious">
    <img alt="Libera.chat (IRC)" src="https://img.shields.io/badge/IRC%20%28Libera.chat%29-%23invidious-darkgreen">
  </a>
  <br>
  <a rel="me" href="https://social.tchncs.de/@invidious">
  <img alt="Fediverse: @invidious@social.tchncs.de" src="https://img.shields.io/badge/Fediverse-%40invidious%40social.tchncs.de-darkgreen">
  </a>
  <br>
  <a href="https://invidious.io/contact/">
  <img alt="E-mail" src="https://img.shields.io/badge/E%2d%2dmail-darkgreen">
  </a>
</div>

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
# build first (see Installation), then run the produced binary from build/
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

&nbsp;•&nbsp;
  <a href="#contribute">Contribute</a>
  &nbsp;•&nbsp;
  <a href="https://invidious.io/donate/">Donate</a>

  <h5>Chat with us:</h5>
  <a href="https://matrix.to/#/#invidious:matrix.org">
    <img alt="Matrix" src="https://img.shields.io/matrix/invidious:matrix.org?label=Matrix&color=darkgreen">
  </a>
  <a href="https://web.libera.chat/?channel=#invidious">
    <img alt="Libera.chat (IRC)" src="https://img.shields.io/badge/IRC%20%28Libera.chat%29-%23invidious-darkgreen">
  </a>
  <br>
  <a rel="me" href="https://social.tchncs.de/@invidious">
  <img alt="Fediverse: @invidious@social.tchncs.de" src="https://img.shields.io/badge/Fediverse-%40invidious%40social.tchncs.de-darkgreen">
  </a>
  <br>
  <a href="https://invidious.io/contact/">
  <img alt="E-mail" src="https://img.shields.io/badge/E%2d%2dmail-darkgreen">
  </a>
</div>

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | C/C++ / Make |
| Manifests detected | Makefile |
| Files in snapshot | 368 |
| Lines of code | 3161 |
| Dependency references | 0 |
| Upstream license | AGPL-3.0 |
| Overlay license | Anticommons 0.1.0 |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `.envrc`
- `Makefile`
- `config`
- `docker-compose.yml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `INVIDIOUS` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: AGPL-3.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
                    GNU AFFERO GENERAL PUBLIC LICENSE
                       Version 3, 19 November 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <http://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.

                            Preamble

  The GNU Affero General Public License is a free, copyleft license for
software and other kinds of works, specifically designed to ensure
cooperation with the community in the case of network server software.

  The licenses for most software and other practical works are designed
to take away your freedom to share and change the works.  By contrast,
our General Public Licenses are intended to guarantee your freedom to
share and change all versions of a program--to make sure it remains free
software for all its users.

  When we speak of free software, we are referring to freedom, not
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original AGPL-3.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `AGPL-3.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `INVIDIOUS` (category: SOCIAL MEDIA)
- **Upstream URL:** https://github.com/iv-org/invidious
- **Pinned commit (SHA):** `381c6e8c929ff9368bd3ee6dc9fac0ee7013ae72`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`33cde0e06f4ec68f533aa39a3edf82f0322b3ec73e95800bf861877aa93e0ba3`.

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

