# US Court of Appeals for the Federal Circuit (us-court-of-appeals-for-the-federal-circuit)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The US Court of Appeals for the Federal Circuit is a federal appellate court with nationwide jurisdiction over cases involving patent law, international trade, government contracts, federal employment, veterans' benefits, and other specialized areas of federal law. The court provides public access to opinions and orders from 2004 to present, with full case records accessible via PACER for cases filed after March 1, 2012. PACER offers developer APIs including the Authentication API and Case Locator (PCL) API for programmatic federal court data access.

**URL:** [https://www.cafc.uscourts.gov/](https://www.cafc.uscourts.gov/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Federal Government, Legal, Patent Law, Federal Courts, Appellate Courts

## Timestamps

- **Created:** 2024-12-25
- **Modified:** 2026-05-03

## APIs

### PACER - Public Access to Court Electronic Records

Public Access to Court Electronic Records (PACER) provides online access to U.S. Federal Court case and docket information including the Federal Circuit (CAFC). Provides Authentication API and Case Locator (PCL) API for programmatic access.

**Human URL:** [https://pacer.uscourts.gov/file-case/court-cmecf-lookup/court/CAFC](https://pacer.uscourts.gov/file-case/court-cmecf-lookup/court/CAFC)

#### Tags:

 - Federal Courts, PACER, Case Records, Legal

#### Properties

- [Documentation](https://pacer.uscourts.gov/file-case/court-cmecf-lookup/court/CAFC)
- [APIReference - PACER Developer Resources](https://pacer.uscourts.gov/file-case/developer-resources)
- [Documentation - PACER Authentication API User Guide](https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide)
- [Documentation - PACER Case Locator (PCL) API User Guide](https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide)

### Federal Circuit Opinions and Orders

Public access to Federal Circuit opinions, orders, and judgments from October 1, 2004, to present in PDF format.

**Human URL:** [https://www.cafc.uscourts.gov/home/case-information/opinions-orders/](https://www.cafc.uscourts.gov/home/case-information/opinions-orders/)

#### Tags:

 - Federal Courts, Opinions, Legal Decisions, Legal

#### Properties

- [Documentation - Opinions and Orders Search](https://www.cafc.uscourts.gov/home/case-information/opinions-orders/)

### Federal Circuit Case Records

Case information and records for the Federal Circuit, accessible via PACER for cases filed on or after March 1, 2012.

**Human URL:** [https://www.cafc.uscourts.gov/home/case-information/case-records/](https://www.cafc.uscourts.gov/home/case-information/case-records/)

#### Tags:

 - Federal Courts, Case Records, Legal

#### Properties

- [Documentation](https://www.cafc.uscourts.gov/home/case-information/case-records/)
- [Getting Started](https://www.cafc.uscourts.gov/home/case-information/)
- [JSONSchema - Federal Circuit Case Schema](json-schema/cafc-case-schema.json)
- [JSONSchema - Federal Circuit Opinion Schema](json-schema/cafc-opinion-schema.json)
- [JSONSchema - PACER Docket Entry Schema](json-schema/cafc-docket-entry-schema.json)

## Common Properties

- [Website](https://www.cafc.uscourts.gov/)
- [Documentation - Case Information](https://www.cafc.uscourts.gov/home/case-information/)
- [Documentation - Opinions and Orders](https://www.cafc.uscourts.gov/home/case-information/opinions-orders/)
- [Getting Started - PACER Registration](https://pacer.uscourts.gov/)
- [APIReference - PACER Developer Resources](https://pacer.uscourts.gov/file-case/developer-resources)
- [Rules and Procedures](https://www.cafc.uscourts.gov/home/rules-procedures/)
- [Contact the Court](https://www.cafc.uscourts.gov/home/about-the-court/contact/)
- [Vocabulary](vocabulary/us-court-of-appeals-for-the-federal-circuit-vocabulary.yml)
- [JSON-LD Context](json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| PACER Case Locator API | Programmatic access to the nationwide federal court case index for case and party searches across all federal courts. |
| PACER Authentication API | API allowing automated authentication to PACER without a user interface for programmatic court record access. |
| CM/ECF Electronic Filing | Court's electronic filing system with XML tags and NextGen CM/ECF integration for document filing and management. |
| Online Opinions and Orders | Free public access to all Federal Circuit opinions, orders, and judgments published from October 2004 to present. |
| Scheduled Cases Calendar | Online calendar of scheduled oral argument cases and courtroom assignments. |
| Statistical Reports | Aggregated case statistics and reports available through the data request process. |

## Use Cases

| Name | Description |
|------|-------------|
| Patent Case Legal Research | Researching Federal Circuit patent law precedent using published opinions, orders, and PACER case dockets. |
| Federal Employment and Veterans Claims Research | Finding Federal Circuit decisions on government contracts, federal employment, and veterans benefits. |
| Court Records Access via PACER | Programmatic access to Federal Circuit case dockets and filings using PACER APIs. |
| Appellate Monitoring | Monitoring active Federal Circuit cases, oral arguments, and new opinions in specific legal areas. |
| Legal Data Analytics | Analyzing trends in Federal Circuit patent, trade, and government contract decisions. |

## Integrations

| Name | Description |
|------|-------------|
| PACER System | Federal Circuit case records integrated with the nationwide PACER federal court records system. |
| CourtListener | Free Law Project's CourtListener provides API access to Federal Circuit opinions and RECAP-archived documents. |
| Justia Dockets | Justia aggregates Federal Circuit case docket information for public access. |

## Artifacts

Machine-readable data specifications organized by format.

### JSON Schema

- [Federal Circuit Case Schema](json-schema/cafc-case-schema.json)
- [Federal Circuit Opinion Schema](json-schema/cafc-opinion-schema.json)
- [PACER Docket Entry Schema](json-schema/cafc-docket-entry-schema.json)

### JSON Structure

- [Federal Circuit Case Structure](json-structure/cafc-case-structure.json)
- [Federal Circuit Opinion Structure](json-structure/cafc-opinion-structure.json)
- [PACER Docket Entry Structure](json-structure/cafc-docket-entry-structure.json)

### JSON-LD

- [US Court of Appeals for the Federal Circuit Context](json-ld/us-court-of-appeals-for-the-federal-circuit-context.jsonld)

### Examples

- [Federal Circuit Case Example](examples/cafc-case-example.json)
- [Federal Circuit Opinion Example](examples/cafc-opinion-example.json)
- [PACER Docket Entry Example](examples/cafc-docket-entry-example.json)

## Vocabulary

- [US Court of Appeals for the Federal Circuit Vocabulary](vocabulary/us-court-of-appeals-for-the-federal-circuit-vocabulary.yml) — Unified taxonomy mapping 3 resources, 4 actions, 0 workflows, and 4 personas across patent law, government contracts, veterans benefits, and federal court data dimensions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
