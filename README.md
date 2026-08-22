# Varian Medical Systems (varian-medical-systems)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Varian Medical Systems is a leading manufacturer of medical devices and software for treating cancer with radiotherapy, radiosurgery, proton therapy, and brachytherapy. Acquired by Siemens Healthineers in 2021, Varian provides the ARIA Oncology Information System (OIS) and developer APIs enabling integration with clinical workflows, EHR systems, and the broader healthcare ecosystem using HL7, DICOM, and FHIR standards.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Healthcare
- Oncology
- Medical Devices
- FHIR
- Radiation Therapy
- Health IT

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### ARIA FHIR API

The Varian ARIA FHIR R4 API provides SMART on FHIR access to oncology clinical data from the ARIA Oncology Information System. Supports read and search operations for Patient, Condition, Procedure, Observation, DiagnosticReport, CarePlan, MedicationRequest, and other clinical resources relevant to cancer care.

- **Human URL:** [https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation](https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation)
- **Base URL:** `https://varian.dynamicfhir.com/fhir/varian/basepractice/r4`

#### Tags

- Healthcare
- Oncology
- FHIR
- Health IT
- Interoperability

#### Properties

- [Documentation](https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation)
- [Capability Statement](https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/openapi/varian-aria-fhir-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/varian-aria-fhir.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/varian-aria-fhir.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ARIA Access API

The legacy ARIA Access API provides SOAP and REST access to core ARIA entities including patients, appointments, prescriptions, treatment plans, orders, and administrative data. Deployed on-premise within the healthcare institution's infrastructure.

- **Human URL:** [https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis](https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis)
- **Base URL:** `https://localhost:55051/Gateway/Service.svc`

#### Tags

- Healthcare
- Oncology
- SOAP
- Web Services
- Health IT

#### Properties

- [Documentation](https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis)
- [Postman Collection](collections/varian-aria-fhir.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/varian-aria-fhir.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/varian-medical-systems)
- [Portal](https://varian.dynamicfhir.com/varian/basepractice/r4)
- [Documentation](https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation)
- [Capability Statement](https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata)
- [Documentation](https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis)
- [Product](https://cancercare.siemens-healthineers.com/products/software/digital-oncology/oncology-management-systems/aria-oncology-information-system)
- [Website](https://www.varian.com)
- [Website](https://cancercare.siemens-healthineers.com)
- [Standard](https://hl7.org/fhir/R4/)
- [Standard](https://www.dicomstandard.org)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
