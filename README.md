# eventer — OpenAPI Specification

**eventer** is an open platform for event and cultural data. Its goal is to make event information
discoverable, interoperable, and decentralized — giving every organizer ownership of their own data.

Under the hood, eventer is built on [sempods](https://www.sempods.org) — an open
[specification](https://spec.sempods.org) for semantic data pods, with a reference implementation
and pods serving live data. Each organizer has a pod holding their own event data; eventer
aggregates across them into one discovery experience. Three organizers in the Chemnitz area
(Saxony, Germany) publish this way today.

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
