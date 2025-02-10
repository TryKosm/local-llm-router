# Local Llm Router

Route between local and fallback LLM providers.

![CI](https://github.com/TryKosm/local-llm-router/actions/workflows/ci.yml/badge.svg)

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
