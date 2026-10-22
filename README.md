# governed-eqms

Open-source governed agentic electronic quality management system (eQMS).

## Scope
Four modules:
- Organization chart with role-based authorization: authority to review, approve and act is assigned by each person's role in quality, regulatory and operations.
- KPI dashboard for quality and operational performance.
- Kappa AI decision-maker module: acts inside the organization chart and KPI dashboard, within role-based authority, through bounded connectors, with human sign-off gates.
- Document control (documentation) module.

Supporting documents, schemas and the evidence format are published under CC BY 4.0 in [governed-eqms-docs](https://github.com/biomedical78/governed-eqms-docs).

## Deployment
- **Pilot:** runs on Spearhead-owned NVIDIA DGX Spark hardware at the pilot manufacturer's site. Data stays on site.
- **Hosted service:** Spearhead Consulting LLC hosts the system on AWS as a managed service billed per token. In the hosted offering, the eQMS software and databases run in Spearhead's AWS cloud. Token billing never governs authorization, which comes from the organization chart by role.
- **Self-hosting:** clone the open-source repositories, provision your own DGX-class hardware, and follow this README and the installation instructions.

## Status
Initial release in preparation. Source code will be published in this repository.

## License
Copyright (c) 2026 Spearhead Consulting LLC.
Licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). See LICENSE.
