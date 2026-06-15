# Varian Medical Systems (varian-medical-systems)

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
