# eventer — OpenAPI Specification

**eventer** is an open platform for event and cultural data. Its goal is to make event information
discoverable, interoperable, and decentralized — giving every organizer ownership of their own data.

Under the hood, eventer is built on sempods, an open protocol for self-hosted semantic data pods.
Each organizer maintains a pod with their event data; eventer aggregates this information into a
unified discovery experience. The platform is currently used by 3 organizers in the Chemnitz area
(Saxony, Germany).

This repository contains the official [OpenAPI 3.1](https://spec.openapis.org/oas/v3.1.0.html)
specification for the eventer web API. A rendered version is available at
[apidoc.eventer.app](https://apidoc.eventer.app/).

## API Overview

| API | Status | Description |
|-----|--------|-------------|
| **Pods API** (`/pods/{pod}/events`) | **Preferred** | Semantic event data (JSON-LD) from organizer pods |
| **Places API** (`/places`) | Active | Venue/location details, shared across APIs |
| **Events API** (`/events`) | Deprecated | Legacy search — use the Pods API instead |

## Contact

Interested in using eventer or contributing? Open an issue on GitHub or reach out at `contact(at)eventer.app`.
