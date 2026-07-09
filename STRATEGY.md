# Strategy — langfuse

## What this is
A local clone of the upstream open-source [Langfuse](https://langfuse.com) project — an LLM engineering platform for tracing, evaluation, and prompt management (Next.js web app + Express worker + Postgres/ClickHouse/Redis). This is a self-hosted mirror of a third-party product, not something Bruno is building to sell.

## Role in the portfolio
Internal tooling. The live Caddy site proxies `/langfuse*` to `127.0.0.1:3030`, meaning this instance is actually deployed and reachable from the kiosk/portal surface — most likely as observability/tracing infrastructure for Bruno's own LLM-backed projects (e.g. the Hermes→litellm wiring noted in the kiosk dashboard docs, or other AI-assisted repos in the portfolio such as IVDR.LLM). It is infrastructure those projects can lean on, not a monetized product of its own.

## Scoring
Not applicable — infrastructure/tooling (self-hosted upstream mirror), not a scored business asset.
