# example-python

A basic Python project scaffolded with `uv`.

## Installation

Prod: 
```bash
uv sync --no-dev --group prod
```

Dev (by default it chooses dev group and not prod as dev is firsti n the list):
```
uv sync
```

## Usage

Run the main script:

```bash
uv run example-python
```

## Testing

Run tests with `pytest`:

```bash
uv run pytest
```
