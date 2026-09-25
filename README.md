# SBOM & VEX Working Group

<img align="right" src="https://github.com/ossf/tac/blob/main/files/images/OpenSSF_StagesBadges_sandbox.svg" width="100" height="100" alt="OpenSSF sandbox WG badge">

The SBOM & VEX Working Group (SBOM-VEX-WG) is a [Sandbox-level](https://github.com/ossf/tac/blob/main/process/working-group-lifecycle.md#to-become-sandbox) working group of the [Open Source Security Foundation (OpenSSF)](https://openssf.org).

We are a format-agnostic, neutral forum that unites tool builders, software producers, end-users, and standards bodies to drive the practical adoption, harmonization, and maturity of Software Bills of Materials (SBOM) and Vulnerability Exploitability eXchange (VEX) across the open source ecosystem.

## Quick Start

- **Read** the [charter](CHARTER.md) for the group's mission, scope, and governance.
- **Join** the [OpenSSF Slack](https://slack.openssf.org/) and say hi in the working group channel, **#wg-sbom-vex**.
- **Attend** a call. All meetings are on the [OpenSSF Community Calendar](https://calendar.google.com/calendar/u/0?cid=czYzdm9lZmhwNWk5cGZsdGI1cTY3bmdwZXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ). See [Meeting Times](#meeting-times) below.
- **Contribute** by opening an [issue](https://github.com/ossf/wg-sbom-vex/issues) or a pull request in this repository, or in one of the [hosted projects](#hosted-projects).

## Mission

Our objective is to bridge the gap between specification and application: transforming community energy into actionable guidance, interoperable tooling, and automated supply chain security outcomes.

The full mission statement is in the [charter](CHARTER.md#1-mission).

## Scope

The working group structures its initiatives, hosted projects, and community engagement around three pillars (see the [charter](CHARTER.md#2-scope) for details):

1. **Formats and Standards.** A neutral ground to map implementation gaps, capture emerging requirements, and drive the effective application of SPDX, CycloneDX, CSAF, and OpenVEX. We foster interoperability across formats ("Pax Interoperabilitatis"), support the evolution of the VEX metaspec and  best practices for SBOM generation in product lifecycles, and maintain feedback loops with external standards bodies.
2. **Technical Initiatives.** We incubate, host, and maintain developer-focused tools that automate the generation, consumption, validation, and enrichment of SBOM and VEX artifacts, and we support emerging domain-specific tools such as those extending SBOMs into data and AI.
3. **Education and Adoption.** We author guides and playbooks, benchmark tooling, and cultivate open forums to lower the barrier to entry for software transparency, for both producers and downstream consumers.

### Scope Axes

Software transparency underpins multiple facets of security and compliance. To keep our work grounded, we position every effort along two axes. The first axis is the **audience** we serve: **education** (guidance, training, and community enablement for practitioners) and **industry** (tooling, standards, and engineering outcomes for producers and consumers).

The second axis is the set of four **anchors** where SBOM and VEX data create value: **Compliance & Policy**, **AI**, **Supply Chain Security**, and **Vulnerability Management**. Each anchor maps to a sister OpenSSF working group we collaborate with.

| Anchor | Education | Industry | Sister WG |
| :--- | :--- | :--- | :--- |
| **Compliance & Policy** | Plain-language guides that translate international software transparency regulations and compliance mandates (e.g. the EU Cyber Resilience Act, US federal guidance) into what developers and stewards actually need to produce. | Act as an agile technical responder to regulatory frameworks; map regulatory requirements to concrete SBOM and VEX fields and tooling so that conformance can be automated. | [Global Cyber Policy](https://github.com/ossf/wg-globalcyberpolicy) |
| **AI** | Educational material on software transparency for models, datasets, and AI systems, and how existing SBOM formats express them (e.g. AIBOM). | Design, validate, and expand SBOM and VEX paradigms into data and machine learning domains; support domain-specific tools and feed requirements back to the format communities. | [AI/ML Security](https://github.com/ossf/ai-ml-security) |
| **Supply Chain Security** | Playbooks for generating, distributing, and consuming SBOMs across the software lifecycle, and benchmarking criteria to help adopters choose tools. | Host and maintain foundational SBOM tooling (Protobom, bomctl, BOMHort); define how SBOM and VEX artifacts integrate with attestation, provenance, and secure build pipelines. | [Supply Chain Integrity](https://github.com/ossf/wg-supply-chain-integrity) |
| **Vulnerability Management** | Guidance for upstream projects on issuing VEX statements and for downstream consumers on ingesting them, including troubleshooting and peer-to-peer enablement. | Maintain OpenVEX and support the VEX metaspec across CSAF, CycloneDX, OpenVEX, and SPDX; align VEX data structures with coordinated vulnerability disclosure and advisory workflows. | [Vulnerability Disclosures](https://github.com/ossf/wg-vulnerability-disclosures) |

## Hosted Projects

The working group provides governance, maintenance, and roadmap support for the following projects. Project progression from Sandbox to Incubating to Graduated follows the [OpenSSF TAC project lifecycle](https://github.com/ossf/tac/blob/main/process/project-lifecycle.md).

| Project | Description | Repository | Slack | Meeting |
| :--- | :--- | :--- | :--- | :--- |
| **Protobom** | A universal SBOM representation in protocol buffers, with a Go library to read, write, and translate between SPDX and CycloneDX. | [protobom/protobom](https://github.com/protobom/protobom) | [#protobom](https://openssf.slack.com/archives/C06ED97EQ4B) | Every other Wednesday, 12:00 PM CT / 1:00 PM ET / 10:00 AM PT |
| **bomctl** | Format-agnostic SBOM tooling that bridges the gap between SBOM generation and analysis tools, built on Protobom. | [bomctl/bomctl](https://github.com/bomctl/bomctl) | [#bomctl](https://openssf.slack.com/archives/C06ED5VB81W) | TBD |
| **BOMHort** | A standalone, Kubernetes-native SBOM visualization and governance platform. | [seebom-labs/BOMHort](https://github.com/seebom-labs/BOMHort) | TBD | TBD |
| **OpenVEX** | A minimal, compliant, interoperable, and embeddable implementation of VEX, with the `vexctl` tooling. | [openvex](https://github.com/openvex) · [ossf/OpenVEX](https://github.com/ossf/OpenVEX) | [#openssf-sig-openvex](https://openssf.slack.com/archives/C05009RHCNT) | Discussed in the VEX Call, see [Meeting Times](#meeting-times) |

Previous SBOM community work that this working group continues can be found in the [SBOM Everywhere SIG](https://github.com/ossf/sbom-everywhere) repository.

## Get Involved

Anyone is welcome to join. The group is open to participation from anyone who abides by the [OpenSSF Code of Conduct](https://openssf.org/community/code-of-conduct/), OpenSSF member or not.

- **Slack:** **#wg-sbom-vex** is the working group's channel. Topic-specific discussion also happens in [#sig-sbom-everywhere](https://openssf.slack.com/archives/C03GKSYFRC0) for SBOM and [#openssf-sig-openvex](https://openssf.slack.com/archives/C05009RHCNT) for VEX. Join the workspace at <https://slack.openssf.org/>.
- **Calendar:** [OpenSSF Community Calendar](https://calendar.google.com/calendar/u/0?cid=czYzdm9lZmhwNWk5cGZsdGI1cTY3bmdwZXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) (Zoom links are in each invite).
- **Issues:** file [issues in this repository](https://github.com/ossf/wg-sbom-vex/issues) for working group matters, or in the relevant hosted project for tooling and specification matters.

## Meeting Times

The working group uses a multi-tiered meeting structure. All calls are open to everyone and are listed on the [OpenSSF Community Calendar](https://calendar.google.com/calendar/u/0?cid=czYzdm9lZmhwNWk5cGZsdGI1cTY3bmdwZXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ), which is the source of truth for dates, Zoom links, and cancellations. Times are shown in US Eastern and US Pacific time and shift with daylight saving time.

| Meeting | Cadence | Time | Notes | Slack | Mailing List |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **SBOM Call** (calendar: *SBOM Everywhere SIG*) | Every other Friday | 11:05 AM ET / 8:05 AM PT | [Meeting Notes](https://docs.google.com/document/d/1wz1mzTkRUPmGtaXAe05hL9agXW5uZ07mdhTfCR1RWQo/edit) | [#sig-sbom-everywhere](https://openssf.slack.com/archives/C03GKSYFRC0) | [openssf-sig-sbom](https://lists.openssf.org/g/openssf-sig-sbom) |
| **VEX Call** (calendar: *VEX SIG*) | Every other Monday | 3:00 PM ET / 12:00 PM PT | [Meeting Notes](https://docs.google.com/document/d/1AIL5FFbEXzVMTc0ygEFEJ7aR7EhDuBKDWinpzsCKHDA/edit) | [#openssf-sig-openvex](https://openssf.slack.com/archives/C05009RHCNT) | [openssf-sig-openvex](https://lists.openssf.org/g/openssf-sig-openvex) |
| **SBOM Coffee Hour** (calendar: *OpenSSF SBOM Coffee Club*) | Every Monday | 11:00 AM ET / 8:00 AM PT | [Meeting Notes](https://docs.google.com/document/d/1aio7P-1PoumfQhMOHQ4gcei9qqUz_RYRvG1MmHpau_k/edit) | [#sig-sbom-everywhere](https://openssf.slack.com/archives/C03GKSYFRC0) | [openssf-sbom-coffee-club](https://lists.openssf.org/g/openssf-sbom-coffee-club) |
| **OpenVEX Project Call** | Monthly | TBD | TBD | [#openssf-sig-openvex](https://openssf.slack.com/archives/C05009RHCNT) | [openssf-sig-openvex](https://lists.openssf.org/g/openssf-sig-openvex) |
| **Protobom Project Meeting** | Every other Wednesday | 12:00 PM CT / 1:00 PM ET / 10:00 AM PT | [Meeting Notes](https://docs.google.com/document/d/1pln25okuHcbyYutA1rAHjepkRwTdFR0hcmO5pmsTv8g/edit) | [#protobom](https://openssf.slack.com/archives/C06ED97EQ4B) | [protobom](https://lists.openssf.org/g/protobom) |
| **SBOMit Weekly Meeting** | Every Wednesday | 11:00 AM ET / 8:00 AM PT | [Meeting Notes](https://docs.google.com/document/d/1-nHXMqvWNzgOxAq08O8Wu2BTHz0U60yBoAklrJAMaRc/edit) | [#sbomit](https://openssf.slack.com/archives/C04U3BHL0AE) | [sbomit](https://lists.openssf.org/g/sbomit-sbomit) |

- The **SBOM Call** is the structured engineering and planning forum to track deliverables, tool development, and broader ecosystem alignment.
- The **VEX Call** is a format-neutral sync to review real-world implementation experiences, address automation gaps, and optimize VEX interoperability.
- The **OpenVEX Project Call** is a dedicated technical sync focused exclusively on OpenVEX specification updates, tooling, and roadmap execution.
- The **SBOM & VEX Coffee Hour** is an informal community gathering for guest presentations, emerging research reviews, and unstructured Q&A for new adopters.

## Cross-WG Collaboration

Fragmented efforts harm the ecosystem. The working group maintains strategic touchpoints with the following OpenSSF working groups, each of which maps to one anchor of the [scope axes](#scope-axes). We are proposing a collaboration model with each of them, which may take the form of recurring joint calls or standing agenda items on their regular community calls. Their regular meetings are listed below so members of this group can attend; all are on the [OpenSSF Community Calendar](https://calendar.google.com/calendar/u/0?cid=czYzdm9lZmhwNWk5cGZsdGI1cTY3bmdwZXNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ).

| Working Group | Collaboration Focus | Regular Meeting | Slack |
| :--- | :--- | :--- | :--- |
| [Supply Chain Integrity](https://github.com/ossf/wg-supply-chain-integrity) | Attestation frameworks, provenance pipelines, and how SBOM and VEX artifacts integrate with them. | Every other Wednesday, 12:00 PM ET / 9:00 AM PT | [#wg_supply_chain_integrity](https://openssf.slack.com/messages/wg_supply_chain_integrity) |
| [Vulnerability Disclosures](https://github.com/ossf/wg-vulnerability-disclosures) | Downstream ingestion workflows and aligning VEX with coordinated vulnerability disclosure and advisory practices. | Every other Wednesday, 11:00 AM ET / 8:00 AM PT (plus an APAC-friendly call on the fourth Thursday of each month, 6:00 PM ET / 3:00 PM PT) | [#wg_vulnerability_disclosures](https://openssf.slack.com/archives/C019Y2A28Q6) |
| [Global Cyber Policy](https://github.com/ossf/wg-globalcyberpolicy) | Translating international software transparency regulations and compliance mandates into actionable developer tools. | Every other Monday, 9:00 AM ET / 6:00 AM PT (3:00 PM CET) | [#wg-globalcyberpolicy](https://openssf.slack.com/archives/C084A6XPX0F) |
| [AI/ML Security](https://github.com/ossf/ai-ml-security) | Extending SBOM paradigms into data and machine learning domains (e.g. AIBOM). | Every other Thursday, 2:00 PM ET / 11:00 AM PT | [#wg-ai-ml-security](https://openssf.slack.com/archives/C0587E513KR) |

Outside the OpenSSF, we directly engage the [SPDX](https://spdx.dev/), [CycloneDX](https://cyclonedx.org/), and [OASIS CSAF](https://oasis-open.github.io/csaf-documentation/) communities to preserve format-neutral interoperability.

## Governance

The [CHARTER.md](governance/CHARTER.md) outlines the scope and governance of our group activities. The working group operates under standard OpenSSF governance principles, striving for lazy consensus among active contributors, and is consistent with the operating guidelines of the OpenSSF [Technical Advisory Council (TAC)](https://github.com/ossf/tac).

### Chairs

The working group is led by three Steering Chairs serving staggered, renewable one-year terms, elected by the active contributors of the working group. The following individuals serve as **interim chairs** until the first election, which will be held within three months of the group's formation:

- Allan Friedman ([@allanfriedman](https://github.com/allanfriedman))
- Adolfo García Veytia ([@puerco](https://github.com/puerco))
- Kate Stewart ([@kestewart](https://github.com/kestewart))

### Reporting

Chairs deliver quarterly status updates to the TAC and post brief bi-weekly summaries to the primary OpenSSF community Slack channels.

### Licenses

In accordance with the [OpenSSF Charter](https://charter.openssf.org/), code contributions are licensed under [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) and documentation under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

### Code of Conduct

This group operates according to the [OpenSSF Code of Conduct](https://openssf.org/community/code-of-conduct/).

## Antitrust Policy Notice

Linux Foundation meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct all of its activities in accordance with applicable antitrust and competition laws. It is therefore extremely important that attendees adhere to meeting agendas, and be aware of, and not participate in, any activities that are prohibited under applicable US state, federal or foreign antitrust and competition laws.

Examples of types of actions that are prohibited at Linux Foundation meetings and in connection with Linux Foundation activities are described in the Linux Foundation Antitrust Policy available at <http://www.linuxfoundation.org/antitrust-policy>. If you have questions about these matters, please contact your company counsel, or if you are a member of the Linux Foundation, feel free to contact Andrew Updegrove of the firm of Gesmer Updegrove LLP, which provides legal counsel to the Linux Foundation.
