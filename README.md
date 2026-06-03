# Compass

Compass is the hyperparameter optimization and model evaluation package in the Poseigen family.
It provides utilities for generating and scoring hyperparameter candidates, model ensembling, and statistical assessment.

## Features

- Random candidate generation across continuous and categorical hyperparameter spaces.
- Candidate scoring with optional model repeats and top-k selection.
- Average ensembles from model repeat sets.
- Bootstrap ensembles for statistical assessment.

## Installation

Install from PyPI:

```bash
pip install poseigen_compass
```

For local development, install from source using your preferred editable-install workflow.

## Usage

Import modules directly:

```python
import poseigen_compass as co
```

## Project Status

poseigen_compass is in active development and is intended to support hyperparameter search and evaluation workflows across the Poseigen ecosystem.

## Related Projects

- poseigen_seaside: shared utilities and metrics foundation.

## License

This project is released under the MIT License.