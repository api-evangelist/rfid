# RFID

Radio-Frequency Identification (RFID) is a wireless technology using electromagnetic fields to automatically identify and track tags on objects. RFID powers supply chain visibility, inventory management, asset tracking, access control, and contactless payments across retail, healthcare, manufacturing, and logistics.

**Standards:** https://www.gs1.org/standards/epcis  
**Zebra Developer Portal:** https://developer.zebra.com/products/rfid  
**ClearStream RFID API:** https://www.clearstreamrfid.com/software/integrate/api/

## APIs

### EPCIS 2.0 REST API (GS1 Standard)

The Electronic Product Code Information Services API for capturing and querying supply chain visibility events from RFID-tagged objects.

**Standard:** GS1 EPCIS 2.0  
**Authentication:** Bearer Token

### Zebra Data Services for RFID

Cloud-based APIs for RFID reader management and tag data collection via Zebra Technologies.

**Portal:** https://developer.zebra.com/data-services-rfid-developer-guide

### ClearStream RFID REST API

RESTful API for integrating RFID reader and Bluetooth Beacon data into applications.

**Documentation:** https://www.clearstreamrfid.com/software/integrate/api/

### Impinj ItemSense RAIN RFID API

APIs for RAIN RFID reader management and item-level inventory visibility.

**Portal:** https://developer.impinj.com/

## Artifacts

### OpenAPI Specs

| File | Description |
|------|-------------|
| [rfid-epcis-openapi.yml](openapi/rfid-epcis-openapi.yml) | GS1 EPCIS 2.0 REST API for event capture and query |

### JSON Schema

| File | Description |
|------|-------------|
| [rfid-epc-event-schema.json](json-schema/rfid-epc-event-schema.json) | EPCIS 2.0 event schema (ObjectEvent, AggregationEvent, etc.) |
| [rfid-tag-schema.json](json-schema/rfid-tag-schema.json) | RFID tag read data schema |

### JSON Structure

| File | Description |
|------|-------------|
| [rfid-epcis-event-structure.json](json-structure/rfid-epcis-event-structure.json) | EPCIS event field documentation |

### JSON-LD

| File | Description |
|------|-------------|
| [rfid-context.jsonld](json-ld/rfid-context.jsonld) | JSON-LD context mapping RFID/EPCIS vocabulary to GS1 references |

### Examples

| File | Description |
|------|-------------|
| [rfid-capture-object-event-example.json](examples/rfid-capture-object-event-example.json) | EPCIS ObjectEvent capture (receiving scenario) |
| [rfid-query-events-example.json](examples/rfid-query-events-example.json) | EPCIS event query by EPC and time range |

### Vocabulary

| File | Description |
|------|-------------|
| [rfid-vocabulary.yml](vocabulary/rfid-vocabulary.yml) | RFID and EPCIS domain vocabulary |

## Key Technologies

- **UHF EPC Gen2 / RAIN RFID** — ISO 18000-63, 860-960 MHz, dominant supply chain protocol
- **HF RFID / NFC** — 13.56 MHz, used in payments and access control
- **EPCIS 2.0** — GS1 standard REST API for supply chain event data sharing
- **EPC** — Electronic Product Code, GS1's unique object identifier standard

## Maintainers

- Kin Lane — kin@apievangelist.com
