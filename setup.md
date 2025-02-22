I am trying to use `uv` for this project.


```bash
git clone git@github.com:bpiyush/CMD.git
cd CMD

# Initialize the project
uv init

# Need to install dependencies
uv add -r requirements.txt

uv lock
uv sync
source .venv/bin/activate

```
