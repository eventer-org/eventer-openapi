# The OpenAPI specification of the eventer web API

This is the official [OpenAPI](https://spec.openapis.org/oas/v3.2.0.html) specification for the eventer web API.

A good-looking web version can be found [here](https://apidoc.eventer.app/).

## API Lifecycle

| API | Status | Description |
|-----|--------|-------------|
| **Pods API** (`/pods/{pod}/events`) | **Preferred** | Semantic event data (JSON-LD) from organizer pods |
| **Places API** (`/places`) | Active | Venue/location details, used by both APIs |
| **Events API** (`/events`) | Deprecated | Legacy search across all sources — use the Pods API instead |
