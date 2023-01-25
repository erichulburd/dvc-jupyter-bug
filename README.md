# To reproduce the bug

1. [InstallPoetry](https://python-poetry.org/docs/#installation).
2. Run the following:

```sh
poetry install
poetry shell
jupyter lab
```

Open the `bug.ipynb` notebook. Run the first cell. It will freeze.