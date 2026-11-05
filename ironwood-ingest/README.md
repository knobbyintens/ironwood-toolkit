# Ironwood Ingest

High-throughput streaming ingestion for the Ironwood lakehouse.

## Overview

This directory contains the public, finished source for Ironwood Ingest. It is the
release that powers our managed offering and it is supported on a best-effort
basis by the Ironwood Data open-source team.

## Key Features

- **Exactly-once delivery**: Append-only event streams land once, even across retries.
- **Schema-on-write**: Typed landing zones keep downstream consumers honest.
- **Back-pressure aware**: The writer adapts to lakehouse commit latency.

## Directory Structure

```
├── src/
│   ├── core.py
│   ├── cli.py
│   └── io_utils.py
├── docs/
│   ├── index.md
│   └── usage.md
├── examples/
│   └── quickstart.py
├── tests/
│   └── test_core.py
├── requirements.txt
└── .gitignore
```

## Quick Start

```bash
git clone https://github.com/ironwood-data/ironwood-toolkit.git
cd ironwood-toolkit/ironwood-ingest
pip install -r requirements.txt
python examples/quickstart.py
```

## Contributing

Issues and pull requests are welcome. Please run the unit tests before opening a
pull request.

## License

Released under the Apache-2.0 License.
