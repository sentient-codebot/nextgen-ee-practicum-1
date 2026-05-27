# NextGenEE Practicum 1

This folder contains the student version of practicum 1: getting started with
PowerGridModel and running a basic power flow calculation.

## Prerequisites

1. Install `uv`: <https://docs.astral.sh/uv/getting-started/installation/>
2. Open this folder in VS Code, PyCharm, or another Python editor.

## Setup

From this folder, install the Python environment:

```bash
uv sync
```

Then select the Python interpreter from `.venv` in your editor.

## Running the Practicum

Run these scripts in order:

```text
practicum_1_first_step_tutorial.py
practicum_1_arena_65_power_flow.py
```

The provided data files are under `data/`, and the plotting helper is under
`plot_utils/`.

## Expected Work

In this practicum, you will:

1. Build a small PowerGridModel example.
2. Run a one-time power flow calculation.
3. Load a realistic grid model from JSON data.
4. Inspect node voltage and line loading results.
