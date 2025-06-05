## Init project

Install uv
`pip install uv`

`uv init <my project>`

`uv add <package>`
`uv remove <package>`

`uv sync` with what is installed

`uv lock ...`generate the lock file

`uv tree`


## Tools

`uv tool dir`

`uv tool update-shell`

Executa a tool sem instalar
`uv tool run ruff`

`uv tool run ruff check`

`uvx ruff check`


Instala a tool
`uv tool install ruff`

`uv tool list`

`uv tool upgrade ruff`

`uv tool upgrade --all`

## Python versions

All the available python versions and paths
- `uv python list`

Install specific version
- `uv python install 3.12.0`

Create venv (embora n precise geralmente)
- `uv venv --python 3.13.0`


### Referencias
- Arjan codes https://www.youtube.com/watch?v=qh98qOND6MI
- Corey Schafer https://www.youtube.com/watch?v=AMdG7IjgSPM
- Tech with tim https://www.youtube.com/watch?v=6pttmsBSi8M