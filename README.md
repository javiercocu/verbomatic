# Verbomatic

A Pipecat-based service for voice-enabled, real-time, multimodal AI applications.

## Installation

This project uses [PDM](https://pdm-project.org/) for dependency management. To get started:

1. Install PDM:
```bash
curl -sSL https://raw.githubusercontent.com/pdm-project/pdm/main/install-pdm.py | python3 -
```

2. Install dependencies:
```bash
pdm install
```

3. Install development dependencies:
```bash
pdm install -G test,lint
```

## Development

- Run tests: `pdm run pytest`
- Format code: `pdm run black .`
- Sort imports: `pdm run isort .`
- Type checking: `pdm run mypy .`
- Linting: `pdm run flake8 .`

## License

Proprietary Software - All Rights Reserved

This software is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

### Third-Party Licenses

This project uses Pipecat, which is licensed under the BSD 2-Clause License. See the [LICENSE](LICENSE) file for details.