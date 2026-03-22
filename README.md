# BRD Investigations: Core Code & Architecture
**Official Website:** [brdinvestigations.co.uk](https://www.brdinvestigations.co.uk)

This repository houses the central codebase, custom styling, and backend architecture for **Beyond Reasonable Doubt (BRD) Investigations**. 

We are an independent UK news and forensic analysis platform dedicated to investigating systemic failures, challenging official narratives, and exposing miscarriages of justice. A primary focus of our current investigative journalism is the rigorous breakdown of the flawed medical and statistical evidence used in the Lucy Letby case.

## Repository Purpose
To ensure our platform remains lightning-fast, secure, and highly scalable, we operate on a decoupled architecture. This repository acts as our Content Delivery Network (CDN) and backend logic hub, containing:

* **`/css/`**: Master stylesheets overriding our core Blogger CMS framework, ensuring a distraction-free, highly readable experience for deep-dive forensic articles.
* **`/js/`**: Custom front-end scripts, including our proprietary `brd-tooltip` engine, which provides readers with instant definitions of complex medical and legal terminology.
* **`/workers/`**: Cloudflare Worker APIs and D1 database logic that power our secure, independent community discussion forums.

## Legal & Copyright
**Copyright (c) 2026 BRD Investigations (Beyond Reasonable Doubt Investigations). All Rights Reserved.**

This repository and its contents are the exclusive intellectual property of BRD Investigations. You may not use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of this code, scripts, or associated assets without the express written permission of the Editor.

For professional inquiries, please contact: editor@brdinvestigations.co.uk