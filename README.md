# RFID (rfid)

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

Radio-Frequency Identification (RFID) is an automatic identification technology that uses radio waves to read and capture information stored on a tag attached to an object. RFID powers supply chain visibility, inventory management, asset tracking, access control, and contactless payments. The RFID ecosystem includes hardware vendors (Zebra, Impinj, Alien Technology), software platforms (ClearStream, TagMatiks, Jetstream), and open standards (GS1 EPCIS, EPC Tag Data Standard, ISO 18000 series).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- RFID
- IoT
- Supply Chain
- Inventory Management
- Asset Tracking
- GS1
- EPCIS

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Zebra Data Services for RFID

Zebra Technologies provides cloud-based REST APIs for managing RFID readers, collecting tag data, and integrating RFID intelligence into enterprise applications. Cloud Connect for RFID enables remote reader management and data collection via REST API.

- **Human URL:** [https://developer.zebra.com/data-services-rfid-developer-guide](https://developer.zebra.com/data-services-rfid-developer-guide)
- **Base URL:** `https://api.zebra.com`

#### Tags

- RFID
- Asset Tracking
- Inventory
- Zebra

#### Properties

- [Documentation](https://developer.zebra.com/data-services-rfid-developer-guide)
- [Portal](https://developer.zebra.com/products/rfid)
- [Postman Collection](collections/rfid-epcis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rfid-epcis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ClearStream RFID REST API

ClearStream provides a RESTful API for RFID and Bluetooth Beacon technology, giving developers full control of RFID readers and gateways to integrate tag data into existing applications and websites.

- **Human URL:** [https://www.clearstreamrfid.com/software/integrate/api/](https://www.clearstreamrfid.com/software/integrate/api/)

#### Tags

- RFID
- Bluetooth Beacon
- Asset Tracking
- REST API

#### Properties

- [Documentation](https://www.clearstreamrfid.com/software/integrate/api/)
- [Postman Collection](collections/rfid-epcis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rfid-epcis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Impinj ItemSense RAIN RFID API

Impinj provides APIs for RAIN RFID reader management and item location data, enabling real-time item-level inventory visibility in retail, healthcare, and manufacturing environments.

- **Human URL:** [https://developer.impinj.com/](https://developer.impinj.com/)

#### Tags

- RFID
- RAIN RFID
- Retail
- Healthcare
- Impinj

#### Properties

- [Documentation](https://developer.impinj.com/)
- [Postman Collection](collections/rfid-epcis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rfid-epcis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GS1 EPCIS API

The Electronic Product Code Information Services (EPCIS) is GS1's standard for sharing supply chain visibility data. EPCIS 2.0 supports REST/HTTP and JSON-LD for capturing and querying RFID events including Object, Aggregation, Transaction, Transformation, and Association events.

- **Human URL:** [https://www.gs1.org/standards/epcis](https://www.gs1.org/standards/epcis)

#### Tags

- GS1
- EPCIS
- Supply Chain
- EPC
- Standard

#### Properties

- [Documentation](https://www.gs1.org/standards/epcis)
- [Postman Collection](collections/rfid-epcis.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rfid-epcis.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://developer.zebra.com/products/rfid)
- [Website](https://www.clearstreamrfid.com/)
- [Website](https://www.gs1.org/standards/epcis)
- [Standard](https://www.gs1.org/standards/epc-rfid-epcis-id-keys/epc-rfid-tds/1-12)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
