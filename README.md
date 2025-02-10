# local-llm-gateway

![CI](https://github.com/TryKosm/local-llm-gateway/actions/workflows/ci.yml/badge.svg)

TypeScript gateway for routing chat requests across local and remote LLM providers with fallback rules.

## Features
- Provider routing by model family.
- Automatic fallback for unhealthy providers.
- Structured health checks and route metadata.
- Unit tests for routing and fallback behavior.

## Development
```bash
npm install
npm test
npm run build
```
