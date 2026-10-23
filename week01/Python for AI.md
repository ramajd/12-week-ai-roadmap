[![WATCH](https://img.youtube.com/vi/ygXn5nV5qFc/maxresdefault.jpg)](https://youtu.be/ygXn5nV5qFc)
## VSCode setup
- Extensions: `python`, `pylance`, `jupyter`, `rainbowcsv`, `ruff (formatter - format on save)`
- Settings: 
	- `Python Terminal Execute In File Dir = true`
	- `Tree indent = 20`
- VENV: `CMD-Shift-P` -> `Python create Environment`
- interactive execute:
	- `pip install ipykernel`
	- set related Jupyter setting: `Jupyter > Interactive Window > Text Editor: Execute Selection = true`
## Creating Projects
- kebab-case
-  workspace: file > Save workspace as ... 
## Python Basics
- Tuples
	- immutable (readonly)
	- `point = (1,2); point[0]`
## More Tools:
- `uv`: package manager
	- `un init my-project`
	- `uv add [dependency]`
	- `uv sync`
	- `uv run python file.py`
