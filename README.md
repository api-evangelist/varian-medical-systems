# Varian Medical Systems

Varian Medical Systems is a leading manufacturer of medical devices and software for treating cancer with radiotherapy, radiosurgery, proton therapy, and brachytherapy. Acquired by Siemens Healthineers in 2021, Varian provides the ARIA Oncology Information System (OIS) and developer APIs enabling integration with clinical workflows, EHR systems, and the broader healthcare ecosystem using HL7, DICOM, and FHIR standards.

**Website:** [https://www.varian.com](https://www.varian.com)
**Siemens Healthineers Cancer Care:** [https://cancercare.siemens-healthineers.com](https://cancercare.siemens-healthineers.com)
**FHIR Developer Portal:** [https://varian.dynamicfhir.com](https://varian.dynamicfhir.com)

## APIs

### ARIA FHIR API
The Varian ARIA FHIR R4 API provides SMART on FHIR access to oncology clinical data from the ARIA Oncology Information System. Read-only access to patient demographics, diagnoses, procedures, observations, care plans, and medications.

- **Documentation:** [https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation](https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation)
- **Capability Statement:** [https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata](https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata)
- **OpenAPI Spec:** [openapi/varian-aria-fhir-openapi.yml](openapi/varian-aria-fhir-openapi.yml)

### ARIA Access API
Legacy SOAP/REST web services for accessing core ARIA entities (patients, appointments, treatment plans). Deployed on-premise at healthcare institutions.

- **Documentation:** [ARIA API Review](https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis)

## Authentication

SMART on FHIR OAuth 2.0 authorization:

- Authorization: `https://varian-smart.dynamicfhir.com/core/connect/authorize`
- Token: `https://varian-smart.dynamicfhir.com/core/connect/token`

## Supported FHIR Resources

| Resource | Operations |
|---|---|
| Patient | Search, Read |
| Condition | Search, Read |
| Procedure | Search, Read |
| Observation | Search, Read |
| DiagnosticReport | Search, Read |
| CarePlan | Search, Read |
| MedicationRequest | Search, Read |
| AllergyIntolerance | Search, Read |
| DocumentReference | Search, Read |
| Goal | Search, Read |

## Artifacts

### OpenAPI Specifications

- [openapi/varian-aria-fhir-openapi.yml](openapi/varian-aria-fhir-openapi.yml) - ARIA FHIR R4 API

### Spectral Rules

- [rules/varian-rules.yml](rules/varian-rules.yml) - API linting rules for ARIA FHIR conventions

### Naftiko Capabilities

- [capabilities/shared/varian-aria-fhir.yaml](capabilities/shared/varian-aria-fhir.yaml) - Shared per-API capability definition
- [capabilities/oncology-clinical-data.yaml](capabilities/oncology-clinical-data.yaml) - Oncology clinical data workflow (8 tools)

### JSON Schema

- [json-schema/varian-patient-schema.json](json-schema/varian-patient-schema.json)

### JSON Structure

- [json-structure/varian-patient-structure.json](json-structure/varian-patient-structure.json)

### JSON-LD Context

- [json-ld/varian-medical-systems-context.jsonld](json-ld/varian-medical-systems-context.jsonld)

### Examples

- [examples/varian-search-patients-example.json](examples/varian-search-patients-example.json)
- [examples/varian-search-conditions-example.json](examples/varian-search-conditions-example.json)

### Vocabulary

- [vocabulary/varian-vocabulary.yml](vocabulary/varian-vocabulary.yml)

## Standards Support

- **FHIR R4** - Primary API standard via ConnectEHR/SMART on FHIR
- **HL7 v2.x** - ADT and scheduling integration with hospital systems
- **DICOM RT** - Treatment plan, dose, and structure set data exchange
- **mCODE** - Minimal Common Oncology Data Elements profiles
- **XRTS** - Cross-vendor radiation therapy summaries

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

---
*Profiled: 2026-05*
