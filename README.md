# Quadruple Licenses Public Domain

A standardized, ready-to-use public-domain-equivalent licensing template designed for bulk use, starter kits, and open-source project templates where attribution is not required.

## Overview

Creative Commons (**CC0 1.0**) is the industry standard for creative assets, **ODC-PDDL 1.0** is specifically designed for databases and datasets, while **MIT-0** and **0BSD** are built for source code. Combining them improperly can create legal ambiguity—particularly regarding software patents, database rights, and moral rights. 

This repository provides a single, unified `LICENSE` file that cleanly separates software logic, creative media, and data assets:

- **Source Code & Scripts:** Dual-licensed under **MIT-0 OR 0BSD** (at the user's choice).
- **Creative Assets & Media:** Dedicated to the public domain under **CC0 1.0 Universal**.
- **Data Assets & Databases:** Dedicated to the public domain under **ODC Public Domain Dedication and License 1.0 (ODC-PDDL 1.0)**.
- **Strict Separation:** CC0 1.0 applies *exclusively* to creative media (images, audio, models, fonts, etc.) and ODC-PDDL 1.0 applies *exclusively* to datasets and databases. Neither applies to source code or scripts.

## How to Use

1. Copy the contents of the [`LICENSE`](LICENSE) file into the root directory of your own repository.
2. Replace `<year>` and `<copyright holders>` in Parts 1 and 2 with your own details.
3. Ensure your repository clearly distinguishes source code files, creative asset files, and data asset files.

## Included Licenses

- **MIT No Attribution (`MIT-0`)** – Applies to source code and scripts.
- **Zero-Clause BSD (`0BSD`)** – Alternative license option for source code and scripts.
- **Creative Commons Zero v1.0 Universal (`CC0-1.0`)** – Applies strictly to creative assets and media.
- **ODC Public Domain Dedication and License 1.0 (`PDDL-1.0`)** – Applies strictly to data assets, datasets, and databases.

---

*Disclaimer: This repository provides a structural combination of standard, SPDX-approved and Open Data Commons (opendatacommons.org) open-source and public-domain licenses. It does not constitute formal legal advice.*
