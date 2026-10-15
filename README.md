# OREiLO Interactive v2.0

An original OREiLO technology showcase and interactive data intelligence application.

## Features

- Responsive OREiLO company website and engineering project showcase
- Interactive Intelligence Studio at `/studio`
- CSV, JSON and JSONL dataset ingestion (10,000 row client limit)
- Dataset profiling, missing values, duplicate detection and inferred field types
- Chart builder: bar, line, area and pie with aggregation
- Searchable data grid, row filtering and CSV export
- Cleaning pipeline with deduplication and execution history
- AI-assisted dataset Q&A using optional OpenAI-compatible API
- Deterministic local analysis when AI is not configured
- GitHub repository data integration
- Contact form (configure CONTACT_WEBHOOK_URL for delivery)
- REST routes for analysis, cleaning and insights
- Metadata, sitemap, robots and automated unit tests

## Run

```bash
npm install
npm run dev
```

Visit `http://localhost:3000` or `/studio`.

Copy `.env.example` to `.env.local` and configure credentials for optional services.

## Verification

```bash
npm test
npm run build
```

## Limits and deployment

This is a substantial standalone OREiLO implementation, not a copy of the reference portfolio. It is not a feature-for-feature reproduction of every original integration: live GitHub timelines, data warehouse connections, production-grade ETL orchestration and WebGL 3D scenes are not included. The studio currently operates on uploaded data in browser memory; no user account or persistence is implemented. Production deployments should add authentication, rate limits, upload constraints, and monitoring.

## Ownership

Copyright (c) 2026 OREiLO. MIT License. Third-party dependencies retain their own licenses.
