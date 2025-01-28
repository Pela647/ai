#### Installation 
- This is manual installation and works in macOS/Linux for other methods check [here](https://docs.openwebui.com/).  
- `curl -LsSf https://astral.sh/uv/install.sh | sh` = install [uv](https://docs.astral.sh/uv/) (uv is a single tool to replace pip, pip-tools, pipx, poetry, pyenv, twine, virtualenv ...).  
- `DATA_DIR=~/.open-webui uvx --python 3.11 open-webui@latest serve` = Run Open WebUI, set the `DATA_DIR` environment variable to avoid data loss.  
- OpenwebUI should be available at `http://0.0.0.0:8080/`.