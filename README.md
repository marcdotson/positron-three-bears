# Project Template


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim
veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea
commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
occaecat cupidatat non proident, sunt in culpa qui officia deserunt
mollit anim id est laborum.

## Project Organization

- `/code` Scripts with prefixes (e.g., `01_import-data.py`,
  `02_clean-data.py`) and functions in `/code/src`.
- `/data` Simulated and real data, the latter not pushed.
- `/figures` PNG images and plots.
- `/output` Output from model runs, not pushed.
- `/presentations` Presentation slides.
- `/private` A catch-all folder for miscellaneous files, not pushed.
- `/writing` Paper, report, and case studies.
- `/.quarto` Hidden Quarto project library, not pushed.
- `/.venv` Hidden Python project library, not pushed.
- `.gitignore` Hidden Git instructions file.
- `.python-version` Hidden Python version file.
- `LICENSE` MIT License for “as is” permission.
- `README.md` GitHub-flavored markdown README rendered from
  `README.qmd`.
- `README.qmd` Quarto markdown README to edit and render into
  `README.md`.
- `_quarto.yml` Quarto project configuration file.
- `pyproject.toml` Python project environment configuration file.
- `uv.lock` Python project environment lockfile.

## Project Environment

After cloning this repository, go to the project’s terminal in Positron
and run `uv run` to create the `/.venv` project library and install the
specified Python and library versions.

For more details on using Positron, Python, Quarto, and GitHub see the
[data stack](https://github.com/marcdotson/data-stack) repository.
