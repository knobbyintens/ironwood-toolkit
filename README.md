# Ironwood Toolkit

Public source for the Ironwood Data open-source tools. Every tool lives in its
own top-level directory and is maintained independently by its owning team.

| Directory | Tool | Purpose |
| --- | --- | --- |
| `ironwood-ingest/` | Ironwood Ingest | High-throughput streaming ingestion for the Ironwood lakehouse. |
| `ironwood-schema/` | Ironwood Schema | Versioned schema registry and compatibility tooling for Ironwood tables. |
| `ironwood-metrics/` | Ironwood Metrics | Lightweight metrics collection and rollups for Ironwood pipelines. |
| `ironwood-synth/` | Ironwood Synth | Controllable synthetic benchmark generation for lakehouse pipelines. |

## Layout

Each tool directory follows the same internal layout (``src/``, ``docs/``,
``examples/``, ``tests/``) so that build, release and packaging scripts can
treat every component uniformly.

## License

Unless a tool directory states otherwise, everything here is released under the
Apache-2.0 License.
