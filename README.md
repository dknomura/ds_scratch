# ds_scratch
Using uv, install instructions here https://github.com/astral-sh/uv

## Setup
```bash
# Install dependencies
uv sync
```

Create new notebook and run in VS Code with jupyter extension https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter. 

To print plot graphs to pdf run then notebook and set the renderer to vscode and pdf 

```bash
uv run jupyter notebook
```

```py
fig.show(renderer="pdf+vscode")
```
