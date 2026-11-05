# Ironwood Schema

Versioned schema registry and compatibility tooling for Ironwood tables.

## Overview

This directory contains the public, finished source for Ironwood Schema. It is the
release that powers our managed offering and it is supported on a best-effort
basis by the Ironwood Data open-source team.

## Key Features

- **Compatibility checks**: Backward, forward and full compatibility modes.
- **Version pinning**: Consumers can pin a schema generation explicitly.
- **Migration planner**: Generates safe migration steps for breaking changes.

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
cd ironwood-toolkit/ironwood-schema
pip install -r requirements.txt
python examples/quickstart.py
```

## Contributing

Issues and pull requests are welcome. Please run the unit tests before opening a
pull request.

## License

Released under the Apache-2.0 License.
