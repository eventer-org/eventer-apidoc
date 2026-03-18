# eventer — API Documentation

Static site that renders the eventer OpenAPI specification using [Redoc](https://github.com/Redocly/redoc).

Deployed at [apidoc.eventer.app](https://apidoc.eventer.app/).

## How it works

- The [eventer-openapi](https://github.com/eventer-org/eventer-openapi) repo holds the source spec
- Its CI bundles the multi-file spec into `dist/openapi.yaml`
- This site loads the bundled spec at runtime via Redoc (v2.5.2)
