# NAPCORE Tools (GitHub organization)

Welcome page for **Public**

## Overview

NAPCORE Task 5.2 develops open-source digital tools for European mobility data services, supporting standardized data exchange and interoperability across transport systems.

## 🔧 Our Tools

We are planning to develop or support development of various types of tools such as:

- **Data Validators** - Validate DATEX II, NeTEx, SIRI, and TN-ITS data
- **Format Converters** - Convert between APDS, DATEX II, and NeTEx formats
- **Version Upgrade Tools** - Upgrade data and their schemas from one standard version to another one
- **Reference Implementations** - Documentation and examples

All the tools will be publicly presented on NAPCORE Store website.

## 📚 Getting Started

Initially, development is to be done by NAPCORE project members only. Later we will open our tools to public.

If you are a NAPCORE participant willing to contribute to our tools, use your NAPCORE contacts to ask Task 5.2 leader (Jan Vlčinský + Roman Hořeňovský) to become member of NAPCORE Tools GitHub organization.

## 🏗️ Repository Structure

Our initial plan for repository naming is as follows:

- `mng-*` - Project management (focused mainly on coordination with WG4 tasks)
- `internal-*` - Internal processes
- `web-*` - Web interfaces (namely NAPCORE Store)
- `tool-*` - Production tools
- `refimpl-*` - Reference implementations
- `fstudy-*` - Feasibility studies

## Repository Plan

This is initial plan of repositories in our organization:

- Initial set is created (`.github*`, `discussions`, `internal-*`, `mng-*`).
- Remaining ones is initial estimation and is subject to backlog evaluation where we will decide, which products are to be really developed.

| repo                          | product                                                                   |
| ----------------------------- | ------------------------------------------------------------------------- |
| **Welcome pages**             |                                                                           |
| .github                       | Public welcome page                                                       |
| .github-private               | Private welcome page                                                      |
| **T5.2 Internal management**  |                                                                           |
| discussions                   | Organization-wide discussion forum                                        |
| internal-backlog              | Internal T5.2 backlog                                                     |
| internal-governance           | Internal T5.2 house rules                                                 |
| internal-knowledge_base       | Knowledge base (howtos, best practices, tips and tricks...)               |
| **WG4 Task 4.x coordination** |                                                                           |
| mng-backlog                   | External backlog (for WG4 Task 4.x partners)                              |
| mng-governance                | Governance (for WG4 Task 4.x partners)                                    |
| **NAPCORE Store Web**         |                                                                           |
| web-napcore_store-data        | NAPCORE Store website - data                                              |
| web-napcore_store-frontend    | NAPCORE Store website - frontend                                          |
| **Tools**                     |                                                                           |
| tool-apds_to_d2               | Tool for converting APDS to DATEX II                                      |
| tool-apds_to_netex            | Tool for converting APDS to NeTEx                                         |
| tool-cybersecurity_validator  | Tool for validating Cybersecurity                                         |
| tool-d2browser-docs           | DATEX II Browser - documentation                                          |
| tool-d2browser-frontend       | DATEX II Browser - frontend                                               |
| tool-d2browser-model2json     | DATEX II Browser - convertor model to JSON                                |
| tool-data_validator-d2        | Tool for validating DATEX II messages and schemas                         |
| tool-data_validator-netex     | Tool for validating NeTEx messages and schemas                            |
| tool-data_validator-siri      | Tool for validating SIRI messages and schemas                             |
| tool-data_validator-tn_its    | Tool for validating TN-ITS                                                |
| tool-uvarbox-part_a           | UVARBOX tool - part A (whatever it is)                                    |
| tool-uvarbox-part_b           | UVARBOX tool - part B (whatever it is)                                    |
| tool-ver_upgrade-d2           | Tool for converting DATEX II schemas and messages to higher model version |
| tool-ver_upgrade-netex        | Tool for converting NeTEx schemas and messages to higher model version    |
| tool-ver_upgrade-siri         | Tool for converting SIRI schemas and messages to higher model version     |
| tool-ver_upgrade-tn_its       | Tool for converting TN-ITS schemas and messages to higher model version   |
| **Feasibility Studies**       |                                                                           |
| fstudy-compl_cert_prog        | Feasibility study for Compliance Certification Programme                  |
| fstudy-data_consumer_feedback | Feasibility study for Data Consumer Feedback                              |
| fstudy-enh_data_quality       | Feasibility study for Enhanced Data Quality Assesment                     |
| **Reference Implementations** |                                                                           |
| refimpl-docs_format_d2-mdbook | Reference implementation of documenting DATEX II format using mdbook      |
| refimpl-docs_format_d2-mkdocs | Reference implementation of documenting DATEX II format using mkdocs      |
| refimpl-docs_format_d2-prd    | Product Requirements Document for documenting DATEX II format             |

