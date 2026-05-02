# Rainbow.AI

Rainbow.AI provides hyperlocal precipitation forecasting APIs that deliver minute-by-minute rain and snow predictions at 1 km resolution, helping businesses and developers optimize weather-sensitive operations with accurate nowcast and map tile data globally.

- **Website:** [rainbow.ai](https://www.rainbow.ai)
- **Developer Portal:** [developer.rainbow.ai](https://developer.rainbow.ai/)
- **Documentation:** [doc.rainbow.ai](https://doc.rainbow.ai)
- **Pricing:** [rainbow.ai/business](https://www.rainbow.ai/business)
- **Terms of Service:** [developer.rainbow.ai/terms-of-service](https://developer.rainbow.ai/terms-of-service)
- **Status:** [status.rainbow.ai](https://status.rainbow.ai)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Weather, Precipitation, Forecasting, Nowcast, Radar, Tiles, Geospatial

## APIs

### Nowcast API
Minute-by-minute precipitation forecasts for the next 4 hours at 1 km resolution for any global location, updated every 10 minutes.

- **Base URL:** `https://api.rainbow.ai/v1`
- **Authentication:** API key via `Ocp-Apim-Subscription-Key` header or `token` query parameter
- **OpenAPI:** [openapi/rainbow-ai-nowcast-openapi.yml](openapi/rainbow-ai-nowcast-openapi.yml)

### Tiles API
Global 256x256 PNG weather map tiles via XYZ CDN for precipitation visualization, supporting real-time and forecasted layers.

- **Base URL:** `https://api.rainbow.ai/v1`
- **Authentication:** API key via `Ocp-Apim-Subscription-Key` header or `token` query parameter
- **OpenAPI:** [openapi/rainbow-ai-tiles-openapi.yml](openapi/rainbow-ai-tiles-openapi.yml)

## Artifacts

### OpenAPI Specifications
| File | Description |
|---|---|
| [openapi/rainbow-ai-nowcast-openapi.yml](openapi/rainbow-ai-nowcast-openapi.yml) | Nowcast API — precipitation forecasting |
| [openapi/rainbow-ai-tiles-openapi.yml](openapi/rainbow-ai-tiles-openapi.yml) | Tiles API — weather map tiles |

### JSON Schema
| File | Description |
|---|---|
| [json-schema/rainbow-ai-nowcast-response-schema.json](json-schema/rainbow-ai-nowcast-response-schema.json) | Nowcast response schema |

### JSON Structure
| File | Description |
|---|---|
| [json-structure/rainbow-ai-nowcast-structure.json](json-structure/rainbow-ai-nowcast-structure.json) | Nowcast response structure documentation |

### JSON-LD
| File | Description |
|---|---|
| [json-ld/rainbow-ai-context.jsonld](json-ld/rainbow-ai-context.jsonld) | Linked data context mapping |

### Examples
| File | Description |
|---|---|
| [examples/rainbow-ai-get-nowcast-example.json](examples/rainbow-ai-get-nowcast-example.json) | Nowcast API request/response example |
| [examples/rainbow-ai-get-map-tile-example.json](examples/rainbow-ai-get-map-tile-example.json) | Map tile request example |
| [examples/rainbow-ai-get-radar-data-example.json](examples/rainbow-ai-get-radar-data-example.json) | Radar data request/response example |

### Rules
| File | Description |
|---|---|
| [rules/rainbow-ai-rules.yml](rules/rainbow-ai-rules.yml) | Spectral ruleset for Rainbow.AI API conventions |

### Capabilities
| File | Description |
|---|---|
| [capabilities/weather-intelligence.yaml](capabilities/weather-intelligence.yaml) | Unified weather intelligence workflow (Nowcast + Tiles) |
| [capabilities/shared/nowcast.yaml](capabilities/shared/nowcast.yaml) | Shared Nowcast API definition |
| [capabilities/shared/tiles.yaml](capabilities/shared/tiles.yaml) | Shared Tiles API definition |

### Vocabulary
| File | Description |
|---|---|
| [vocabulary/rainbow-ai-vocabulary.yml](vocabulary/rainbow-ai-vocabulary.yml) | Meteorological and API domain vocabulary |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
