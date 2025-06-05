## Init projetc
`uv init <my project>`

`uv add <package>`
`uv remove <package>`

`uv sync` with what is installed

`uv lock ...`generate the lock file

`uv tree`


## Tools

`uv tool dir`

`uv tool update-shell`

`uv tool install ruff`
 
`uv tool run ruff`

`uv tool run ruff check`

`uvx ruff check`

`uv tool upgrade ruff`


## Python versions

All the available python versions and paths
- `uv python list`

Install specific version
- `uv python install 3.12.0`

Create venv
- `uv venv --python 3.13.0`